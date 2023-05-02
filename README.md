# Welcome to the QuestCraft GitHub!
### **[Support us on Patreon!](https://patreon.com/QuestCraftXR)**

### We are partnered with BisectHosting! Support us by going to their **[website](https://bisecthosting.com/xrcraft)** and using code "xrcraft" at checkout to get 25% off of any server over 3GB.

![sponsor image](/partnerimage.png)
# QuestCraft
![QC](/QCSimple3.jpg)

QuestCraft, utilizing Vivecraft and Pojlib, is a standalone port of Minecraft: Java Edition to Oculus Quest Headsets. With a team of four main developers and 8 third party developers, over the past year we have not only gotten the bestselling game, Minecraft: Java Edition running on Android, but we have also worked with third-party developers to bring it into Virtual Reality on the Oculus Quest line of standalone HMDs.

# Features
- ### **Roomscale Minecraft VR!** 
- ### **~~Quest and~~ Quest 2 Native!**
- ### **Full Multiplayer in VR!**                                                                    
- ### **Immersive Controls through Vivecraft, Like Punching Blocks!**                                                                                                   
- ### **Supports 1.19.4, 1.19.3, 1.19.2, and 1.18.2!**                                                                                                                                 
- ### **Includes a Unity and Pojlib-built *launcher* that allows you to start QuestCraft, switch between versions and renderers, and use Mod Manager, a tool to download and install supported mods right from your Quest!!**
**Quest 1 Support is no longer available due to Quest Software v51.**

# Installation Instructions

**NOTE: In order to install QuestCraft, you must have an internet connection in order for the initial setup to succeed. Furthermore, you MUST own a legal, valid copy of Minecraft: Java Edition to play!**

First off, you most likely want to install QuestCraft. Please go to the release page for **[QuestCraft](https://github.com/QuestCraftPlusPlus/QuestCraft/releases/latest)** and download the APK to your computer or Android device.

Secondly, you need to install the QuestCraft APK to your VR Headset using **[SideQuest](https://sidequestvr.com)** and follow the necessary steps to connect your Quest. Drag and drop the APK, and wait for it to install.

Next, open the QuestCraft launcher on your headset. Be sure to grant it all requested permissions. Once complete, follow the on-screen prompts to enter your Minecraft login details and wait for QuestCraft to download any remaining files (seen in the bottom-right).

And boom! You have successfully installed QuestCraft on your VR headset! To play, simply press the **Play** button and wait for it to load, it might take a while depending on headset age and model.

## Supported Renderers (Take note when installing mods!)

- ### Zink
**[Zink](https://docs.mesa3d.org/drivers/zink.html)**, while being primarily slow, has great mod compatibility. Complex mods like Distant Horizons and Immersive Portals should work.
- ### Vulkan
**[Vulkan](https://www.vulkan.org/)**, while being very fast, has low mod compatibility. Complex mods like Distant Horizons and Immersive Portals should work.

## Included Mods (For Zink)
### These mods are preinstalled and are for use with **Zink** in order to increase performance. Vulkan does not have any, as it's fast on its own.

- **[Better Biome Blend](https://modrinth.com/mod/better-biome-blend)** (Fixes and adds features to the Biome Blend setting)                                                                                                                           

- **[Cloth Config](https://modrinth.com/mod/cloth-config)** (Libary for config screens, e.g. Video Settings)

- **[Concurrent Chunk Management Engine (C2ME)](https://modrinth.com/mod/c2me-fabric)** (Improves chunk loading)

- **[Cull Less Leaves](https://modrinth.com/mod/cull-less-leaves)** (Culls leaves for performance, 1.18.2 only!)
                                                                                                                                                  
- **[Entity Culling](https://modrinth.com/mod/entityculling)** (Renders only visible blocks and entities, improving overall performance)

- **[Fabric API](https://modrinth.com/mod/fabric-api)** (API for Fabric. Essential to basically get any mod running.)

- **[Ferrite Core](https://modrinth.com/mod/ferrite-core)** (Decreases memory usage by doing technical stuff)

- **[Fastload](https://modrinth.com/mod/fastload)** (Improves world load and prevents potential crashes)

- **[Immediately Fast](https://modrinth.com/mod/immediatelyfast)** (Optimizes lots of things, making rendering more GPU efficient)

- **[Krypton](https://modrinth.com/mod/krypton)** (Slightly reduces memory usage on servers, decreases server CPU usage and server ticks)

- **[LazyDFU](https://modrinth.com/mod/lazydfu)** (Improves game boot time, by making DataFixerUpper do less stuff)

- **[Lithium](https://modrinth.com/mod/lithium)** (General purpose performance mod)

- **[MaLiLib](https://www.curseforge.com/minecraft/mc-mods/malilib)** (Libary for some mods)

- **[Smooth Boot](https://modrinth.com/mod/smoothboot-fabric)** (Makes Minecraft loading smoother)

- **[Sodium](https://modrinth.com/mod/sodium)** (Improves FPS and fixes graphical issues)

- **[Starlight](https://modrinth.com/mod/starlight)** (Improves the lighting engine)

- **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)** (Port of Vivecraft to run on Fabric)

- **[Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat)** (Adds proximity voice chat)

## Some Recommended Settings and Tips (For Zink)
1. In the options menu, go to VR Settings/Stereo Rendering and set the resolution (NOT CAMERA RES) to 80%. This will decrease the general quality, but will give an extra performance boost.
2. The game's render distance is best at 4-6, but you *may* encounter lag spikes when using it. 9 and above is not recommended.
3. Oceans contain LOTS of kelp that decrease framerate. Don't mine any of it all at once, as your game may CRASH if lots of entities (in this case, kelp waiting to be picked up) exist at once.
4. [Skyblock](https://minecraft.fandom.com/wiki/Tutorials/Skyblock) and [Oneblock](https://www.curseforge.com/minecraft/worlds/oneblock) worlds perform the best, as they require less hardware usage.

# Notes
- We do not exist on TikTok. No one from the dev team makes TikTok videos.
- QuestCraft (QCXR) is developed and maintained by the QCXR team, we also contribute upstream to the open source tools that we used to make this a reality, make sure to check out **[MCXR](https://github.com/mcxr-org/MCXR)**, the previous VR mod, now replaced with **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)**, **[PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)** (for Pojlib!), and **[VulkanMod](https://github.com/xCollateral/VulkanMod)** for Vulkan support!
- The QCXR forks we use are **[Pojlib](https://github.com/questcraftplusplus/pojlib)**, **[VivecraftMod](https://github.com/questcraftplusplus/vivecraftmod)**, and **[VulkanMod](https://github.com/QuestCraftPlusPlus/VulkanMod).** 
- All support questions should be asked inside of the QuestCraft Discord (discord.gg/questcraft) for the best experience.
- **questcraft.net is not maintained or owned by anyone on the QuestCraft team**; they could put malware on it anytime. Please do not download anything from or visit questcraft.net. **Our new website is located here at [QuestCraft](https://questcraft.org/)**. 
- Pico (and ONLY Pico) support is planned and will begin development after 4.0. Until then, kindly use **[Vivecraft PCVR](https://www.vivecraft.org/)**.
- When installing mods that are not from Mod Manager on your Quest, you may face issues, ranging from unexpected behavior to crashes! If you experience any, please **[file an issue](https://github.com/QuestCraftPlusPlus/QuestCraft/issues/new/choose)**!
- Shaders can be used, but expect very low performance!

## Controls

![There's supposed to be controls here](/Control.png)

These controls are subject to change.
