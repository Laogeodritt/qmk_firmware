# Planck layout for multilingual programmers

A QWERTY layout by [Laogeodritt](https://github.com/laogeodritt). Features:

* **QWERTY layout**
* **Non-English layouts**: AltGr (Right Alt) on base layer allows better out-of-box compatibility with your OS's non-English QWERTY layouts and US International Sort.
* **Polyglot keyboard layout**: On the base layer, AltGr and keys for accessing the Greek, Maths and Symbols deadkeys on Laogeodritt's custom Windows "Polyglot" keyboard.
* **For programmers**: Symbols positioned in a single layer on the home row for easy access.
* **For keyboard shortcut-heavy programmes (e.g. Photoshop)**: Easy access to F-keys and numpad keys for software that uses them extensively.

This layout intends to be fairly opinionated and exclude unnecessary configuration/adjustment features, e.g., the key for swapping OS and ALT is not present on the Adjust layer. You can re-add such configuration to the Adjust layer, or simply modify the layout to suit your own needs.

Partially based on the [Smittey](https://www.smittey.co.uk/the-planck-key-theory) keyboard.

# Layer overview

TODO: add images

## Main layer

* QWERTY layout. Non-switchable, but you could replace it with Dvorak/Colemak or re-add the switch keys (they are still available in keymap.c).
* Standard CTRL-OS-ALT key order in bottom-left corner. CTRL position more similar to standard keyboards for ease of use of keyboard shortcuts.
* Right shift is available (Shift when held, Enter when tapped).
* AltGr available for easy access to symbols and accents in your OS's standard non-English layouts.
* Access to greek, maths and symbols deadkeys on Laogeodritt's custom Windows "Polyglot" keyboard layouts. These keys are useless for other layouts, you may want to find other functions for them if you don't use this layout. (Unfortunately you don't have four keys for the arrow keys, if you want to keep AltGr.)

## Raise layer

* Number row
* Numpad-style layout on the right side for ease of numerical data entry. Designed to stick to the Planck philosophy of everything being within one key of your home row fingers.
* ISO layout key ("NUBS") available beside the left shift.

# Lower layer

* Number row symbols on top row, corresponding to the *Raise* layer's number row.
* Other symbols []+=-\_{}| on the home row.

# Function layer

* Left hand: access to all 12 Function keys.
* Right hand: true numpad keys, for applications that differentiate between number row and numpad keys. Same numpad layout as on the *Raise* layer.
* This layer can be locked (from the *Adjust* layer) when doing extensive numerical data entry or needing extensive access to function keys.

# Space layer

* Activates on holding space.
* Arrow keys (WASD and vim-style HJKL).
* PrintScreen, because I have nowhere else to put it. Just in case you need it.

# Adjust layer

* Extensively redesigned for an easier-to-remember layout.
* Highly minimalistic: no keys to swap configurations like the OS-ALT key order. You can change the layout or re-add these keys if desired.
* RESET, DEBUG, CAPSLOCK on left side.
* Audio, Music and MIDI on/off and other control keys on right side.
