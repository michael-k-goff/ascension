# Properties

Most data relevant to the player will be stored as properties attached to each map location.

## General

I plan to store properties as long vectors of values attached to every map location. My hope is that most property management can be done with matrix multiplication for efficient processing. On a given turn, a map location's properties are only affected by its immediate neighbors, children locations, and parent location. It may take several turns for a property to diffuse. For example, if a new factory is built, it creates pollution, which will spread across neighbors over several turns.

## Units

Rather than treating each individual unit as a seperate object, each map location will have a number that represents the quantity of the unit. For example, there might be 6 Archers at a location. If moved to another location with Archers, then they may be merged. They can also be split. This is hoped to streamline the usage of large armies relative to treating each unit as a separate object.

Units require food and supplies, or else will diminish. Thus if attempting to invade a neighbor, it is necessary to plan these logistics.

## Buildings

Unlike in Civilization, there can be several of a building at a location, though there may be diminishing returns to the value of many buildings. This will be stored as a number at the location as well.

## Resources

There will be many tradable resources, such as metals, types of food, and so on. Trade will occur by properties flowing through cities and across civilizational lines if the civs agree to trade or have free trade policies.

## Demographics

Values representing the overall population, age breakdown, population by ethnicity, race, and religion, values, and education are properties.

## Crime

There will be at least one property for crime. This may be broken down into multiple properties for different types of crime.

## Pollution

Properities such as particulates, greenhouse gases, ozone depletion, nitrous oxide, sulfur dioxide, water pollution, noise, light pollution, urban heat islands, and other kinds of pollution will be their own properities.

## Economics

Economic properties, such as unemployment and inflation, will be properities.

## Social

There will be several social properties, a major purpose of which is to regulate the pace of expansion. One property will be Revolution. If too high, a territory might break off and form a separate civilization or join another civilization. Corruption, Bureaucracy, and Special Interests will be properties. If too high, which will be the case if the player tries to expand farther than the current technology level allows, cities on the periphery will cost more to maintain than they produce and are thus a net drag on civilizational power.