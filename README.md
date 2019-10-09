# Ubuntu_macosx_look


## 1 - First of all install Gnome_Tweak_tool
It can download from Ubuntu store or install directly in Terminal

###  a - The terminal way

$ `sudo add-apt-repository universe`

$ `sudo apt install gnome-tweak-tool`


Run this commands on terminal

OR

### b - In ubuntu store


search for "GNOME Tweaks" in Ubuntu store

## 2 - Install extensions from Ubuntu repository

by using these commands

$ `sudo apt install gnome-shell-extensions`

## 3 - Install extensions from Gnome.org

Go to browser

### a - for Firefox Add-on

https://addons.mozilla.org/en-US/firefox/addon/gnome-shell-integration/

### b - for chrome web store

https://chrome.google.com/webstore/detail/gnome-shell-integration/gphhapmejobijbbhgpjhcjognlahblep?hl=en

## 4 - Install Host Connector

The next step is to install Gnome shell host connector.

$ `sudo apt install chrome-gnome-shell`

## 5 - Now install gnome extensions in browser

We can find extensions frome here

https://extensions.gnome.org/

### a - First install user theme

This is for enabling user themes for shell in gnome tweak tool.
You can find it frome here

https://extensions.gnome.org/extension/19/user-themes/

### b - Install Dash To Dock Extension

This extension moves the dash out of the overview transforming it in a dock for an easier launching of applications and a faster switching between windows and desktops.
You can find it frome here

https://extensions.gnome.org/extension/307/dash-to-dock/

### c - Install blyr

Apply a Blur Effect to GNOME Shell UI elements.
You can find it frome here

https://extensions.gnome.org/extension/1251/blyr/

### d - Install Net speed 

Displays Internet Speed.
You can find it frome here

https://extensions.gnome.org/extension/104/netspeed/

### e - Install open wheather

Weather extension to display weather information from https://openweathermap.org/ or https://darksky.net for almost all locations in the world.
you can find it from here

https://extensions.gnome.org/extension/750/openweather/

## 6 - Create Folder

You need to create `.themes` and `.icons` Folders in `home` folder.
To create Run those commands in terminal

$ `mkdir .themes`

$ `mkdir .icons`

## 7 - Download Themes and Icons

You can download Icons and Themes from here

Themes

https://www.gnome-look.org/

Icons

https://www.gnome-look.org/browse/cat/132/order/latest/

Shell themes

https://www.gnome-look.org/browse/cat/134/

Login screen

https://www.gnome-look.org/browse/cat/131/

OR

Themes And Icons are uploaded in Zip formate. Extract and place it into the folders

here `Mojave-dark-theme.tar(1).xz` is put in `.themes` folder. It incluse shell theme

here `Mojave-Cursors-MOD-icons.zip` for cursor pack and `Mojave-circle icons-.tar.xz` for icon pack. These two are placed in `.icons` folder

## 8 - Put the Theme folder in Themes And Put the Icons in Icon folder

Put themes on `.themes` folder 

&

Put icons on `.icons` folder

## 9 - Open gnome-tweak-tool and apply 

Open Gnome-tweak-tool. Named Tweaks in app list

Select the following in Appearance

In `Theme` select `Mojave-dark-theme`

In `Cursor` select `Mojave-Cursors-MOD-icons`

In `Icons` select `Mojave-circle icons`

In `shell` select `Mojave-dark-theme`

In tab Enable all downloaded extensions in Extensions tab.
In Extensions open Dash-to-dock settings select Dock on Bottom position

In top bar tab enable Battery Percentage

## 10 - Set Font

Font added here. Download and

move all Fonts in to: "`~/.local/share/fonts" or "/usr/share/fonts`"

## 11 - Lock screen

This is theme nearly looks like macOS lockscreen , with script which can set wallpaper for your desktop and simultaneously set same wallpaper on lock screen and login screen with blur effect like on macOS.

To get this Go To

https://www.gnome-look.org/p/1207015/

## 12 - SLiM Display Manager

To setting up.

	- Install SLiM Display Manager. SLiM is in all repositories of the most used distros.

	- Choose as your default Display Manager running the command: "sudo dpkg-reconfigure slim"
		
	- Extract and move the  folder of Mojave theme to the directory "themes" on: "/user/share/slim/themes"

	- Run "sudo gedit /etc/slim.conf" and press "ctrl + f", type "current_theme", and change the name for "macOSMojave".
           (**use the text editor of your preference in your distro**)

	- Install the fonts to apply to the theme.

	- If you want to change the background, just rename the image that you like as "background" 
	   and move to the folder theme in "/user/share/slim/themes". The supported images format are "jpg" and "png".

	- To change Desktop Sessions just press "F1"

	- If you can take a screenshot just press the key F11

Note: You can not use the cursor in the SLiM Display Manager; so if you want to "shutdown or reboot" in the login screen, you need to type "halt" or "reboot" in the username box and then write the password, and it's done, so the icons below the screen are just decoration to make more similar to the macOS login screen.

To download go to

https://www.gnome-look.org/p/1326269/

## 13 - Restart the shell 

Press the following key

`Ctrl + Alt + F2`

OR

Restart the PC

# You are Done