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

The font is pre-installed on Windows, but to make it accessible to regular users and third-party apps, 
you'll have to install it to the regular fonts directory, which is `C:\Windows\Fonts`.\
Don't worry, installing (or later removing) the font from `C:\Windows\Fonts` directory won't corrupt the boot screen at all.
The boot screen fonts are located in a different folder, which is `C:\Windows\Boot\Fonts`.

Download, extract if needed and double-click one of the files in one of the directories.\
Then, click on "Install" in the window that appears.\
Now wait for the installation process to finish (this should take up to 10 seconds).\
You're done!

Tip: you can press `Win + S`, search for "Character map", open it, select the "Segoe Boot Semilight" font, scroll to the bottom and see the circle frames present.\
You can also view the Unicode indexes of them (if you hover your mouse over them).

# Technical (API) information
The fonts are stored on Windows computers inside the `C:\Windows\Boot\Fonts` directory.

Unicode range for the Windows 10 loading circle is `U+E052` to `U+E0C6` inclusive.
For the Windows 11 one it's `U+E100` to `U+E176` inclusive.\
*Note: I haven't verified these ranges yet, so it's the best to check for them manually for now.*

For Python coders (and other people), I'll be releasing a sample application with this font in action soon.
