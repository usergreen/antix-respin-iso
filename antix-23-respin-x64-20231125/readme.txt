readme.txt

2023-04-01 00:35 JST
update: 2023-11-25 11:57 UTC

This is an unofficial derivative (re-spin) of the antiX Linux. The default desktop environment is the same as the official antiX Linux version, zzzFM-IceWM. This is a desktop environment that combines the zzzFM file manager with the IceWM window manager. The upstream base is antiX-23_x64-base.iso, which does not include the office suite.

User: demo
Demo password: demo
Root password: root

NOTE:
This ISO image file is set NO default locale parameters. So, you should choose your prefered locale from among th pull-down list.

** Optional L10n support
Many locales are included, but the followings are well supported (for example, on browser and mailer):

de_DE.UTF-8 - German locale for Germany
el_GR.UTF-8 - Greek locale for Greece
en_US.UTF-8 - English locale for the USA
es_ES.UTF-8 - Spanish locale for Spain
fr_FR.UTF-8 - French locale for France
hi_IN.UTF-8 - Hindi  locale for India
hr_HR.UTF-8 - Croatian locale for Croatia
hu_HU.UTF-8 - Hungarian locale for Hungary
id_ID.UTF-8 - Indonesian locale for Indonesia
it_IT.UTF-8 - Italian locale for Italy
ja_JP.UTF-8 - Japanese locale for Japan
nl_NL.UTF-8 - Dutch locale for the Netherlands
pl_PL.UTF-8 - Polish locale for Poland
pt_BR.UTF-8 - Portuguese locale for Brasil
ru_RU.UTF-8 - Russian locale for Russia
sv_SE.UTF-8 - Swedish locale for Sweden
zh_CN.UTF-8 - Chinese locale for Simplified Chinese (簡体字)
zh_TW.UTF-8 - Chinese locale for Traditional Chinese (繁体字)

**Known bugs
None, but you should read the release news provided at https://antixlinux.com/antix-23-released/

** Downloading sites
An updated version will be available at https://sourceforge.net/projects/antix-respin-iso/

** Origin of this snapshot.iso
Modified from the Official ISO of
antiX-23_x64-base.iso (Arditi del Popolo) 28 Aug, 2023
https://sourceforge.net/projects/antix-linux/

**Multilingual Support
uim (universal input method) framework supports Multilingualism.

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

*** Setup uim
Default input mode is fixed as "Direct".
Input method is setup automatically, depending on a language environment you chose. So that, you should change direct mode to another one.

To switch from direct mode to uim input, set as the following steps:
Main menu (antiX) --> Applications --> Preferences --> Input Method (uim) --> Global Settings --> check "Specify default IM --> select Anthy (UTF-8) for Japanese --> click on "OK" --> Restart Session

*** To Enable Japanese input
uim-anthy is preinstalled by default. Enable uim-Anthy as mentioned above.

Optionally, you can enable Japanese input as follows, if you add uim toolbar on Desktop:
Click uim IM Switcher on the toolbar to change input mode from Direct to Anthy.

Then, press Shift + Space key to start Japanese input, for example.
Press Shift + Space key again to return to the Direct mode.

Noted: When choosing ja_JP.UTF-8 at Boot Menu, 半/全 key is also available by default to toggle between English and Japanese. There is no need to change uim preferences as above.

*** To Enable pinyin input
Follow the same ateps above. uim-pinyin is already pre-installed.

If you need another input method for many other languages, add m17n support by installing uim-m17nlib package as follows:
 # apt install uim-m17nlib

** About IceWM Desktop
It includes several other desktops besides the default desktop environment, including Fluxbox and JWM and more. You can use the menu to switch between them without having to log off.

And IceWM is considered that a desktop environment that is not very commonly used, but it is light and practical. The following link provides an article explaining what it is about.

Reference link: ROX Desktop--A habit-forming desktop environment that is lighter than GNOME and KDE https://mag.osdn.jp/07/02/09/0024235

** Terms of use
See https://mxlinux.org/terms-of-use/

This Live ISO image was released in a hope that it would be useful. Therefore you are allowed to redistribute or modify under the GNU General Public License v.3. Its full text can be found both at https://www.gnu.org/licenses/gpl-3.0.html and onboard at /usr/share/common-licenses/GPL-3. But please be noted that the Upstream's trademark and its logo exclusively belong to the Official Dev Team, which means it is firmly prohibited for commercial usage without permission.

This readme.en.txt was written by Green

END.

