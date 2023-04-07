Readme.en.txt
2023-04-01 00:35 JST
update: 2023-04-02 12:24 UTC

This is an unofficial derivative (re-spin) of the antiX Linux. The default desktop environment is the same as the official antiX Linux version, Rox-IceWM. This is a desktop environment that combines the Rox-Filer file manager with the IceWM window manager. The upstream base is antiX-22_x64-base.iso, which does not includs the office suite.

User: demo
Demo password: demo
Root password: root

**Multilingual Support
uim (universal input method) framework supports Multilingualism.
Optionally, you can enable Japanese input as follows:

Click uim IM Switcher on the toolbar to change input mode from Direct to Anthy. Then, press Shift + Space key to enable Japanese input.

Press Shift + Space key again to return to the Direct mode.

** About Universal Input Method (uim)
Uim is an input method module library which supports various scripts and can act as a front end for a range of input methods, including Anthy, Canna, or SKK (for Japanese), Pinyin (for Chinese), Byeoru (for Korean), and M17n (for many other languages). Most of its functions are implemented in Scheme, so it's very simple and flexible.

You can search additional plugins for uim as follows:
$ apt search uim-

For example:
uim-byeoru - Byeoru input module for hangul.
uim-chewing - Chewing input module for Chinese.
uim-pinyin - Traditional and Simplified Chinese.
uim-viqr - Vietnamese Quoted-Readable support.
uim-latin - Latin script input support.

If you need another input method for many other languages, add m17n support by installing uim-m17nlib package as follows:
 # apt install uim-m17nlib

**Known bugs
None.

** Downloading sites
An updated version is usually available at https://sourceforge.net/projects/mx-respin-iso/

**About IceWM Desktop
It includes several other desktops besides the default desktop environment, including Fluxbox and JWM and more. You can use the menu to switch between them without having to log off.

And IceWM is considered that a desktop environment that is not very commonly used, but it is light and practical. The following link provides an article explaining what it is about.

Reference link: ROX Desktop--A habit-forming desktop environment that is lighter than GNOME and KDE https://mag.osdn.jp/07/02/09/0024235


This readme.en.txt was written by Green

END.

