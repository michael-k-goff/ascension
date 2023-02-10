# The World

The world is to be a tree, with the world as a whole as the root node. A parent-child relationship should be viewed as containment. For example, in a full multiverse map, the children of the root might be individual universes, the children of those nodes might represent galaxies, and so forth.

## Map Dynamism

Map components are created and destroyed dynamically. For example, a cislunar map does not inintially exist, but when the player is able to explore cislunar space with satellites and astronautics, a cislunar map is created.

A player is also able to create maps through certain events, or perhaps directly through gameplay actions. For example, a city might be represented as a single node, but when it grows to a single size, a player can "zoom in" on it, thereby opening a new map that will allow more detailed city planning.

Likewise, maps may be destroyed at certain gameplay junctures. At some point in the game, for instance, an island, which had previously been treated as an array of tiles, may be compressed into a single tile. The property system should be such that the compression of a map does not have a major effect of the evolution of properties.

## Exploration

At the start of the game, most of the map is blacked out. Tiles are revealed if in the line of sight of a unit or city. If they case to be in the line of sight, they become gray with the fog of war. Early in the game, unseen tiles may eventually become black again to represent the forgotting of the world structure.

## Navigation

A node and its siblings will generally comprise a grid of squares or hexagons, through which units can navigate normally. Where applicable, there will be options to zoom in our out. For example, a rocket that zooms out from an Earth map will be in cislunar space and can then navigate that. The number of moves per turn may vary depending on the map level.

A unit has a given number of moves per turn. The rate as which these moves are expended depends on the types of terrain (moving through a forest may be more costly than moving across open grassland, for instance) and the map level. If multiple units are merged on a single tile, the number of turns remaining may be the minimum of the number for the merged units, or a weighted average of the moves remaining.