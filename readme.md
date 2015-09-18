**Karmilla** is a slightly modified version of **Karla**. 

Karla is an outstanding grotesque sans serif typeface family created by Jonathan Pinhorn ([@jonpinhorn_type](http://twitter.com/jonpinhorn_type), a graduate of the MA in Typeface Design at the University of Reading), released through Google Webfonts in 2012.

The aim of Karmilla is to offer a workaround for designers who want to use Karla on a French language website, which requires adding and tweaking some glyphs.

The original Karla font can be found here: http://www.google.com/webfonts/specimen/Karla

The source files have been obtained from http://code.google.com/p/googlefontdirectory/ 

## Where are the source files?

The contributors are working mostly with FontForge, and we are currently using the native sfdir (SplineFont Directory) format. This format stores each glyph in a single file. We plan to move to the more widespread UFO format in the near future (see [issue #17](https://github.com/ms-studio/karmilla/issues/17)).

To open the font via FontForge, do "File > Open", navigate to and highlight the "Karmilla-Regular.sfdir" folder, and click "OK" – FontForge will then open the font. Don't attempt to open a single .glyph file.

## How to generate fonts?

Here is the convention we are using we make changes, such as adding or improving glyphs:
- Change the version number, under Element > Font Info
- Export a new TTF, via Generate Fonts > TTF.
- We name the TTF with the version appended to the filename, such as Karmilla-Regular-013.ttf - this makes it easier to test and compare different versions.

## Changes:

Some of the changes we made so far:

* added french quotes «», €, ᴃ
* improved éóíú on retina screens.
* added å for Scandinavian languages.
* added ç (cedilla) character for better French support.
* added œ (ligatured o and e) character for better French support.
* added various punctuation marks.
* the q character has been streamlined.
* the position of the typographic apostrophe has been changed, so it matches the height of ascenders (l', d').

See the [FONTLOG.txt](https://github.com/ms-studio/karmilla/blob/master/FONTLOG.txt) for details.
