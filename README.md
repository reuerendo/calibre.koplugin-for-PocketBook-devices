# PocketBookDBHandler
Module for the plugin calibre.koplugin to the KOreader application. The program adds information about books sent via the Smart Device App protocol of the Calibre application to the PocketBook device database. This eliminates the need to reboot the device to find books in the reader's built-in library.

## Installation:
Add files pb-dp.lua and wireless.lua to the folder /applications/koreader/plugins/calibre.koplugin.
The original wireless.lua and main.lua files should be replaced.

## Collections
The plugin adds books to collections on the device. To use this function, you should specify the column lookup name in the calibre (in the #name format) in the plugin settings.


*The program was tested on a PocketBook InkPad 4 and Touch Lux 5 devices.*

*The code was mostly written by Claude AI. A huge thanks to [Volodymyr Streltsov](https://github.com/VolodymyrStreltsov), who explained to me and Claude what bind and bind1 are.*

