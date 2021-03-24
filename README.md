![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fmike-marshall0164%2Fmob-attack-tool%2Fmaster%2Fmodule.json&label=Foundry%20Version&query=$.compatibleCoreVersion&colorB=orange) [![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fmob-attack-tool&colorB=4aa94a)](https://forge-vtt.com/bazaar#package=mob-attack-tool) ![Latest Release Download Count](https://img.shields.io/github/downloads/mike-marshall0164/mob-attack-tool/latest/module.zip)

# Mob Attack Tool
A module for Foundry VTT that offers a tool for handling mob attacks in the dnd5e system.

## How to install
You can install this module by pasting this url in the corresponding text field of Foundry's package installer: `https://raw.githubusercontent.com/mike-marshall0164/mob-attack-tool/main/module.json`

## How to use
After activating this module, a new button appears in the token controls bar. This button is only visible to users with the GM role. To use the Mob Attack tool, make sure you have at least one token selected and exactly one token targeted. 

A dialog window will appear, populated with the weapon options of the selected tokens along with their respective attack bonuses and a checkbox. Tick the checkbox of the weapon(s) you want to use for the mob attack. 

Clicking on the Mob Attack button in the dialog window will then whisper a message to the GM with the mob attack results. Furthermore, the weapon item is rolled the number of times that an attack would hit.

## Examples

![MAT-video-v0 0 3](https://user-images.githubusercontent.com/17188192/110196581-c81b2f00-7e45-11eb-908a-f0fd73567e10.gif)

### Example Mob Attack Tool + Better Rolls for 5e + Midi-QOL

![MAT-video-midi-qol-v0 0 3](https://user-images.githubusercontent.com/17188192/110196624-0fa1bb00-7e46-11eb-9ec1-ade1ef8dff96.gif)

## Planned improvements
* Improved support for [midi-qol](https://gitlab.com/tposney/midi-qol). -> _In Progress_
* Further (optional) automation of the initial selection of tokens -> _In Progress_
* Some documentation and better structuring of the repo
* Custom Mob Attack tables

## Inspirations
This module was inspired by [Multiattack 5e](https://github.com/jessev14/Multiattack-5e).
The map shown in the examples was made by ~~Printable RPG~~ Spellarena. You can check out more of their beautiful maps on the [Spellarena Patreon](https://www.patreon.com/m/spellarena). 

## Contributors
Juanfrank has kindly given feedback and helped me out with condensing damage formulas.
