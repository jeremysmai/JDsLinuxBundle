# JDsLinuxBundle
Fresh System? Need packages quick? Bam.
(Requirements: Linux - Debian)
Most apps in this bundle are automatically included in most Linux Distributions, but if not here's a list to jog that memory.

## Bottles Configs
**Elder Scrolls Online** - This is the backup file for the bottles config I use. This config has more then the necessary dependenceis to get ESO to run on Bottles on Linux. Can even use minion to allow addons. No need for Windows anymore. [Link to Config File](backup_The-Elder-Scrolls-Online.yml.zip) (its a zipped .yml file) You will also need the Install_ESO.exe from the Official Website. *This is really for users who bought from the site stricly and not using steam or any other storefront.* 
**Use the Dependencies.yml for hopefeuly a prereq list of Dependencies needed to get ESO installer to even boot. Working on a script next to automate this entire process**

### Install Process
1. Things needed to install: Bottles, Install_ESO.exe & Dependencies.yml (Shown Above)
2. Install Bottles, After Install, Import Config using the Dependencies.yml
3. Select "Run Executable" within newly setup Bottle, naviagte to and select Install_ESO.exe
4. Once the installer pops up, proceed with normal install. *Note that the whole Install window will dissappear when finished, this is normal!*
5. Click add Shortcut within Bottle, naviagate the path selecting Bethesda.net_Launcher.exe as the shortcut (drive_c > Program Files (x86) > Zenimax Online > Launcher > Bethesda.net_Launcher.exe)
6. Once selected the new shortcut will populate within bottle, select the play button. Launcher should pop up, now you can install the full game. Once installed, press play and enjoy.

*Bonus* To get addons to fully work, install Flatseal and Minion (both are flatpaks). Using minion you can install and manage your ESO addons. But for Minion to see your Game files, you'll need to use flatseal to give filepath permission to Minion to see the Bottles directories. Will elabortate further in future. Will also setup script for future ease of use.

## Packages In Bundle
(Compressed Download (to) Include Solarized Themes)
Currently just a listing of must have apps on a fresh Linux System *according to jeremysmai*

 App | Details
 ---------------- | ----------------
| [OpenRazer](https://openrazer.github.io/) | Razer Synapse Replacement for Linux |
| [Atom](https://atom.io/) | hey I'm using that app to type this |

## Helpful Terminal commands
Below are a list of helpful commands and links to helpful tips on Terminal and it's ways...

[Name/Command] | Details
---------------- | ----------------
|||


## rEFInd (Use with caution)
 Download | Details
---------------- | ----------------
| [rEFInd](http://sourceforge.net/projects/refind/files/0.11.4/refind-bin-0.11.4.zip/download) | For multi-booting with Mac OS X see [this](https://www.rodsbooks.com/refind/installing.html) for reference |

#### To Do
- [ ] Eventually build a list that automatically supplies links for the newest downloads / a bundle.zip or better compression for easy storage long term flash-drive style

Phantom Inc. |'' | :bowtie:
Version .05 :man_astronaut:
