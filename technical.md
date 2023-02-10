# Technical

I am not sure yet whether this game should be sold or distrubuted for free.

For ease of usage, the game should be implemented in Javascript and run in modern browsers without any additional installation required. Due to the large maps and large number of properties envisioned, performance could be a challenge. I imagine that the most efficient way to do this will be to stores all properties at a map location as a vector, and at each turn, add to each location's property vector the product of a hard-coded matrix and the property vectors associated with all neighboring tiles, including the parents and children.

If four neighbors are assumed (not diagonals), there should on average be six matrix muliplications and vector additions each turn for each location.

Due to the sparsity of the property matrix, this might not be the most efficient approach. It will also be necessary to perform some non-linear postprocessing, such as for example insuring that certain resources such as gold cannot go below zero.

I imagine that there could be as many as 50,000 locations open at a given time (there may be more total, but as some open up later in the game, others will close). I imagine that there could be as many as 1000 properties. This gives 50 million properties that need to be updated every turn. That could be a challenge.

Since it will take a while each turn to move units, select buildings, and do other things, property updates will occur throughout the turn, to minimize the wait time at the end of the turn.