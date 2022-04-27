# My linux configs

These are all just my personal taste and the only reason it is public is so that I don't have to log in to access it, these are all unorganized and I don't see that changing any time soon. I have added instructions for what you need to do if you want to use any of my configs feel free to add suggestions in **_issues_**. You will find Neofetch , bpy/bashtop in misc

## config.conf (Minimal neofetch)

my minimal neofetch config

this should go without saying but you will need neofetch installed already

go down to line 723 and change the Ascii distro unless you want to keep the small Arcolinux logo there are lots of comments that you can follow and I would recommend customising the config

you will need to go to "**_/.config/neofetch_**" and save this config file and remove you're old config file

the auto function doesn't work with these settings for whatever reason and it just shows a distorted tux penguin


## Flashy

**_/.config/neofetch_**

flashy version of the minimal neofetch config

go down to line 723 and change the Ascii distro unless you want to keep the Arcolinux logo there are lots of comments that you can follow and I would recommend customising the config

change the files name to **config.conf**

just follow the instuctions for the minimal config


## Bpytop

**_/.config/bpytop_**

just swap the bpytop config that I have for the one you have


## Bashtop

**_/.config/bashtop_**

follow the instructions for bpytop they're pretty similiar

## OBS Studio

OBS studio has multiple files that are needed for it to work(**_untitled.json_**, **_basic.ini_**, **_services.json_** and **twitch_ingests.json**), **_untitled.json_** replaces **_/home/thubs/.config/obs-studio/basic/profiles/Untitled/basic.ini_**, **_basic.ini_** replaces **_/home/thubs/.config/obs-studio/global.ini_**, **_services.json_** replaces **_/home/thubs/.config/obs-studio/basic/scenes/Untitled.json_** and **twitch_ingests.json** replaces **_/home/thubs/.config/obs-studio/plugin_config/rtmp-services/twitch_ingests.json_**. Apologies for the wall of text

## .Bashrc/.profile

Just some terminal customizations, you will need to replace your normal bashrc and profile **make sure you only have 1 .bashrc and 1 .profile**

## How to help

submit any config files which you want added to this repo with a pull request or open an issue if you want a specific programs config
