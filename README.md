# Tinvaak 2

Wabbajack Modlist Installer by Althro & The Animonculory.

**Modlist Download: [Wabbajack UI](https://github.com/wabbajack-tools/wabbajack/releases)**

**Modlist Support: [The Animonculory Server](https://discord.gg/DffHKcszfg)**

![Tinvaak-banner](https://raw.githubusercontent.com/Althro/Tinvaak2/main/.github/T2Banner.webp)



[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Tinvaak](#downloading-and-installing-tinvaak)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [Post Character creation](#post-character-creation)
      - [Important steps](#important-steps) 
      - [In Game MCM Options](#in-game-mcm-options)
      - [Sunhelm](#sunhelm)
  - [Updating Tinvaak](#updating-the-modlist)
  - [FAQ](#faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Controller setup](#controller-setup)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

> "The Dragonborn may very well save the day, but to this uncaring realm, you are just a mortal. You are yet another unimportant person in the world, something that passersby see and rarely interact with. As you advance, weapons drawn, you hesitate, unsure if you can really do this. That tiny bit of uncertainty, that small voice of doubt: It's amplified and ever-present."

Tinvaak is a list focused on making Skyrim: Special Edition (SSE) into an actual roleplaying game. Many new mechanics and changes are present to offer an alternate take on the game. You can view many of these changes in the [showcase video from DroppedIceCream](https://www.youtube.com/watch?v=4N0cOrv5Crc), the [official trailer](https://youtu.be/8bLSGfok47g) and the [Changes to Gameplay](https://github.com/Althro/Tinvaak2/blob/main/Changes%20to%20Gameplay.md) article.

Support for the list is handled on the [official Animonculory discord server](https://discord.gg/DffHKcszfg).

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Tinvaak is aimed at higher tier machines so a system like the following is advised:

### 1080p
- 2nd Gen Ryzen (2800x)/6th Gen Intel i5 CPU 
- 16GB DDR4 Ram
- SSD
- 6GB GPU (1660 super/5600XT); 8GB GPU (1070/5700XT) recommended

### 1440p/1080p Ultrawide
- 3rd Gen Ryzen (3600)/9th Gen Intel i5 CPU
- 32GB DDR4 Ram
- NVME SSD
- 8GB GPU (RTX 2080/6700XT); 10GB+ (RTX 3080/6800) recommended

Space required: Approx 250GB

## Installation

Installing Tinvaak is relatively easy and, if you have nexus premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Tinvaak, please complete the following steps. 

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside `/Documents/My Games/`.
4. Reinstall Skyrim into a location that is not Program files or your desktop. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. **Do not place it in program files, on your desktop or in your downloads folder.** I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Tinvaak

Downloading and installing Tinvaak can take a while depending on your internet connection and computer. To install Tinvaak, complete the following steps.


1. Open Wabbajack and click on browse modlists.
2. Press the download button on Tinvaak and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Tinvaak. **Do not install it to your desktop or downloads folder.** The downloads folder will autofill.
4. Press the play button to begin.
5. Go and pet your nearest fluffy animal whilst Wabbajack does its thing.
6. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

Tinvaak uses a new Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.

### BethINI

You will need to use BethINI to set your monitors screen resolution. If you don’t, you’ll be running the game at 1440p which is a lot more performance intensive. To set this, complete the following steps.

1. Go to where you have installed the list and open the tools folder.
2. Open the BethINI folder and run the program.
3. Set your resolution, in my case this is 1440p.
4. Choose whether you want borderless/windowed or Fullscreen.
5. Press save and exit.

### ENB

Tinvaak comes already set up with Ominous ENB for Obsidian Weathers. If you wish to use a different ENB, you should make sure to use one that support Lux. To replace the ENB, complete the following steps.

1. Delete the enbcache, enbseries folders and the enbseries.ini from the Game Root folder (/installation folder/Game Root).
2. Download an ENB you want.
3. Copy the enbseries folder and enbseres.ini into the Game Root folder.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. Once launched, ensure that the correct profile you want to play on is selected in the left-hand dropdown box. By default, it will be set to the normal profile, but you can change it to the Khajiit Speak profile by selecting that one. 

Make sure the dropdown box on the right is set to `Play Tinvaak` and press the run button.

### Post Character creation

#### Important steps

Once you have created your character and all the messages on screen have dissappeared, wait until you get a prompt to `assign your attributes` and assign them. **Note**: These are permanent so choose wisely. You can then use the Medical history book to assign more attributes should you wish. 

Once you have completed that, you are free to explore the room. Take a look around at the containers and whatever is on the table, they may be useful for your adventures. When you have finished examining the room, talk to the little dragon next to the door to select a start of your choice, then go through the door to begin your journey.

#### In-Game MCM options

All the important MCM options are automatically configured for you already. Once all the messages have disappeared, you have confirmed the Dino’s Spell Casting pop-up and assigned your attributes, tweak the following to your liking:

- Lucien (If you set a supported nickname, he will call you by that)
- SkyUI
- SV Mods Menu (Spells Cost Stamina and Spell learning requirements)

**DO NOT TOUCH THE DEFLECTION MCM. YOU WILL BREAK MANY THINGS.**

#### Sunhelm

After you have spawned into the world, open the MCM menu and navigate to SunHelm. Set the following settings.

- General Settings
	- Gameplay Options
		- Raw Meat Damage [unchecked]
		- Carry Weight Penalty [unchecked]

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### Anniversay Edition

Neither the AE version of the game nor the Creation Club content that comes with it are supported with Tinvaak. It will not work if you just add it!

### BA Alchemist Arsenal

You need to be level 5 and open the crafting kit to use this. For more detail on it, please see the [advanced gameplay guide](https://github.com/Althro/Tinvaak2/blob/main/Advanced%20Gameplay%20Overview.md).

### Controller Setup

Please follow this [excellent guide by ShadesOfDawn and Chri3i](https://github.com/chri3i/Gamepad-Guide-by-ShadesOfDawn-and-me) for setting up a controller with Tinvaak. Antimicro is included with the list to allow for Engarde compatibility.

### Ultrawide Options

I personally do not own an Ultrawide, so I cannot offer support beyond what is below. To properly configure a 21x9 ultrawide, complete the following.

1. Download [Complete widescreen fix for vanilla and SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/1778?tab=files) and place the installed files above Hoizons UI.
2. Activate the Horizons UI 21:9 mod
3. Activate Oblivion-like Loading Menu 21x9
4. Open BethINI, set your resolution and enable borderless windowed
5. In the Extended UI MCM set your Aspect Ratio

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

#### ENB

Tinvaak ships with an ENB setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. I recommend opening the console before doing edits.

##### Removing the letterbox

1. Press [Shift+Enter] to open the ENB menu
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button
5. Press [Shift+Enter] to return to the game

##### Turning off settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexFireLights
- ComplexParticleLights – Disable Big Range
- Reflection

If you really cannot handle the ENB, uncheck `useEffect`.

### Zoomed in Display

This is caused by Windows display scaling feature. To fix this you can do either of the following.
- Set display scaling back to 100% in Windows screen resolution settings
- Edit SSE Display Tweaks ini file under Render
	- Fullscreen: `True`
	- Borderless: `False`
    
## Removing the Modlist
Simply delete the folder and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Chef & Spaniard for assisting with so many things. You’re both awesome.
- Annakins for testing, the trailer, and the logo. You’re awesome.
- The Animonculory Dev Team
- Galaxy Synth for Tinvaak 1.
- Noggog for Mutagen.
- iXanza, JanuarySnow and OsmosisWrench for recompiled MCM scripts for automation.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
- My amazing Patreons.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/Althro/Tinvaak2/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/Althro/Tinvaak2/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/Althro/Tinvaak2/blob/main/Changelog.md) before you do.
