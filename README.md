# Welcome to the QuestCraft GitHub!
[Support us on Patreon!](https://patreon.com/QuestCraftXR)

First off, you most likely want to install QuestCraft. If you would like to get going instantly then please go to the release page for [QuestCraft](https://github.com/QuestCraftPlusPlus/QuestCraft/releases/latest) and download the APK to your computer or mobile device.

### We are partnered with BisectHosting! Support us by going to their [website](https://bisecthosting.com/xrcraft) and using code "xrcraft" at checkout to get 25% off of any server over 3GB.

![sponsor image](/partnerimage.png)
# Installation Instructions

**NOTE: In order to install QuestCraft, you must have an internet connection in order for the inital setup to succeed. Furthermore, you MUST own a legal, valid copy of Minecraft: Java Edition to play!**

First, you need to install the QuestCraft APK to your VR Headset using [SideQuest](https://sidequestvr.com) (Recommended, available on Windows, macOS, Linux, and Android) or with [QuestToolbox](https://github.com/mitchv2020/QuestToolbox) (Available on Windows, Auto Installer coming to QuestToolbox soon).

Next, open the QuestCraft launcher on your headset. Be sure to grant it all requested permissions. Once complete, follow the on-screen prompts to enter your Minecraft login details and wait for QuestCraft to download any remaining files.

And boom! You have successfully installed QuestCraft on your VR headset! To play, simply press the **Play** button and wait for it to load, it might take a while depending on headset age and model.

## Included Mods (Performance is key!) 

[Better Biome Blend](https://modrinth.com/mod/better-biome-blend) (Fixes and adds features to the Biome Blend setting)                                                                                                                           

[Concurrent Chunk Management Engine (C2ME)](https://modrinth.com/mod/c2me-fabric) (Improves chunk loading)

[Cloth Config](https://modrinth.com/mod/cloth-config) (Libary for config screens, e.g. Video Settings)
                                                                                                                                                  
[Entity Culling](https://modrinth.com/mod/entityculling) (Renders only visible blocks and entities, improving overall performance)

[Fabric API](https://modrinth.com/mod/fabric-api) (API for Fabric. Essential to basically get any mod running.)

[Fastload](https://modrinth.com/mod/fastload) (Improves world load and prevents potential crashes)

[Ferrite Core](https://modrinth.com/mod/ferrite-core) (Decreases memory usage by doing technical stuff)

[Immediately Fast](https://modrinth.com/mod/immediatelyfast) (Optimizes lots of things, making rendering more GPU efficient)

[Krypton](https://modrinth.com/mod/krypton) (Slightly reduces memory usage on servers, lowers server CPU usage and server ticks)

[LazyDFU](https://modrinth.com/mod/lazydfu) (Improves game boot time, by making DataFixerUpper do less stuff)

[Lithium](https://modrinth.com/mod/lithium) (General purpose performance mod)

[MaLiLib](https://www.curseforge.com/minecraft/mc-mods/malilib) (Libary to make more mods work)

[Smooth Boot](https://modrinth.com/mod/smoothboot-fabric) (Makes Minecraft loading smoother)

[Sodium](https://modrinth.com/mod/sodium) (Improves FPS and fixes graphical issues)

[Starlight](https://modrinth.com/mod/starlight) (Improves the lighting engine)

[Tweakeroo](https://www.curseforge.com/minecraft/mc-mods/tweakeroo) (Big QOL mod that changes alot of things)

[VivecraftMod](https://github.com/ferriarnus/VivecraftMod) (Port of Vivecraft to run on Fabric)

[Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat) (Adds proximity voice chat)

## Recommended mods

QuestCraft is fairly slow by itself because minecraft is a very badly optimized game. QuestCraft already includes a couple of mods to enhance the performance, but here is a (not comprehensive) list of some more recommended mods:

- [More Culling](https://modrinth.com/mod/moreculling) (Culls not just leaves, but loads of other things to improve performance. Getting [More Culling Extra](https://modrinth.com/mod/morecullingextra) will also add more culling features!)
- [Architectury API](https://modrinth.com/mod/architectury-api) (makes lots of mods available)
- [Indium](https://modrinth.com/mod/indium) (Uses the Fabric Rendering API to allow many mods to work with Sodium) (**NOTE: You must have the latest [Sodium](https://modrinth.com/mod/sodium) version in order for the mod to work, otherwise the game WILL crash.**)
- [Mod Menu](https://modrinth.com/mod/modmenu) (Adds a mod menu to see what mods and libraries are present, and if [YetAnotherConfigLib](https://modrinth.com/mod/yacl) is present, can customize mod settings)
- [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) (Adds dynamic lights to light emitting blocks, making the lighting more realistic and better overall.)
- [Exordium](https://modrinth.com/mod/exordium) (Decrease GUI framerate to speed up world rendering)

**NOTE: When installing (supported) mods on your Quest, you may need to update a dependancy that's bundled in with QCXR (e.g. Fabric API, Sodium). However, this may lead to issues, ranging from unexpected behavior to crashes! If you experience any, please [file an issue](https://github.com/QuestCraftPlusPlus/QuestCraft/issues/new/choose).**
At the moment, Iris and Canvas do not work. Distant Horizons support is planned, but may take a while. 

## Some recommended Settings and Tips 
1. In the options menu, go to VR Settings/Stereo Rendering and set the resolution (NOT CAMERA RES) to 80%. This will decrease the general quality, but will give an extra performance boost.
2. The game's render distance is best at 4. 5 works, but you may encounter lag spikes when using it. 6 and above, you are on your own.
3. Oceans contain LOTS of kelp that decrease framerate. Don't mine any of it all at once, as your game may CRASH if lots of entites (in this case, kelp waiting to be picked up) is exist at once.
4. If any leave culling mod (e.g. [Cull Leaves](https://modrinth.com/mod/cull-leaves), [More Culling](https://modrinth.com/mod/moreculling)) is present, you can set the leaves quality to Fancy!
5. You are able to max out Biome Blend if you have QCXR 3.1 or later!
6. If [More Culling](https://modrinth.com/mod/moreculling) is present, go to the video settings and go to the More Culling tab. Set the leave culling type to Depth and enjoy a performance boost!


# Notes
- We do not exist on TikTok. No one from the dev team makes TikTok videos. 
- QuestCraft (QCXR) is developed and maintained by the QCXR team, we also contribute upstream to the open source tools that we used to make this a reality, make sure to check out [MCXR](https://github.com/mcxr-org/MCXR), the previous VR mod, now replaced with [VivecraftMod](https://github.com/ferriarnus/VivecraftMod) and [PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher) (for Pojlib)! 
- All support questions should be asked inside of the QuestCraft Discord (discord.gg/questcraft) for the best experience.
- **questcraft.net is not maintained or owned by anyone on the questcraft team**, they could put malware on it at any time. Please do not download anything from or visit questcraft.net. **Our new website is located here at [QuestCraft](https://questcraft.org/). 
- Pico support isn't planned for time being. Until then, use Vivecraft PCVR.
## Controls

![There's supposed to be controls here](/Control.png)

These controls are subject to change.
