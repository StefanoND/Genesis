# Folder Structure

Inspired by:

[Shantnu Tiwari](https://new.pythonforengineers.com/author/shantnu/)'s [How to structure your godot project so you don't get confused](https://new.pythonforengineers.com/blog/how-to-structure-your-godot-project-so-you-dont-get-confused/)
[Josh Anthony](https://joshanthony.info/)'s [How I structure my game projects](https://joshanthony.info/2021/12/06/how-i-structure-my-game-projects/)

## INIT

Main Scene

## CORE_CONFIG

INIT's script and tells which screen file will be loaded first

## Directory Structure

Each directory have their own README further explaining their purpose.

### \_debug

Isolated system(s) to aid in debugging.

### \_samples

Individual systems at their default state.

### \_tests

Systems, features, functionalities, etc being worked on.

### addons

3rd-Party content.

### assets

Resources that are used in the game.

### bridges

Connects systems together without affecting their reusability/modularity.

### config

Exposed configurations from systems.

### core

Generalized and Reusable systems, features, UIs, etc across multiple games.

### docs

Project's Documentations.

### game_objects

Everything that will be in the game.

### game_world

Levels, maps, areas, etc that will be in the game.

### helpers

Libraries with generalized helper functions, vars, consts, etc.

### src

Where all scripts in the game are.

### systems

Systems, functionalities, features, etc of the game

### ui

Generalized and Specific UIs

### utils

Anything that aids/helps with the development, that won't be in the final game.
