# BetterAPI

A simple library that adds thin wrappers around the new RoR2 Content Pack system with some helper functionality.
This is far from complete, if you want me to add something to it, I might do it, see how to contact me below.
It should be enough to implement simple items, buffs, etc. 

For an example, check out https://github.com/xoxfaby/MoreItems


## Currently implemented APIs:
 - Items
 - Buffs
 - Languages
 - Prefabs
 - Objectives
 - CostTypes
 - Interactables (BETA)
 - Stats (BETA)

## Support Me

If you like what I'm doing, consider supporting me through GitHub Sponsors so I can keep doing it:

https://github.com/sponsors/xoxfaby

## Help & Feedback

If you need help or have suggestions, create an issue on github, join my discord or find me on the RoR2 Modding Discord 

[My Discord](https://discord.gg/Zy2HSB4) XoXFaby#1337

https://github.com/xoxfaby/BetterAPI

## Changelog

## v1.3.0
 - Added Stats API:
   This API provides an easy way to add stats characterBody's without having to deal with IL hooks. 
   Currently the API barely has any implemented, if you need easy access to a stat for your mod it's best to suggest it to us in our Discord so we can add the appropriate functionality.
 - This version also ensures that RoR2 knows the game is modded when BetterAPI is used. I don't see any reason a clientside non-game-affecting mod would need to use BetterAPI so this is not likely to be changed. 
 - 

### v1.2.1
 - Updated for latest RoR2 Patch. 
   This is NOT a breaking change, if your mod uses BetterAPI it should continue working now. 

## v1.2.0
 - Buffs: Fixed error that stopped buffs from being added correctly;
 - CostTypes: Added CostType API, mainly used for interactables.
 - Objectives: Added Objectives API to add objectives to the tracker on the top right.
 - Added various prefab APIs:
   - BodyPrefabs
   - MasterPrefabs
   - NetworkedPrefabs
   - ProjectilePrefabs
   - Added Util method for creating prefabs from existing gameobjects.
 - BETA: Interactables: Added Interactables API for adding interactables such as chests, shrines, anything you want. 
   This API is under active development, expect breaking changes in future updates as it is worked on. 
   Join the discord if you are planning to use this API.

### v1.1.2
 - Items: Added ability to add ItemDisplays to characters that didn't originally have an ItemDisplayRuleSet (Heretic)

### v1.1.1
 - Items: Improved ItemDisplay support:
   - Set ItemDisplay by CharacterModel name or bodyPrefab name
   - Easier to use CharacterItemDisplayRuleSet helper to make adding ItemDisplays super simple
   - ItemDisplay component automatically added to followerPrefab if it's missing to avoid errors.
   - Fully backwards compatible, but I encourage using the new helper, once again see MoreItems for examples. 

## v1.1.0
 - Items: Added ItemDisplay support

## v1.0.0
 - Inital Release