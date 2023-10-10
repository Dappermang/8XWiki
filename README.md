
<div align=center>  <h1> 8XWiki </h1>  </div>

# Welcome
Welcome to the 8XWiki! This repository is here to contain all of my libraries wiki pages.

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Disclaimer](#disclaimer)
- [Documentation](#documentation)
- [Installation](#installation)
- [Modules](#modules)
  - [Clock](#clock)
  - [Animo](#animo)
  - [Submarine](#submarine)
  - [AStar](#astar)
- [Contributing](#contributing)

# Disclaimer
<i>This library is intended for use with GameMaker Versions 2.3.X+ Don't come crying if it doesn't work on previous versions!</i>

Nearly everything in this repository is work-in-progress and undocumented, so not every Module will be available yet. Feel free to contribute to make that faster!

# Documentation
[Documentation is work-in-progress, so please feel free to contribute](https://github.com/Dappermang/8XLib/wiki)</link>.

# Installation
Here's how to install:
1. Download the latest <link>[release or prerelease](https://github.com/Dappermang/8XLib/releases)</link>.
2. Open GameMaker
3. Goto Tools -> Import Local Package

# Modules
Modules are marked "released" or "unreleased" depending on if they are available in the GitHub release

## Clock
**Released** :white_check_mark:

This module features;
- Timers
- Timer Controllers

Timers are small structs that can be modified with a bunch of different options like randomized tick-rates, set time, callbacks etc.
Timer controllers can be used to control groups of timers at once.

## Animo
**Released** :white_check_mark:

This module features;
- Lightweight animation structs that are highly modular.
- Globally scoped animation map that you can store individual character animations in.
- Auto adding animations to the global map based on GameMaker's asset tags.
- Single, Looped and Chained animation types.
	- Single: Will only animate once.
	- Looped: Will animate based on an amount of iterations defined.
	- Chained: Will animate based on iterations and switch to another defined animation once it reaches its maximum iterations.

## Submarine
**Prerelease** :hammer:

This module features;
- Event Handler
- Event subscription and publication

Objects or Structs can be subscribed to an event and when an event is published, a callback ( if defined ) will execute.

## AStar
**Unreleased** :interrobang:

This module will feature;
- AStar Grids
- AStar Search

## Contributing
Issues, PRs, Feature Requests are all welcome!
[Please read the associated style-guide, while it is not a requirement it is appreciated!](https://github.com/Dappermang/8XLib/blob/release/CONTRIBUTING.md)
