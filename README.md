# Alexa Dungeon ![travis build status](https://travis-ci.com/tganyan/11-14-express-api.svg?branch=master)

## Overview

An Alexa skill application that takes the user on a dungeon crawl, narrated by Alexa herself. 
#### The user can:
 * generate a character 
 * traverse a vast fantasy landscape
 * obtain weapons, potions, and spells
 * battle creatures that vary in difficulty and scale with the progression of the character
 
The game utilizes the [Dungeons and Dragons api](http://www.dnd5eapi.co/), along with character input to generate a DnD style dungeon complete with random enemy encounters, boss battles, skill rolls, and character progression.

## Usage

Below are some example commands to kickoff and control your adventure:
```
Alexa, open Dungeon Crawl
    >> Hail, young adventurer. blah blah blah...
```
```
Alexa, go north
    >> You find yourself face to face with a baby wyvern!
```
```
Alexa, cast magic missile
    >> The giant rat took 15 damage from magic missile.
    >> The giant rat has died
```

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have **NodeJS** installed along with either **NPM** or **Yarn**. In addition, the **ASK-CLI** is required for development on this application.

### Installing

Copy the link from the github repository
In the command line, navigate to the parent directory where you want to store this project
In the command line, type:
```
git clone <repository url>
```
Once the project files are there, navigate to **/lambda/custom** and type:
```
npm install
```
or
```
yarn i
```

## Running the tests

* Test case example
```
TEST EXAMPLE
```


## Alexa speech models
```

```

## EDR

![edr-diagram](placeholder.jpg)

## Built With

* [NodeJS](https://nodejs.org) - The javascript runtime used
* [Jest](https://jestjs.io/) - Testing platform used
* [Eslint](https://eslint.org/) - Coding style linter


## Authors

* [**Tyler Anyan**](http://tyleranyan.com/)
* [**Tom North**]()
* [**Diego Ramos**]()
* [**Daniel Frey**]()
* [**Wyatt Peffley**]()

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
