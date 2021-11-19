# *Evangelion Unit 01*
### Overview
This is a XFCE/gtk3 theme. It was build upon the Sakura-Dark theme, with additional apps customized and *gaps* between windows.
### Color palette
Green 0|Green 1|Green 2|Green 3|Black 0
:---:|:---:|:---:|:---:|:---:
![green0](./pictures/green0-33ff00.png)|![green1](./pictures/green1-C7FBA5.png)|![green2](./pictures/green2-ADF182.png)|![green3](./pictures/green3-2C8C1F.png)|![black0](./pictures/black0-1F1D1C.png)
#33ff00|#C7FBA5|#ADF182|#2C8C1F|#1F1D1C

Purple 0|Purple 1|Purple 2|Pink 0|Orange 0
:---:|:---:|:---:|:---:|:---:
![purple0](./pictures/purple0-916CAD.png)|![purple1](./pictures/purple1-523874.png)|![purple2](./pictures/purple2-711F8C.png)|![pink0](./pictures/pink0-DC7D68.png)|![orange0](./pictures/orange0-F08B18.png)
#916CAD|#523874|#711F8C|#DC7D68|#F08B18
### About *gaps*
This theme only handles the inner gaps between windows, to add gaps to the outer line you must manually add in XFCE settings, go to:
	settings manager > Workspaces > Margins
In the screenshots the margins used is 3px on every side.
### How to install?
If you already don't have a theme folder in your home directory then create one:

`mkdir ~/.themes`

now clone this repo to your .themes directory:

`git clone https://github.com/inatagan/eva-01.git ~/.themes/eva-01`
### Preview
<!-- #### Desktop
![Desktop](./screenshots/Screenshot_2021-11-01_20-26-02.png)
#### Firefox && code
![Firefox && code](./screenshots/Screenshot_2021-11-01_20-48-38.png)
#### GIMP && Thunar && Sakura terminal
![GIMP && Thunar && Sakura terminal](./screenshots/Screenshot_2021-11-01_20-48-45.png)
#### Notifications
![Notifications](./screenshots/Screenshot_2021-11-01_20-49-33.png)
#### Whisker menu
![Whisker menu](./screenshots/Screenshot_2021-11-01_21-02-17.png)
#### System info
![System info](./screenshots/Screenshot_2021-11-01_22-08-21.png) -->
### XFCE Panel
Copy the panel config file to its default destination

`cp -i ~/.themes/eva-01/xfce-perchannel-xml/xfce4-panel.xml ~/.config/xfce4/xfconf/xfce-perchannel-xml/`

The panel uses a custom background, currently the background provided supports the following resolutions [4k, QHD, FHD and HD], if you want the panel to look the same on an unsupported screen you must edit/create a custom background to fit your screen resolution.

To set the background go to the panel settings, chose panel **1** > in the appearance tab set Style to Background image and chose the appropriate file, the bg image should be in `~/.themes/eva-01/panel-background/`
### My Keybindings
Copy the keyboard shortcuts file if you want the same keybindings as well to `~/.config/xfce4/xfconf/xfce-perchannel-xml/`

`cp -i ~/.themes/eva-01/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml ~/.config/xfce4/xfconf/xfce-perchannel-xml/`

Some of the Keybindings are:

* `Super Key + W = Browser(Firefox)`

* `Super Key + F = File Manager(Thunar)`

* `Super Key + T = Terminal`

* `Super Key + C = Code`

* `Alt + F2 = Appfinder (Compact)`

* `Alt + F3 = Appfinder (Extended)`

* `Alt + F4 = Close current window`

* `Alt + F9 = Minimize current window`

* `Alt + F10 = Maximize current window`

* `PrtSc = XFCE Screnshot without capturing mouse cursor`

* `Shift + PrtSc = XFCE Screnshot with capturing mouse cursor`

* `Ctrl + Up = Volume up(+5%)`

* `Ctrl + Down = Volume down(-5%)`

XFWM provide minimal tiling functions, that are arranged as a grid with the following keybindings:

Super Key +
#|Left | Full side | Right
:---:|:---:|:---:|:---:
Top|7|8|9
Full side|U|null|O
Bottom|J|K|L

### Wallpapers
The main wallpaper was made using [this art as source](https://www.instagram.com/p/CWGAOQgP0_H/?utm_medium=copy_link) by @ikhimaz.
### Software shown and additional themes
Firefox theme [**EVA-01**](https://addons.mozilla.org/en-US/firefox/addon/eva-01-theme/)

Code theme [**EVA-01**](https://marketplace.visualstudio.com/items?itemName=inatagan.eva-01-vscode-theme)

Icons theme [**Papirus**](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) + [yaru folders](https://github.com/PapirusDevelopmentTeam/papirus-folders)

Mouse cursor theme [**Oreo spark lime**](https://github.com/varlesh/oreo-cursors)

---
