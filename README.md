# Noted Layout
For an introduction to the <em>Noted</em> layout, see the <a href="https://dariogoetz.github.io/noted-layout/">introduction page</a>.

<em>Noted</em> is a keyboard layout that aims to allow efficient and comfortable typing both in German and English.

It has its roots in the <a href="https://www.neo-layout.org">Neo family</a> of German alternate keyboard layouts and aims to improve upon them.

The design of the <em>Noted</em> layout was supported by a newly developed <a href="https://github.com/dariogoetz/keyboard_layout_optimizer">optimizer</a> based on a mixed-language corpus (60% German, 40% English).

## Layout on ISO Keyboards
![Noted Layout](/images/noted-1-tkl.path.svg)

## Layout on Ergonomic Keyboards (crkbd or Cantor)
![Noted Layout](/images/crkbd/noted-1-tkl.path.svg)

## Troubleshooting

### The layout file is not working under Debian Bookworm

On older distributions one has to use the [pre-239](https://github.com/dariogoetz/noted-layout/blob/main/xkb/pre_239/noted) layout file. The newer layout file is only compatible with xkb 2.39 and later. This would be available from Debian Trixie onwards.

### Pasting using Ctrl-V does not work under KDE

There is a global shortcut in KDE used by *KDE Daemon* to activate a systems monitor. It is bound to `Ctrl-Esc`. This interferes with the `Ctrl-V` paste shortcut. To disable the systems monitor shortcut, go to the shortcuts section in the KDE System Settings ("Kurzbefehle" in German), search for *Esc* and disable the corresponding shortcut. After that, KDE needs to be restarted, e.g., by logging out and in again or by restarting the system.

### The layout cannot be activated using the systems settings

In order to be able to choose a lavout from the systems settings, the `custom` lavout file has to be used. For this, a required and complicated integration process has already been done. More information can be found [here](https://www.neo-layout.org/Layouts/noted/#download-und-installation).

On some systems even using the `custom` file does not work. This was reported for Debian Bookworm and Trixie with KDE for some, but not all users. No solution is known yet.
