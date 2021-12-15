# My custom keyboard layout files for Mac OS X

This repository contains customized "Russian - Phonetic/ Translit" keyboard layouts in `.keylayout`/ `.bundle` format, for use on MacOS.
Layout was modified to allow entering Cyrillic symbols on both standard and Nordic (Finnish/ Swedish) keyboard like it's done in Translit (http://www.translit.ru/).

Here are some example of input transformations that are made (entered symbols -> displayed symbols):

- "zh" -> "ж"
- "sh" -> "ш"
- "shh" -> "щ"
- "ch" -> "ч"
- "je" -> "э"
- etc.

## How to install a new keyboard layout

1. Copy the `.keylayout` or `.bundle` file to the `~/Library/Keyboard Layouts/`: `cp ./Cyrillic 2.bundle ~/Library/Keyboard Layouts/`
2. Reboot, or log out and log in again.
3. Enable the new keyboard layout "Russian - Translit FI - AK" via _System Preferences_ › _Language & Text_ › _Input Sources_.

## Credits

Created using [Ukelele.app](http://scripts.sil.org/ukelele).
