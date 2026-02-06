# Noah Baron - DungeonLayoutGenerator - CMPM 147

This tool is designed to generate dungeon layout designs for a dungeon based rogue-like. Based on parameters, it will generate a floor plan that can be traversed with a start and end room, with some variation and branching paths. In this current implementation, the parameters for maximum room count and basic branching are implemented, with more to come on the way. This generator functions by creating a start room, then creating the linear “spine” of the dungeon until it reaches the end node. Then, it will loop over each of the rooms, and generate branching rooms off of that. This creates a dungeon with a somewhat linear flow, but keeps some variation of player choice.

This tool is created in UCSC's CMPM 147 - Generative Design class, instructed by Tyler Coleman

![Output](RoomLayoutOutput.jpg)
