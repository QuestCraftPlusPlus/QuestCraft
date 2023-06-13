# Welcome to the QuestCraft GitHub!
### **[Support us on Patreon!](https://patreon.com/QuestCraftXR)**

![sponsor image](/partnerimage.png)
# QuestCraft
![QC](/QCSimple3.jpg)

QuestCraft, utilizing Vivecraft and Pojlib, is a standalone port of Minecraft: Java Edition to Oculus Quest Headsets. With a team of four main developers and 8 third party developers, over the past year we have not only gotten the bestselling game, Minecraft: Java Edition running on Android, but we have also worked with third-party developers to bring it into Virtual Reality on the Oculus Quest line of standalone HMDs.

# Features
- ### **Roomscale Minecraft VR!** 
- ### **Quest 2 Native!\***
- ### **Full Multiplayer!**                                                                    
- ### **Immersive Controls through Vivecraft!**                                                                                                   
- ### **Supports 1.18.2, 1.19.2-4, and 1.20.0!!**                                                                                                                                 
- ### **Includes a Unity and Pojlib-built *launcher* that allows you to start QuestCraft, switch between versions and renderers, automatically updates installed mods and other MC components in milliseconds, and use Mod Manager, a tool to download and install supported mods right from your Quest!**
**\*Quest 1 Support is no longer available. You can't use any version of QuestCraft on it.**

# Installation Instructions

**NOTE: In order to install QuestCraft, you must have an internet connection in order for the initial setup to succeed. Furthermore, you MUST own a legal, valid copy of Minecraft: Java Edition to play!**

**Make sure your Quest 2 is on v51 or later before installing!**

First off, you most likely want to install QuestCraft. Please go to the release page for **[QuestCraft](https://github.com/QuestCraftPlusPlus/QuestCraft/releases/latest)** and download the APK to your computer or Android device.

Secondly, you need to install the QuestCraft APK to your VR Headset using **[SideQuest](https://sidequestvr.com/setup-howto)** and follow the necessary steps to connect your Quest. Drag and drop the APK, and wait for it to install.

Next, open the QuestCraft launcher (through Unknown Sources) on your headset. Be sure to grant it all requested permissions. Once complete, follow the on-screen prompts to enter your Minecraft login details, then press play and wait for all of the files to download (aproxx. 10 minutes).  (You will need to do this for each specific version in order to play that version!)

**NOTE: You may encounter crashes when installing, ESPECIALLY on v53 and later. This is because Meta can't fix memory leaks, for some reason. Don't fret, just launch the app again, press play again, and the download will continue where it left of before the crash.**

And boom! You have successfully installed QuestCraft on your VR headset! To play, simply press the **Play** button and wait for it to load, it might take a while depending on the headset's age.

## Supported Renderers (Take note when installing mods!)

- ### Zink
**[Zink](https://docs.mesa3d.org/drivers/zink.html)**, works with a lot of mods, at the cost of performance. (which is fixed with the performance mods below)
- ### Vulkan
**[Vulkan](https://www.vulkan.org/)**, while being very fast, doesn't work with a lot of mods. 

## Included Mods 

**Did you experience a mod-related crash when loading MC? You can do 1 of these solutions to find the cause and fix it!**

**Easy Way**                                                                                                                                                                                                                                                                                  
Join the QuestCraft Discord Server at **discord.gg/questcraft** and go to #bot-commands. Type /logs and upload your log file (which can be retrieved from Android/data/com.qcxr.qcxr using a file viewer e.g Windows Explorer). The QuestCraft Bot, Crafty, will give you feedback and help you fix any issues.

**Manual Way**                                                                                                                                                                                                                                                                                      
To find out what caused the crash, open the latestlog.txt file. You can find it in Android/data/com.qcxr.qcxr with a file viewer. Go to the bottom of the file and look for a Fabric error message. This message will tell you which mods caused the crash. Once you know what caused the problem, you can fix it.

If neither of these solutions helped you, please go to the support channel of the QuestCraft Discord (discord.gg/questcraft). 

### Non-Performance Mods:

- **[Cloth Config](https://modrinth.com/mod/cloth-config)** (Libary for config screens, e.g. Video Settings)

- **[Fabric API](https://modrinth.com/mod/fabric-api)** (API for Fabric. Essential to basically get any mod running.)

- **[Mod Menu](https://modrinth.com/mod/modmenu)** (Menu that lists the currently installed mods and if **[YACL](https://modrinth.com/mod/yacl)** is installed, can configure them!)

- **[Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat)** (Adds proximity voice chat)

- **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)** (Port of Vivecraft to run on Fabric)

### Performance Mods: (for Zink)

- **[Better Biome Blend](https://modrinth.com/mod/better-biome-blend)** (Fixes and adds features to the Biome Blend setting, improving biome looks and improving performance)                                                                                                                    

- **[Concurrent Chunk Management Engine (C2ME)](https://modrinth.com/mod/c2me-fabric)** (Improves chunk loading)
                                                                                                                                                  
- **[Entity Culling](https://modrinth.com/mod/entityculling)** (Renders only visible blocks and entities, improving overall performance)

- **[Ferrite Core](https://modrinth.com/mod/ferrite-core)** (Decreases memory usage by doing technical stuff)

- **[Fastload](https://modrinth.com/mod/fastload)** (Improves world load and prevents potential crashes)

- **[Immediately Fast](https://modrinth.com/mod/immediatelyfast)** (Optimizes lots of things, making rendering more GPU efficient)

- **[Krypton](https://modrinth.com/mod/krypton)** (Slightly reduces memory usage on servers, decreases server CPU usage and server ticks)

- **[LazyDFU](https://modrinth.com/mod/lazydfu)** (Improves game boot time)

- **[Lithium](https://modrinth.com/mod/lithium)** (General purpose performance mod)

- **[More Culling](https://modrinth.com/mod/moreculling)** (Culling mod to improve performance) 

- **[Noxesium](https://modrinth.com/mod/noxesium)** (Adds features to fix bugs and performance)

- **[Smooth Boot](https://modrinth.com/mod/smoothboot-fabric)** (Makes Minecraft loading smoother)

- **[Sodium](https://modrinth.com/mod/sodium)** (Improves FPS and fixes graphical issues)

- **[Starlight](https://modrinth.com/mod/starlight)** (Improves the lighting engine)

## Some Recommended Settings and Tips (For Zink)
1. In the options menu, go to VR Settings/Stereo Rendering and set the resolution (NOT CAMERA RES) to 80%. This will decrease the general quality, but will give an extra performance boost.
2. The game's render distance is best at 4-6, but you *may* encounter lag spikes when using it. 9 and above is not recommended.
3. Oceans contain LOTS of kelp that decrease framerate. Don't mine any of it all at once, as your game may CRASH if lots of entities (in this case, kelp waiting to be picked up) exist at once.
4. **[Skyblock](https://minecraft.fandom.com/wiki/Tutorials/Skyblock)** and **[Oneblock](https://www.curseforge.com/minecraft/worlds/oneblock)** worlds perform the best, as they require less hardware usage.

# Recommended servers
1. **MinecraftVR** - `MinecraftVR.mysrv.us`
2. **TSC** - `mc.playtsc.com`

# Notes
- We do not exist on TikTok. No one from the dev team makes TikTok videos.
- QuestCraft (QCXR) is developed and maintained by the QCXR team, we also contribute upstream to the open source tools that we used to make this a reality, make sure to check out **[MCXR](https://github.com/mcxr-org/MCXR)**, the previous VR mod, now replaced with **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)**, **[PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)** (for Pojlib!), and **[VulkanMod](https://github.com/xCollateral/VulkanMod)** for Vulkan support!
- The QCXR forks we use are: **[Pojlib](https://github.com/questcraftplusplus/pojlib)**, **[VivecraftMod](https://github.com/questcraftplusplus/vivecraftmod)**, and **[VulkanMod](https://github.com/QuestCraftPlusPlus/VulkanMod).** 
- All support questions should be asked inside of the **[QuestCraft Discord](discord.gg/questcraft)** for the best experience.
- **questcraft.net is not maintained or owned by anyone on the QuestCraft team**; they could put malware on it anytime. Please do not download anything from or visit questcraft.net. **Our new website is located here at [QuestCraft](https://questcraft.org/)**. 
- Pico (and ONLY Pico) support is planned and is currently in development. Until then, kindly use **[Vivecraft PCVR](https://www.vivecraft.org/)**.
- When installing mods that are not from Mod Manager on your Quest, you may face issues, ranging from unexpected behavior to crashes! If you experience any, please **[file an issue](https://github.com/QuestCraftPlusPlus/QuestCraft/issues/new/choose)** or go to the **[Discord server](https://discord.gg/questcraft/)**!
- Shaders can be used, but expect slideshow frames!

## Controls

![There's supposed to be controls here](/Control.png)

These controls are subject to change.
