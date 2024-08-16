# Doc-HardwareInfos

![Plugin](https://github.com/Mecanes/Images/blob/main/plugins.png?raw=true)

## Plan
<!--ts-->
* [Description](#Description)
* [Objective](#Objective)
* [Requirement](#Requirement)
* [Warning](#Warning)
* [Installation](#Installation)
* [Contents](#Contents)
* [Advantages and uses](#Advantages-and-uses)
* [Details](#Details)
* [Features & applications](#features-&-usages)
* [License](#License)
* [Author](#Author)
* [History](#History)

## Description

The "Hardware Info" plugin is a powerful and intuitive solution for retrieving and displaying player hardware information. Designed for developers and game server administrators, this plugin provides accurate and comprehensive details of players' hardware configuration, enabling better performance management and rapid problem resolution. 

## Objective

The objective of "Hardware Info" is to provide details of players' hardware to optimize performance and solve problems.

## Requirement

Target version : UE5.2 ～ 5.4

Target platform : Windows

## Warning
It may be that the plugin has trouble collecting good information under certain CPU / GPU / RAM . We're working hard on this and will be updating it regularly to make it compatible with a wide range of hardware. 

Test done :

CPU :

- [x] RYZEN 5000
- [ ] INTEL

GPU:

- [x] NVIDIA 4000
- [ ] AMD


## Installation

Install the plugin via the marketplace .

If the functionality isn’t available after installing the plugin, it’s possible that the plugin hasn’t been activated. Please make sure the plugin is enabled by going to Edit > Plugins.

## Contents
There are 4 structure-type Blueprints :
* Get Hardware Data
* Get CPU Data
* Get GPU Data
* Get Ram Data
* Get data from the player's screen
* Get Player FPS

> **Its structures can be used in all your blueprints ( Actor, Character, ... )**
>> **Know at least the basics of blueprint (structure)**

![Structure Infos](https://github.com/Mecanes/Images/blob/main/UE.png)

## Advantages and uses
***Advantage*** :
* **Improved server performance**: Quickly identify weak hardware configurations and optimize performance accordingly.
* **Simplified technical support**: Easier diagnosis of hardware problems, enabling faster and more accurate assistance.

***Use cases*** :
* **Game developers**: Use hardware data to adapt and optimize your game for the most common hardware configurations.
* **Gamer communities**: Offer enhanced technical support by quickly identifying hardware problems.

### Details
- [x] CPU
    - Company : returns the name of the company , ***for example : AMD***
    - Name : returns the name of the prossessor , ***for example : RYZEN***
    - Number : returns the number , ***for example : 7***
    - Series Complete : returns the complete name , ***for example : 5800x***
    - Series : returns the series , ***for example : 5000***
    - Core : returns the number of core , ***for example : 8***
- [x] GPU
    - Company : returns the name of the company , ***for example : NVIDIA***
    - Name : returns the name of the prossessor , ***for example : GEFORCE***
    - Mark : returns the brand , ***for example : RTX***
    - Model : returns the Model , ***for example : 4060 ti***
    - Minimun Model : returns ***for example : 4060***
    - Series : returns the series , ***for example : 4000***


## Features & applications

#### Code Example
![CPU Example](https://github.com/Mecanes/Images/blob/main/CPU_DATA.png?raw=true)

## Licence

[MIT License](https://en.wikipedia.org/wiki/MIT_License)

## Author

[Mecanes](https://x.com/MecanesFr)

## History

- [x] [03/08/2024] Creation of official documentation
