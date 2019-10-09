# mac
Apple Mac related stuffs

## Hungarian keyboard layout extension

This extension provides typical Windows-style AltGr keys to official Hungarian keyboard layout.

Prerequisites:

* External Windows-style keyboard (external Apple keyboard also works, but confusing ;-)
* Official Hungarian keyboard layout (Input Source) has been installed
* Installed Karabiner-Elements, see: https://pqrs.org/osx/karabiner/

Install steps:

1. Acivate official Hungarian keyboard layout
1. Download `Hungarian_AltGr.json` to `/Users/<username>/.config/karabiner/assets/complex_modifications/`.
1. Open Karabiner-Elements
1. In Simple modifications, define **left_command** -> **left_control** and **left_control** -> **left_command** replacements
1. In Complex modifications, click on *Add rule*, click on *Enable All* of line **AltGr for Hungarian**.
1. Review Devices (Apple Internal Keyboard may not be activated)
1. Close Karabiner-Elements

Features

* Most important `AltGr` keys work
* **`LEFT Ctrl`** keys (on terminal, too):
  * `A` select all
  * `C` copy
  * `V` paste
  * `X` cut
  * `F` find
  * `Z` undo
  * `Y` redo
* **`RIGHT Ctrl`** keys (on terminal):
  * `C` break
  * `X` exit (nano)
  * `W` where (nano)
* Other keys:
  * `Alt + Tab`: task selection (next, with Shift: previous)
  * `Windows + Tab`: tab selection (next, with Shift: previous)
  * `Windows + Ctrl + Q`: Lock screen
  * `Windows + mouse click`: properties (right click)
  * `Ctrl + mouse click`: open link in new tab in the backbgound (Firefox)
  * `Alt + mouse click`: download link (Firefox)
