# Design Document

## General

The game's working title is Ascension.

## Gameplay

The game will probably have a turn-based structure, though a real-time structure is possible. The property system described below might lend itself more to turn-based gameplay.

## World

See [details](world.md) about the structure, exploration, and navigation of the world.

## Technology

See [details](tech.md) about technological progression.

## Buildings

See [details](buildings.md) about construction, maintenance, and operation of buildings.

## Properties

See [details](properties.md) about the property systen.

## Other Civilizations

See [details](diplomacy.md) about diplomacy and warfare with other civilizations.

## Graphics

The graphics will be simple. The main display will main a map, most of which will be a square or hexagonal array of tiles. There are several layers to the map representing different properties. The player can see buildings and units, or toggle to other properties. The player can also click on a location and get a detailed view of the properties at that specific location.

## Interface

On the left side of the screen will be a layered menu to access buidings. The player can select a building through the menu, then click on a map location to begin construction at that location.

The player can also click on a location that they control, and if there are buildings with actions available, the player can then choose the building, and then the action. There might be an additional submenu depending on the action.

For example, if the player wants to train an archer, they would click on a location that contains a Barracks, select the Barracks, and then "Train Archer". The training process then commences, which requires turns and resources, just like constructing buildings.

## Sound

I want 3-5 original songs for each era, representative of that era. They will play in a cycle during gameplay. If this cannot be done, there should be plenty of public domain music that will suffice.

There should be appropriate sound effects for menu navigation, combat, and other major events.

## Technical

See some [details](technical.md) about implementation.