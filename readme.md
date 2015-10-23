**Karmilla** is a slightly modified version of **Karla**. 

Karla is an outstanding grotesque sans serif typeface family created by Jonathan Pinhorn ([@jonpinhorn_type](http://twitter.com/jonpinhorn_type), a graduate of the MA in Typeface Design at the University of Reading), released through Google Webfonts in 2012.

The aim of Karmilla is to offer a workaround for designers who want to use Karla but need support for French, German, Norvegian, Slovak or Icelandic, which requires adding and tweaking some glyphs.

The original Karla font can be found here: http://www.google.com/webfonts/specimen/Karla

The source files have been obtained from https://github.com/google/fonts/tree/master/ofl/karla

## Can I install the font on my computer?

Yes you can! You will find the files in the "ttf" folder. The .ttf extension stands for "TrueType font", a common format for fonts on Mac OS, Microsoft Windows and Linux.

## Can I use Karmilla as a webfont?

Yes of course! For your convenience, we have generated a webfont, which you can find in the "webfontkit" folder.

## Where are the source files?

You will find them in the "src" folder.

## What format are they in?

The contributors are working mostly with FontForge, and we are currently using the native sfdir (SplineFont Directory) format. This format stores each glyph in a single file. We plan to move to the more widespread UFO format at some point in the future (see [issue #17](https://github.com/ms-studio/karmilla/issues/17)).

To open the font with FontForge, do "File > Open", navigate to "/src/" and highlight the "Karmilla-Regular.sfdir" folder, and click "OK" – FontForge will open the font. Don't attempt to open a single .glyph file.

## How to generate fonts?

Here is the convention we are using when we make significant changes, such as adding or improving glyphs:

- Increment the version number, under "Element > Font Info".
- Export a new TTF, via "Generate Fonts > TTF".
- We name the TTF with the version appended to the filename, such as "Karmilla-Regular-014.ttf" - this makes it easier to test and compare different versions.

## Changes:

Some of the changes we made so far:

* added ß for the German alphabet.
* added characters for the Icelandic alphabet.
* added french quotes «», €, ¥, ᴃ
* added å, ø and æ for Scandinavian languages.
* added ç (cedilla) character for better French support.
* added œ (ligatured o and e) character for better French support.
* added various punctuation marks.
* the q character has been streamlined.
* the position of the typographic apostrophe has been changed, so it matches the height of ascenders (l', d').

See the [FONTLOG.txt](https://github.com/ms-studio/karmilla/blob/master/FONTLOG.txt) for details.
