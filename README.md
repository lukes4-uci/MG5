# MG5
## Devlog
1. Scripting is helpful for when the entity's movement behavior is limited or controlled, and does not encounter strange terrain or other conditions. Navmesh is more important for when the entity has to navigate around uncontrolled in an environment with obstacles or limited paths. Navmeshes would makes sense for RTS games like the Total War series, where creatures would have to moves around complicated terrain like hills and forests, while scripted movement makes more sense with games like traditional 2D fighting games, where there are only 2 players inside of a small, flat area.
2. The for loop checks the distance between the player and each bird within the list; if that distance is less than or equal to the _interactDistance variable, the script calls the RunAway function on that bird to make it run away from the player's position. This means that only bird at a distance less than or equal to the _interactDistance variable from the player will run away. 

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
