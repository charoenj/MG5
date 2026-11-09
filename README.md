# MG5
## Devlog
Put your Devlog here.

1. NavMesh is more useful when you're navigating around obstacles and when the player needs to automatically find a path instead of having to control every movement meticulously. A game that I think would benefit from NavMesh is most likely Sims. They need to walk around furniture and not clip through walls. On the other hand, a game that might not need NavMesh is a game with meticulous movement where every jump and run counts such as Super Mario Bros. This is also important because collisions occur for that game like with the lucky blocks and for the wall jumping, so it is important for the character to be able to interact with the environment without the movement and physics being limited.
2. The for loop goes through every bird in the _birds array. It starts at index 0 and continues till the end of the array (I did not hard code it to the number of the birds in this case, but I could have put 3). For each bird, Vector3.Distance calculates the distance between the bird's position and the player's position (it is basically checking how close each bird is to the player. For the if statement, any bird that is within or equal to the _interactDistance it will run away from the player. Birds that are farther away than the interaction distance will not run away. So the birds only react if the player gets close enough to them.


## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
