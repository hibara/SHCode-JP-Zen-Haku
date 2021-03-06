[English](README.md) / [日本語](README-JP.md)

# SHCode JP Zen Haku

This is a set of Open Type and True Type fonts, which are monospaced fonts for programming and also support Japanese language display such as comment-out.

Also, this font is just "[Source Han Code JP](https://github.com/adobe-fonts/source-han-code-jp)", an open-source font by Adobe, with additional editing for full-width space visualization. Although I changed the font name under "SIL Open Font License", most of the contents except for the full-width space are "Source Han Code JP".

These fonts were created and edited by font production software called "[BirdFont](https://birdfont.org/)" from "Source Han Code JP" of Open Type fonts. The extension "*.bf" is dedicated data to be loaded by the software. You can't open it with other software, and you can't convert it to font data directly.

## License

The same license of "Source Han Code JP" is applied as it, because it is distributed under "SIL Open Font License". For more information, please see the following page.

<https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL_web>
<https://osdn.net/projects/opensource/wiki/SIL_Open_Font_License_1.1>（Japanese）

## Download

If you only want the font data other than the [BirdFont](https://birdfont.org/) data for font editing, you can download it from the following page.
<https://github.com/hibara/SHCode-JP-Zen-Haku/releases>

## About the full-width space

I have been using a similar programming font "[CodeM](https://github.com/MasayukiFukada/CodeMFont)", but I decided to switch to "Source Han Code JP" because of easy to distinguish alphanumeric characters.

However, when I accidentally typed a full-width space, I felt it was easy to make a mistake because it was not visualized in "Source Han Code JP".

In "CodeM", you will see the following:

![alt text](https://raw.githubusercontent.com/hibara/SHCode-JP-Zen-Haku/master/image/CodeM-full-width-space.png)

It's quite convenient and easy to read. So I added my own to make the full-width spaces visible in "Source Han Code JP" as well. Furthermore, I drew a neat square with a dotted line in this version, because the corners are omitted and it may look like a "circle" in "CodeM".

![alt text](https://raw.githubusercontent.com/hibara/SHCode-JP-Zen-Haku/master/image/SHCodeJPZenHaku-full-width-space.png)

The number of full-width space in Unicode is "U+3000". If you want to edit this font with [BirdFont](https://birdfont.org/) software, you can easily import it by copying and pasting the following source code when the font outline is displayed.

```xml
<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.0//EN" "http://www.w3.org/TR/2001/REC-SVG-20010904/DTD/svg10.dtd">

<svg version="1.0" id="glyph_　" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" width="100px" height="98.099999999999994px">
<g id="　">
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M14.08316 113.17372 C14.08316 112.18477 14.08316 110.20687 14.08316 109.21792 C16.05299 109.21792 19.99266 109.21792 21.96249 109.21792 C21.96249 110.20687 21.96249 112.18477 21.96249 113.17372 C19.99266 113.17372 16.05299 113.17372 14.08316 113.17372 z" id="path_　_0" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M29.96327 113.26586 C29.96327 112.27691 29.96327 110.29901 29.96327 109.31006 C31.9331 109.31006 35.87277 109.31006 37.8426 109.31006 C37.8426 110.29901 37.8426 112.27691 37.8426 113.26586 C35.87277 113.26586 31.9331 113.26586 29.96327 113.26586 z" id="path_　_1" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M46.20329 113.40597 C46.20329 112.41702 46.20329 110.43912 46.20329 109.45017 C48.17312 109.45017 52.11279 109.45017 54.08262 109.45017 C54.08262 110.43912 54.08262 112.41702 54.08262 113.40597 C52.11279 113.40597 48.17312 113.40597 46.20329 113.40597 z" id="path_　_2" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M62.18981 113.26586 C62.18981 112.27691 62.18981 110.29901 62.18981 109.31006 C64.15964 109.31006 68.09931 109.31006 70.06914 109.31006 C70.06914 110.29901 70.06914 112.27691 70.06914 113.26586 C68.09931 113.26586 64.15964 113.26586 62.18981 113.26586 z" id="path_　_3" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M18.06283 99.23021 C17.07391 99.223 15.09606 99.20859 14.10714 99.20138 C14.1215 97.2316 14.15022 93.29203 14.16458 91.32225 C15.1535 91.32946 17.13135 91.34388 18.12028 91.35109 Q18.10591 93.32087 18.12208 94.48493 Q18.13826 95.64899 18.06283 99.23021 z" id="path_　_4" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M17.94943 81.3142 C16.96051 81.30699 14.98266 81.29258 13.99374 81.28537 C14.0081 79.31559 14.03682 75.37602 14.05118 73.40624 C15.04011 73.41345 17.01796 73.42787 18.00688 73.43508 Q17.99251 75.40486 18.00869 76.56892 Q18.02486 77.73298 17.94943 81.3142 z" id="path_　_5" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M17.94943 63.39819 C16.96051 63.39098 14.98266 63.37657 13.99374 63.36936 C14.0081 61.39958 14.03682 57.46001 14.05118 55.49023 C15.04011 55.49744 17.01796 55.51186 18.00688 55.51907 Q17.99251 57.48885 18.00869 58.65291 Q18.02486 59.81697 17.94943 63.39819 z" id="path_　_6" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M13.99063 45.207 C13.99063 44.21805 13.99063 42.24015 13.99063 41.2512 C15.96046 41.2512 19.90013 41.2512 21.86996 41.2512 C21.86996 42.24015 21.86996 44.21805 21.86996 45.207 C19.90013 45.207 15.96046 45.207 13.99063 45.207 z" id="path_　_7" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M78.05735 45.32039 C78.05735 44.33144 78.05735 42.35354 78.05735 41.36459 C80.02718 41.36459 83.96685 41.36459 85.93668 41.36459 C85.93668 42.35354 85.93668 44.33144 85.93668 45.32039 C83.96685 45.32039 80.02718 45.32039 78.05735 45.32039 z" id="path_　_8" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M85.9849 99.3436 C84.99598 99.33639 83.01813 99.32198 82.02921 99.31477 C82.04357 97.34499 82.07229 93.40542 82.08665 91.43564 C83.07557 91.44285 85.05343 91.45727 86.04235 91.46448 Q86.02798 93.43426 86.04416 94.59832 Q86.06033 95.76238 85.9849 99.3436 z" id="path_　_9" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M86.09829 81.20081 C85.10937 81.1936 83.13152 81.17919 82.1426 81.17198 C82.15696 79.2022 82.18568 75.26263 82.20004 73.29285 C83.18897 73.30006 85.16682 73.31448 86.15574 73.32169 Q86.14137 75.29147 86.15755 76.45553 Q86.17372 77.61959 86.09829 81.20081 z" id="path_　_10" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M85.9849 63.05802 C84.99598 63.05081 83.01813 63.0364 82.02921 63.02919 C82.04357 61.05941 82.07229 57.11984 82.08665 55.15006 C83.07557 55.15727 85.05343 55.17169 86.04235 55.1789 Q86.02798 57.14868 86.04416 58.31274 Q86.06033 59.4768 85.9849 63.05802 z" id="path_　_11" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M29.97896 45.207 C29.97896 44.21805 29.97896 42.24015 29.97896 41.2512 C31.94879 41.2512 35.88846 41.2512 37.85829 41.2512 C37.85829 42.24015 37.85829 44.21805 37.85829 45.207 C35.88846 45.207 31.94879 45.207 29.97896 45.207 z" id="path_　_12" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M46.08069 45.207 C46.08069 44.21805 46.08069 42.24015 46.08069 41.2512 C48.05052 41.2512 51.99019 41.2512 53.96002 41.2512 C53.96002 42.24015 53.96002 44.21805 53.96002 45.207 C51.99019 45.207 48.05052 45.207 46.08069 45.207 z" id="path_　_13" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M62.18241 45.0936 C62.18241 44.10465 62.18241 42.12675 62.18241 41.1378 C64.15224 41.1378 68.09191 41.1378 70.06174 41.1378 C70.06174 42.12675 70.06174 44.10465 70.06174 45.0936 C68.09191 45.0936 64.15224 45.0936 62.18241 45.0936 z" id="path_　_14" />
<path style="fill:none;stroke:#000000;stroke-width:0px;stroke-linecap: butt;stroke-linejoin: miter;" d="M78.28414 113.24246 C78.28414 112.25351 78.28414 110.27561 78.28414 109.28666 C80.25397 109.28666 84.19364 109.28666 86.16347 109.28666 C86.16347 110.27561 86.16347 112.25351 86.16347 113.24246 C84.19364 113.24246 80.25397 113.24246 78.28414 113.24246 z" id="path_　_15" />
</g>
</svg>
<!-- BirdFontClipboard
BF glyph: U+3000
BF name: 　
BF unassigned: false
BF left: 0
BF right: 100
BF path: S 14.08316,0.12628 L 14.08316,4.08208 L 21.96249,4.08208 L 21.96249,0.12628 L 14.08316,0.12628
BF stroke: 0
BF path: S 29.96327,0.03414 L 29.96327,3.98994 L 37.8426,3.98994 L 37.8426,0.03414 L 29.96327,0.03414
BF stroke: 0
BF path: S 46.20329,-0.10597 L 46.20329,3.84983 L 54.08262,3.84983 L 54.08262,-0.10597 L 46.20329,-0.10597
BF stroke: 0
BF path: S 62.18981,0.03414 L 62.18981,3.98994 L 70.06914,3.98994 L 70.06914,0.03414 L 62.18981,0.03414
BF stroke: 0
BF path: S 18.06283,14.06979 L 14.10714,14.09862 L 14.16458,21.97775 L 18.12028,21.94891 D 18.10591,19.97913 18.13826,17.65101 18.06283,14.06979
BF stroke: 0
BF path: S 17.94943,31.9858 L 13.99374,32.01463 L 14.05118,39.89376 L 18.00688,39.86492 D 17.99251,37.89514 18.02486,35.56702 17.94943,31.9858
BF stroke: 0
BF path: S 17.94943,49.90181 L 13.99374,49.93064 L 14.05118,57.80977 L 18.00688,57.78093 D 17.99251,55.81115 18.02486,53.48303 17.94943,49.90181
BF stroke: 0
BF path: S 13.99063,68.093 L 13.99063,72.0488 L 21.86996,72.0488 L 21.86996,68.093 L 13.99063,68.093
BF stroke: 0
BF path: S 78.05735,67.97961 L 78.05735,71.93541 L 85.93668,71.93541 L 85.93668,67.97961 L 78.05735,67.97961
BF stroke: 0
BF path: S 85.9849,13.9564 L 82.02921,13.98523 L 82.08665,21.86436 L 86.04235,21.83552 D 86.02798,19.86574 86.06033,17.53762 85.9849,13.9564
BF stroke: 0
BF path: S 86.09829,32.09919 L 82.1426,32.12802 L 82.20004,40.00715 L 86.15574,39.97831 D 86.14137,38.00853 86.17372,35.68041 86.09829,32.09919
BF stroke: 0
BF path: S 85.9849,50.24198 L 82.02921,50.27081 L 82.08665,58.14994 L 86.04235,58.1211 D 86.02798,56.15132 86.06033,53.8232 85.9849,50.24198
BF stroke: 0
BF path: S 29.97896,68.093 L 29.97896,72.0488 L 37.85829,72.0488 L 37.85829,68.093 L 29.97896,68.093
BF stroke: 0
BF path: S 46.08069,68.093 L 46.08069,72.0488 L 53.96002,72.0488 L 53.96002,68.093 L 46.08069,68.093
BF stroke: 0
BF path: S 62.18241,68.2064 L 62.18241,72.1622 L 70.06174,72.1622 L 70.06174,68.2064 L 62.18241,68.2064
BF stroke: 0
BF path: S 78.28414,0.05754 L 78.28414,4.01334 L 86.16347,4.01334 L 86.16347,0.05754 L 78.28414,0.05754
BF stroke: 0
BF end -->
```

## Font installation

* [OS X](http://support.apple.com/kb/HT2509)
* [Windows](http://windows.microsoft.com/en-us/windows-vista/install-or-uninstall-fonts)
* [Linux/Unix-based systems](https://github.com/adobe-fonts/source-code-pro/issues/17#issuecomment-8967116)

## Support

Basically, there are no guarantees or support, but if you have any suggestions or requests, please add them to the Issues of this project, or contact us below. I will help you as possible.

[Mituhiro Hibara](mailto:m@hibara.org)
