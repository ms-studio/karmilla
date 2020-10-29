![Sample Image](/documentation/Karmilla_01.jpg)

**Karmilla** is an expanded version of **Karla**. 

Karla is an outstanding grotesque sans serif typeface family created by Jonathan Pinhorn ([@jonpinhorn_type](http://twitter.com/jonpinhorn_type), a graduate of the MA in Typeface Design at the University of Reading), released through Google Webfonts in 2012.

The aim of Karmilla is to offer a workaround for designers who want to use Karla but need support for French, German, Norvegian, Slovak or Icelandic, which requires adding and tweaking some glyphs.

The original Karla font can be found here: https://fonts.google.com/specimen/Karla

The source files have been obtained from https://github.com/google/fonts/tree/master/ofl/karla

## Can I install the font on my computer?

Yes you can! You will find the files in the "fonts > ttf" folder. The .ttf extension stands for "TrueType font", a common format for fonts on Mac OS, Microsoft Windows and Linux.

## Can I use Karmilla as a webfont?

Yes of course! For your convenience, we have generated a webfont, which you can find in the "fonts > webfontkit" folder.

## Where are the source files?

You will find them in the "sources" folder.

## What format are they in?

The contributors are working mostly with [FontForge](https://fontforge.github.io/), and we are currently using the native sfdir (SplineFont Directory) format. This format stores each glyph in a single file. We plan to move to the more widespread UFO format at some point in the future (see [issue #17](https://github.com/ms-studio/karmilla/issues/17)).

To open the font with FontForge, do "File > Open", navigate to "sources" and highlight the "Karmilla-Regular.sfdir" folder, and click "OK" – FontForge will open the font. Don't attempt to open a single .glyph file.

## How to generate fonts?

Here is the convention we are using when we make significant changes, such as adding or improving glyphs:

- Increment the version number, under "Element > Font Info".
- Export a new TTF, via "Generate Fonts > TTF".

## Changes:

Some of the changes we made so far:

* added ß for the German alphabet.
* added characters for the Bulgarian and Russian cyrillic alphabet.
* added characters for the Icelandic alphabet.
* added french quotes «», €, ¥, ᴃ
* added å, ø and æ for Scandinavian languages.
* added ç (cedilla) character for better French support.
* added œ (ligatured o and e) character for better French support.
* added various punctuation marks.
* the q character has been streamlined.
* the position of the typographic apostrophe has been changed, so it matches the height of ascenders (l', d').

See the [FONTLOG.txt](https://github.com/ms-studio/karmilla/blob/master/FONTLOG.txt) for details.

## Examples

- See [images](/documentation/) and [Gallery](/documentation/Gallery.md).
- Used on https://marjorieober.com/

## In Collections:

Karmilla has been included in the following font collections:

- The [Open Font Library](https://fontlibrary.org/en/font/karmilla)
- [Font Squirrel](https://www.fontsquirrel.com/fonts/karmilla)
- [Use & Modify](http://usemodify.com/fonts/karmilla/), curated by [Raphaël Bastide](https://github.com/raphaelbastide)
- Interstice Typothèque, curated by Alexandre Liziard & Étienne Ozeray
- Supertypo, curated by Karol Zaharanski
