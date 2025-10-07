## FuelWings Refueled: A successor to FuelWings

- FuelWings originally made by [@diygary](https://github.com/diygary) (AKA Tortoise), later adopted by [@linuxgurugamer](https://github.com/linuxgurugamer), and finally remastered by me, [@munktron239](https://github.com/munktron239)
- How to use this mod: Simply build your plane, select which wing pieces you want to have fuel in, and choose your desired fuel type! See wings.png for exact fuel values.

-------------------------------------------------------------------------------------------------------------------------------------------------

- FuelWings is an awesome mod. I love being able to store fuel inside of wings, just like many aircraft do in real life.
- Unfortunately, the mod was made a very long time ago. Like '10+ years' long ago. KSP has changed a lot since 2014.
- Currently, FuelWings depends on ``Firespitter.dll`` for the switching module, which itself is quite outdated (5+ years old).
- Since nobody really uses Firespitter anymore, I wanted to completely overhaul this mod using the much more reliable B9PartSwitch.

-------------------------------------------------------------------------------------------------------------------------------------------------

## Why use Refueled over the original FuelWings?

- User-friendly: No more clicking 'Next Tank' to guess what fuels are available. Fuel types are easily visible and have description support.
- Game balance: Parts stats are identical to stock. Existing craft with wings will default to 'Structural', and mass/cost will remain unchanged.
- Logical: Doesn't add fuel to any nosecones; their purpose is for aerodynamics and not for fuel storage. Tail connectors do get fuel, though!
- Consistency: In FuelWings, some volume levels were slightly off or too high. In Refueled, all fuel values are consistent across similar parts.
- Moar fuel types: Fuel types such as LH2 and Hydrolox are possible using CommunityResourcePack. CryoTanks boiloff is also supported.
- Easy expansion: Add fuel to your own wing parts with one easy MM patch! See ``AssignTagsToWings.cfg`` for more instructions.

-------------------------------------------------------------------------------------------------------------------------------------------------

## Drawbacks

- For wings that already have fuel (Big-S Delta Wing, FAT-455 Aeroplane Main Wing, etc), B9 changes the dry mass/cost by a small amount.
- If you decide to use fuel in these wings, performance will be (ever-so-slightly) worse than in stock.
- Because of this, this patch affecting these wings is disabled by default. If PatchManager is installed, then you can enable it in-game.
- Currently no support for B9ProceduralWings. This may change in future versions, though.

-------------------------------------------------------------------------------------------------------------------------------------------------

## Dependencies and Supported Mods

- [ModuleManager](https://forum.kerbalspaceprogram.com/topic/50533-18x-112x-module-manager-423-july-03th-2023-fireworks-season/)
- [B9PartSwitch](http://forum.kerbalspaceprogram.com/index.php?showtopic=140541)
- (Optional) [PatchManager](https://forum.kerbalspaceprogram.com/topic/163072-112x-patchmanager/)
- (Optional) [CommunityResourcePack](https://forum.kerbalspaceprogram.com/index.php?/topic/83007-*)
- (Optional) [CryoTanks](https://forum.kerbalspaceprogram.com/topic/195042-112x-cryotanks-liquid-hydrogen-storage-and-management-aug-13-2024/)
- If PatchManager is installed, fuel switches for the Big-S/FAT-455 wings can be enabled in-game.
- If CRP is installed, LiquidHydrogen and Hydrolox fuel switches will be available.
- If CryoTanks is installed, cryogenic fuel types will require EC cooling.

-------------------------------------------------------------------------------------------------------------------------------------------------

## Credits and Thanks

- [@diygary](https://github.com/diygary) for creating the original FuelWings mod way back during the golden days of KSP.
- [@linuxgurugamer](https://github.com/linuxgurugamer) for adopting FuelWings, and for inspiring me to create my own version.
- [@JadeOfMaar](https://github.com/jadeofmaar) for basically rewriting the entire mod for me, and for helping out in general.
- You! For making it to the very end of this README file. Thanks for checking it out!
