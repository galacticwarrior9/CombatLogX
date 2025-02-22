# CombatLogX
[![Code Size](https://img.shields.io/github/languages/code-size/SirBlobman/CombatLogX)](https://github.com/SirBlobman/CombatLogX/)
[![Build Status](https://jenkins.sirblobman.xyz/job/SirBlobman/job/CombatLogX/badge/icon)](https://jenkins.sirblobman.xyz/job/SirBlobman/job/CombatLogX/)
[![Crowdin Localization](https://badges.crowdin.net/combatlogx-spigot-plugin/localized.svg)](https://crowdin.com/project/combatlogx-spigot-plugin)

# Description
CombatLogX is a plugin made for the Spigot server software.  
It has many combat-related features to add to your server.  
One of the main features of this plugin are the Expansions, which are like modules that allow you to add different things and change how the plugin works.

# Dependencies
- [Spigot 1.8.8 - 1.17.1](https://spigotmc.org/)
- [SirBlobmanCore 2.3.1 or higher](https://jenkins.sirblobman.xyz/job/SirBlobman/job/SirBlobmanAPI/)

## Main Features
- Custom expansions that change how the plugin works
- Tag players when they attack other players
- Punish players that log out during combat

## Installation Guide
1. Download the CombatLogX.zip file from Jenkins or SpigotMC
2. Stop your server. (Click the stop button on the panel or type `stop` into the console if your server doesn't use a panel.)
3. Upload the contents of CombatLogX.zip to your server.
4. Delete the CombatLogX.zip file.
5. If the files were uploaded and extracted correctly, your server should have the following files:
   - File: `/plugins/CombatLogX.jar`
   - File `/plugins/SirBlobmanCore.jar`
   - Folder: `/plugins/CombatLogX/`
   - Folder: `/plugins/CombatLogX/expansions/`
   - Multiple Files: `/plugins/CombatLogX/expansions/*.jar`
6. Start your server. (Click the start button on the panel or execute the script if your server doesn't use a panel.)
7. Edit the configuration files for the main plugin, languages, and expansions.
8. Type the command `/clx reload` to reload the configuration files.

## Localization
A translation project for CombatLogX V11 is in progress. If you wish to help out, please visit the Crowdin page below:  
https://crowdin.com/project/combatlogx-spigot-plugin

### Localization Credits
https://crowdin.com/project/combatlogx-spigot-plugin/reports/top-members

## Expansions
If you want to find out more about the expansions, please visit this page:  
<https://www.spigotmc.org/wiki/combatlogx/>

You can also open the README files in each expansion folder.

## Developer API
If you are looking for the source for the current version on Spigot (10.3.8.3), please check the "old/10.0.0.0" branch.  
If you want to create expansions or learn how to use the CombatLogX API for V11/Beta, please visit this page:  
[API README](api/README.MD)

## Support
Support is provided by creating a new issue, or by chatting with the Support Team on my discord.  
**Discord Link:** <https://discord.gg/XMq2agT>
