# SegoeBootSemilight
Segoe Boot Semilight TTF fonts ripped straight from Windows 10 and 11 system files.

# Info
This repository contains TTF fonts that include the loading circles from both Windows 10 and 11 boot screens!\
Yes, these circles are fonts, so they are lightweight and easy to render.

The Windows 10 fonts can be found in `Win10` directory in this repository.\
The Windows 11 fonts can be found in `Win11` directory in this repository.

Please note that Windows 11 fonts also contain Windows 10 loading circles (defined under the same codes), so I recommend downloading the Windows 11 fonts.

# Installation
*I recommend installing the `segoe_slboot.ttf` file because loading circle characters in `segoen_slboot.ttf` are stretched a bit.*

Download, extract if needed and double-click one of the files in one of the directories.\
Then, click on "Install" in the window that appears.\
Now wait for the installation process to finish (this should take up to 10 seconds).\
You're done!

Tip: you can press `Win + S` and search for "Character map", select the "Segoe Boot Semilight" font, scroll down and see the loading wheels present.\
You can also view the Unicode indexes of them (if you hover your mouse over them).

# Technical (API) information
The fonts are stored on Windows computers inside the `C:\Windows\Boot\Fonts` directory.

Unicdoe range for the Windows 10 loading circle is `U+E052` to `U+E0C6`.
For the Windows 11 one it's `U+E100` to `U+E176`.
*There are also some blank characters between `U+E0C6` and `U+E100` (for some reason).*

For Python coders (and other people), I'll be releasing a sample application with this font in action soon.
