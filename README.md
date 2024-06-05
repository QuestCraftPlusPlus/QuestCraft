# Welcome to the QuestCraft GitHub!
### **[Support us on Patreon!](https://patreon.com/QuestCraftXR)**

# QuestCraft
![QC](/QCSimple3.jpg)

QuestCraft, utilizing Vivecraft and Pojlib, is a standalone port of Minecraft: Java Edition to Oculus Quest Headsets. With a team of four main developers and 8 third-party developers, over the past year, we have not only gotten the bestselling game, Minecraft: Java Edition running on Android, but we have also worked with third-party developers to bring it into Virtual Reality on the Oculus Quest line of standalone HMDs.

# Features
- ### **Roomscale Minecraft VR!** 
- ### **Quest 2 and 3 Native!\***
- ### **Full Multiplayer!**                                                                    
- ### **Immersive Controls through Vivecraft!**                                                                                                   
- ### **Supports 1.18.2 (most stable version), 1.19.2 and 4, and 1.20.1 - 1.20.4!****                                                                                                                                 
- ### **Includes a launcher that allows you to start QuestCraft, switch between versions, automatically update installed mods and other MC components in seconds, and use Mod Manager, a tool to download and install supported mods, modpacks and resourcepacks right from your Quest!**                                                                                                                                                                                

# Installation Instructions

**NOTE: To install QuestCraft, you must have an internet connection for the initial setup to succeed. Furthermore, you MUST own a legal, valid copy of Minecraft: Java Edition to play!**

First off, you most likely want to install QuestCraft. Please go to the release page for **[QuestCraft](https://github.com/QuestCraftPlusPlus/QuestCraft/releases/latest)** and download the APK to your computer or Android device.

Secondly, you must install the QuestCraft APK to your VR Headset using **[SideQuest](https://sidequestvr.com/setup-howto)** and follow the necessary steps to connect your Quest. Drag and drop the APK, and wait for it to install.

Next, open your headset's QuestCraft launcher (through Unknown Sources). Be sure to grant all requested permissions. Once you're done, you'll follow the on-screen prompts to enter your Minecraft login details, then press play and wait for all of the files to download (aproxx. 10 minutes).  (You must do this for each specific version to play that version!)

**NOTE: You may encounter crashes when downloading your selected MC version, ESPECIALLY on v53 and later. This is because Meta can't fix memory leaks, for some reason. Don't fret; launch the app again, press play again, and the download will continue where it left of before the crash. If it continues, please keep trying. If, after 4 attempts, you still are not loaded in, please visit the support channel of the [QuestCraft Discord](https://discord.gg/questcraft)**

And boom! You have successfully installed QuestCraft on your VR headset! To play, press the **Play** button and wait for it to load; depending on the headset, it might take a while.

## Supported Renderer

**Regal**
We use a renderer named Regal, an almost perfect renderer for Minecraft. You may find issues, you can see some renderer specific issues on our Discord, and in the known-issues-5•0

## Included Mods 

**Did you experience a mod-related crash when loading MC? You can do 1 of these solutions to find the cause and fix it!**

**Easy Way**                                                                                                                                                                                                                                                                                  
Join the QuestCraft [Discord Server](https://discord.gg/questcraft) and go to #bot-commands. Grab your log by going to Need Help? button, going to the link it supplies, downloading the log, then uploading it to Crafty by doing /logs.

**Manual Way**                                                                                                                                                                                                                                                                                      
To find out what caused the crash, you can open the latestlog.txt file. You can find it in Android/data/com.qcxr.qcxr with a file viewer. You can go to the bottom of the file and look for a Fabric error message. This message will tell you which mods caused the crash. Once you know what caused the problem, you can fix it.

If you need help with these solutions, please go to the support channel of the QuestCraft [Discord](https://discord.gg/questcraft). 

**All mods that are preinstalled can be toggled off and on with the exeption of Vivecraft and Fabric API in a new instance.

## Some Recommended Settings and Tips
1. In the options menu, go to VR Settings/Stereo Rendering and set the resolution (NOT CAMERA RES) to 80%. This will decrease the general quality but will give an extra performance boost.
2. The game's render distance is best at 4-6, but you *may* encounter lag spikes when using it. 9 and above is not recommended.
3. Oceans contain LOTS of kelp that decreases framerate. Don't mine any of it all at once, as your game may CRASH if many entities (in this case, kelp waiting to be picked up) exist simultaneously.
4. **[Skyblock](https://minecraft.wiki/w/Tutorials/Skyblock)** and **[Oneblock](https://www.curseforge.com/minecraft/worlds/oneblock)** worlds perform the best, as they require less hardware usage.

# Notes
- We do not exist on TikTok. No one from the dev team makes TikTok videos.
- QuestCraft (QCXR) is developed and maintained by the QCXR team; we also contribute upstream to the open-source tools that we used to make this a reality; make sure to check out **[MCXR](https://github.com/mcxr-org/MCXR)**, the previous VR mod, now replaced with **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)**, **[PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)** (for Pojlib!), [Zink](https://docs.mesa3d.org/drivers/zink.html) for our current renderer and **[VulkanMod](https://github.com/xCollateral/VulkanMod)**!
- All support questions should be asked inside of the **[QuestCraft Discord](discord.gg/questcraft)** for the best experience.
- **questcraft.net is not maintained or owned by anyone on the QuestCraft team**; they could put malware on it anytime. Please do not download anything from or visit questcraft.net. **Our new website is here at [QuestCraft](https://questcraft.org/)**. 
- Pico (and ONLY Pico) support is planned and is currently in development. Until then, kindly use **[Vivecraft PCVR](https://www.vivecraft.org/)**.
- When installing mods that are not from Mod Manager on your Quest, you may face issues, ranging from unexpected behaviour to crashes! If you experience any, please **[file an issue](https://github.com/QuestCraftPlusPlus/QuestCraft/issues/new/choose)** or go to the **[Discord server](https://discord.gg/questcraft/)**!

# This project is open source...
...but you don't find source code in this repo. You can find the source code for each subproject in their respective repos:
- **[Pojlib (Launcher library)](https://github.com/questcraftplusplus/pojlib)**
- **[VivecraftMod (Minecraft VR Mod)](https://github.com/questcraftplusplus/vivecraftmod)**
- **[Unity Env (Launcher Wrapper)](https://github.com/QuestCraftPlusPlus/QCXR-XR-Wrapper).** 

## Controls

![There's supposed to be controls here](/Control.png)
