# Iota
Iota is a single line sans serif typeface, designed with Metapost. Based on Metafont, Metapost is an open source programming language that allows you to draw figures, and therefore characters. Metapost describes the letter by its "ductus", its structure.

## Resources
The SVG export was made possible by the Single-line Relief work done by the Isdat-type
https://github.com/isdat-type/Relief-SingleLine.git

## Inkscape + Hershey Text Extension SVG fonts method
→fonts/open_svg/

First install IOTA-Outline-Regular.otf on your system; then copy IOTA-Singleline-Regular.svg there:

• (macOS)

/Applications/Inkscape.app/Contents/Resources/share/inkscape/extensions/svg_fonts

• (Windows)

C:\Program Files\Inkscape\share\inkscape\extensions\svg_fonts

Only for Windows users: if you can not use IOTA-Singleline-Regular.svg even if effectively copied in the / svg_fonts folder, try the following action: right-click on IOTA-Singleline-Regular.svg then select / Properties / Security / Unlock / Apply.

Compose your layout in Inkscape using IOTA-Outline-Regular.otf, launch Hershey Text Extension (now available by default) to render your text blocks as single-line letters: go to / Extension / Text / Hershey Text.

Then, in font select Other (bottom of the list after the existing Hershey fonts) and type IOTA-Singleline-Regular in the next field of the dialog box as a path-name, then apply rendering.

Beware to first copy your source text blocks: after the Hershey Text Extension rendering process, texts are becoming not editable. Hershey Text Extension unfortunately apparently disables the kerning values even if truly embedded in the SVG font.

## Content of the directory

- IOTA Outline
	- OTF & TTF files
    - UFO file
	- Glyphs file

- IOTA Singleline
	- SVG font file
    - UFO file
	- Glyphs file

- Fontlog  

- OFL Licence

## Coverage 

IOTA contains 355 glyphs

Support for 86 languages detected:
Afrikaans Albanian Asu Basque Bemba Bena Breton Catalan Chiga Colognian Cornish Croatian Czech Danish Dutch English Estonian Filipino Finnish French Friulian Galician Ganda German Gusii Hungarian Inari Sami Indonesian Irish Italian Jola-Fonyi Kabuverdianu Kalenjin Kinyarwanda Latvian Lithuanian Lower Sorbian Luo Luxembourgish Luyia Machame Makhuwa-Meetto Makonde Malagasy Maltese Manx Morisyen Northern Sami North Ndebele Norwegian Bokmål Norwegian Nynorsk Nyankole Oromo Polish Portuguese Quechua Romanian Romansh Rombo Rundi Rwa Samburu Sango Sangu Scottish Gaelic Sena Serbian Shambala Shona Slovak Soga Somali Spanish Swahili Swedish Swiss German Taita Teso Turkish Upper Sorbian Uzbek (Latin) Volapük Vunjo Welsh Western Frisian Zulu

## Specimen
![Specimen 1]()

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. 
This license is copied below, and is also available with a FAQ at 
http://scripts.sil.org/OFL

## Repository Layout

This font repository follows the Unified Font Repository v2.0, 
a standard way to organize font project source files. Learn more at 
https://github.com/raphaelbastide/Unified-Font-Repository