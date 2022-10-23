# bsd-factory-sets
## A repository containing .set files for my WIP Battle Spot Doubles Factory formats on Pokemon Showdown!
### Created by Damon Murdoch ([@SirScrubbington](https://twitter.com/SirScrubbington))

## Description
This repository contains several .set files, which follow basically the 
same format as Pokemon Showdown! exports with some minor differences. 
These files are compiled into JSON format for use with my Pokemon 
Showdown! Battle Spot Doubles Factory format using a Python script. 

My current intention is to flesh out the ORAS BSD sets fully, and then
progress to working on Sun and Moon, then Sword and Shield, and then
finally Black and White 2.

### File Format
The file format is as follows:
* Most lines except for the first line (Species) are optional
* Any line starting with '#' is commented and will be ignored by the compiler 
* Comments do not currently work in the middle of lines!

```
Nickname (Species) @ Item1 / Item2 / ... / itemN
Ability: Ability1 / Ability2 / ... / AbilityN
EVs: n HP / n Atk / n Def / n SpD / n Spe
IVs: n HP / n Atk / n Def / n SpD / n Spe
Nature nature
- MoveOption1 / MoveOption2 / ... /MoveOptionN
- MoveOption1 / MoveOption2 / ... /MoveOptionN
- MoveOption1 / MoveOption2 / ... /MoveOptionN
- MoveOption1 / MoveOption2 / ... /MoveOptionN
```

Example:

```
# Standard Landorus
Landorus-Therian @ Choice Scarf / Assault Vest
Ability: Intimidate
EVs: 4 HP / 244 Atk / 4 Def / 4 SpD / 252 Spe
Adamant nature
- U-turn
- Earthquake
- Rock Slide
- Superpower / Knock Off
```

### Version
The latest revision for this software is 0.1.

### Language
Pokemon Showdown! Set Format (Modified)

### Date Created
Monday, 24 October 2022

## Future Changes
A list of future planned changes are listed below.

| Change Description             | Priority |
| ------------------------------ | -------- | 
| Finish the remaining ORAS Sets | High     |
| Start adding Sun & Moon Sets   | Medium   |
| Start adding SWSH Sets         | Low      |
| Start adding B2W2 Sets         | Low      |

### Problems or improvements
If you have any suggested fixes or improvements for this project, please 
feel free to open an issue [here](../../issues).

### Sponsor Me
If you would like to sponsor this project, please feel free to 
make a donation [here](https://www.paypal.com/paypalme/sirsc).
