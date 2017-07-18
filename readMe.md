# Troop Command
> Troop Command is a SRPG based on Fire Emblem (Specifically Blazing Sword and Echoes), Advance Wars, and Yggdra Union. The game is a Map-Based Strategy War Game, more commonly referred to as a SRPG (Strategy Role Playing Game).

## Table of Contents
* [Release Notes](#release_notes)
	* [v0.1.1](#v0.1.1)
	* [v0.1.0](#v0.1.0)
	* [v0.0.9](#v0.0.9)
	* [v0.0.8](#v0.0.8)
	* [v0.0.7](#v0.0.7)
	* [v0.0.6](#v0.0.6)
	* [v0.0.5](#v0.0.5)
	* [v0.0.4](#v0.0.4)
	* [v0.0.3](#v0.0.3)
	* [v0.0.2.5](#v0.0.2.5)
	* [v0.0.2](#v0.0.2)
	* [v0.0.1](#v0.0.1)
* [Tech Stack](#tech_stack)
* [Meta](#meta)
* [Contributing](#contributing)

## Release Notes <a name="release_notes"/>

### v0.1.1 ### <a name="v0.1.1"/>
* Currently in Progress!

### v0.1.0 ### <a name="v0.1.0"/>
* WIP

### v0.0.9 ### <a name="v0.0.9"/>
* WIP

### v0.0.8 ### <a name="v0.0.8"/>
* WIP

### v0.0.7 ### <a name="v0.0.7"/>
* WIP

### v0.0.6 ### <a name="v0.0.6"/>
* WIP

### v0.0.5 ### <a name="v0.0.5"/>
* WIP

### v0.0.4 ### <a name="v0.0.4"/>
* WIP

### v0.0.3 ### <a name="v0.0.3"/>
* Created new EquipmentFactory to setup equipment for gameplay.
* Added ability to setup equipment on unit's scriptable object.
* Removed old scripts & replaced prefabs with scriptable objects. 
* All equip data are auto-updated from changes made to csv files.
* Removed old enemy classes & created folders to hold equip data.
* Created new armors & items with the ability to parse csv files.
* Created new weapons for units to use and updated class data.
* Fixed some comments and variable names for greater clarity.

### v0.0.2.5 ### <a name="v0.0.2.5"/>
* Created new classes that will be used in actual gameplay.
* Provided a temporary view to see what attacks are being used.
* Implemented multiple attack options for the AI to display.
* Created very simple AI for enemy units to move and attack.
* Made multiple improvements & bug fixes to the turn controller.
* Added additional cutscenes to showcase win/loss results.
* Added basic victory conditions so the player can win or lose.
* Added new comments and edited variables for greater clarity.
* Renamed and moved several scripts to existing or new folders.
* Heavily commented all AI & enemy code for future modifications.

### v0.0.2 ### <a name="v0.0.2"/>
* Provided example units to showcase various game mechanics.
* Created a UnitFactory to auto-create game units for battles.
* Created several experimental scripts to be used for later.
* Implemented ability menu UI to showcase weapon/unit data.
* Implemented ability effects and damage power for all weapons.
* Fixed several EasingControl & Tweener bugs occurring in-game.
* Updated battle UI to showcase damages and status hit rates.
* Added hit rate mechanics for both standard & status attacks.
* Added status effect mechanics and made the new poisoned status.
* Implemented turn order/phases for both player & enemy units.
* Added minimum & maximum ranges for unit's actions & attacks.
* Added area of effect for certain actions performed by units.
* Reorganized all movement and range-related scripts in Assets.
* Added attack ranges for all units to select potential targets.
* Created a stat panel to view all units' class stats.

### v0.0.1 ### <a name="v0.0.1"/>
* First build push to GitHub containing all initial project files.

## Tech Stack <a name="tech_stack"/>
* Unity3D
* Visual C#
* Visual Studio Community 2015

## Meta <a name="meta"/>
[Yamil Burgos](https://github.com/yamilburgos/) – yamil.burgos1293@gmail.com

## Contributing <a name="contributing"/>
1. [Fork it](https://YBurgos@bitbucket.org/YBurgos/troop-command.git/)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request