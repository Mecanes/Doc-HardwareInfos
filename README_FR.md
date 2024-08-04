# Doc-HardwareInfos

## Plan
<!--ts-->
* [Description](#Description)
* [Objectif](#Objectif)
* [Exigence](#Exigence)
* [Avertissement](#Avertissement)
* [Installation](#Installation)
* [Contenu](#Contenu)
* [Detail](#Detail)
* [Caractéristiques & applications](#Caractéristiques-et-applications)
* [License](#Licence)
* [Auteur](#Auteur)
* [Histoire](#Histoire)

## Description

Le plugin "HardwareInfos" est une solution puissante et intuitive pour récupérer et afficher les informations sur le matériel des joueurs. Conçu pour les développeurs et les administrateurs de serveurs de jeux, ce plugin fournit des détails précis et complets sur la configuration matérielle des joueurs, permettant une meilleure gestion des performances et une résolution rapide des problèmes. 

## Objectif

L'objectif de "HardwareInfos" est de fournir des détails sur le matériel des joueurs afin d'optimiser les performances et de résoudre les problèmes.

## Exigence

Version cible : UE5.2 ～ 5.4

Plate-forme cible : Windows

## Avertissement
Il se peut que le plugin ait des difficultés à collecter des informations correctes sous certaines conditions de CPU / GPU / RAM . Nous travaillons dur sur ce sujet et nous le mettrons à jour régulièrement pour le rendre compatible avec une large gamme de matériel. 

Test done :

CPU :

- [x] RYZEN 5000
- [ ] INTEL

GPU:

- [x] NVIDIA 4000
- [ ] AMD


## Installation

Installez le plugin via le Marketplace d'UE.

Si la fonctionnalité n'est pas disponible après l'installation du plugin, il est possible que le plugin n'ait pas été activé. Veuillez vous assurer que le plugin est activé en allant dans Editer > Plugins.

## Contenu

Il y a 4 structure :
* Get Hardware Data
* Get CPU Data
* Get GPU Data
* Get Ram Data

> **Ses structures peuvent être utilisées dans tous vos Blueprint ( Acteur, Personnage, ... )**
>> **Connaître au moins les bases du Blueprint (structure)**

![Structure Infos](https://github.com/Mecanes/Images/blob/main/structure_infos.png?raw=true)

## Caractéristiques et applications

#### Code Example
![CPU Example](https://github.com/Mecanes/Images/blob/main/CPU_DATA.png?raw=true)

### Detail
- [x] CPU
    - Company : retourne le nom de la company , ***par exemple : AMD***
    - Name : retourne le nom du prossesseur , ***par exemple : RYZEN***
    - Number : retourne le nombre , ***par exemple : 7***
    - Series Complet : retourne le nom complet , ***par exemple : 5800x***
    - Series : retourne la series , ***par exemple : 5000***
    - Core : retourne le nombre de core , ***par exemple : 8***
- [x] GPU
    - Company : retourne le nom de la company , ***par exemple : NVIDIA***
    - Name : retourne le nom du prossesseur , ***par exemple : GEFORCE***
    - Mark : retourne la marque , ***par exemple : RTX***
    - Model : retourne le Model , ***par exemple : 4060 ti***
    - Minimun Model : retourne ***par exemple : 4060***
    - Series : retourne la serie , ***par exemple : 4000***

## Licence

[MIT License](https://en.wikipedia.org/wiki/MIT_License)

## Auteur

[Mecanes](https://x.com/MecanesFr)

## Histoire

- [x] [03/08/2024] Creation de la Documentation officiel
