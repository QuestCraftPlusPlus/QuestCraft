# Welcome to the QuestCraft GitHub!
### **[Support us on Patreon!](https://patreon.com/QuestCraftXR)**

# QuestCraft
![QC](/QCSimple3.jpg)

QuestCraft, utilizing Vivecraft and Pojlib, is a standalone port of Minecraft: Java Edition to many VR Headsets. With a team of three main developers and 11 third-party developers, over the past year, we have not only gotten the bestselling game, Minecraft: Java Edition running on Android, but we have also worked with third-party developers to bring it into Virtual Reality on the Meta Quest and other standalone HMDs.

# Features
- **Roomscale Minecraft VR!** 
- **Quest 2 and 3 Native!\**
- **Pico Neo 3, 4, 4u Support along with other headsets!\**
- **Full Multiplayer!**                                                                    
- **Immersive Controls through Vivecraft!**                                                                                                   
- **Supports 1.19.2 + 4, 1.20.1, 4 + 6, 1.21.1 + 4*                                                                                                                                 
- **Includes a launcher that allows you to start QuestCraft, switch between versions, automatically update installed mods and other MC components in seconds, and use Mod Manager, a tool to download and install mods, modpacks and resourcepacks right from your Quest!**                                                                                                                                                                                

# Installation Instructions

**NOTE: To install QuestCraft, you must have an internet connection for the initial setup to succeed. Furthermore, you MUST own a legal, valid copy of Minecraft: Java Edition to play!**

First off, you most likely want to install QuestCraft. Please go to the release page for **[QuestCraft](https://github.com/QuestCraftPlusPlus/QuestCraft/releases/latest)** and download the APK to your computer or Android device.

Secondly, you must install the QuestCraft APK to your VR Headset using **[SideQuest](https://sidequestvr.com/setup-howto)** and follow the necessary steps to connect your preferred VR headset. Drag and drop the APK, and wait for it to install.

Next, open your headset's QuestCraft launcher (maybe in Unknown Sources.) Make sure to grant requested permissions. Once you're done, you'll follow the on-screen prompts to enter your Minecraft login details, then press play and wait for all the files to download. (approx. 10 minutes, dependent on internet speed, you must do this for each specific version to play that version!) While it downloads, do not take off your headset as it may cause files to stop transferring.

And boom! You have successfully installed QuestCraft on your VR headset! To play, press the **Play** button and wait for it to load; depending on the headset, it might take a while, but our nifty log viewer will show you progress, (1-4 minutes max with default mods.)

## Supported Renderer

**Light Thin Wrapper**

We use a renderer made in joint collaboration with [PojavLauncherTeam](https://github.com/PojavLauncherTeam), which allows for fast, compatible, and best way to play Java Edition on Mobile Devices.

## Included Mods 

QuestCraft includes many mods that replace modpacks for optimization. [You can check it out here!](https://github.com/QuestCraftPlusPlus/Pojlib/blob/QuestCraft/mods.json)

## Mod Issues

**Did you experience a mod-related crash when loading MC? You can do 1 of these solutions to find the cause and fix it!**

### Easy Way

Join the QuestCraft [Discord Server](https://discord.gg/questcraft) and go to #bot-commands. Grab your log by going to Need Help? button, going to the link it supplies, downloading the log, then uploading it to Crafty by doing /logs.

### Manual Way

To find out what caused the crash, you can open the latestlog.txt file. You can find it in Android/data/com.qcxr.qcxr with a file viewer. You can go to the bottom of the file and look for a Fabric error message. This message will tell you which mods caused the crash. Once you know what caused the problem, you can fix it. You can now also get logs by pressing the "Need Help?" button, where it will give you a mclo.gs link.

If you need help with these solutions, please go to the support channel of the QuestCraft [Discord](https://discord.gg/questcraft). 

*All mods that are preinstalled can be toggled off and on with the execption of Vivecraft and Fabric API in a new instance.*

## Some Recommended Settings and Tips
1. In the options menu, go to VR Settings/Stereo Rendering and set the resolution (NOT CAMERA RES) to 80%. This will decrease the general quality but will give an extra performance boost.
2. The game's render distance is best at 4-6, but you *may* encounter lag spikes when using it. 9 and above is not recommended.
3. **[Skyblock](https://minecraft.wiki/w/Tutorials/Skyblock)** and **[Oneblock](https://www.curseforge.com/minecraft/worlds/oneblock)** worlds perform the best, as they require less hardware usage.

# Notes
- We do not exist on TikTok. No one from the dev team makes TikTok videos.
- QuestCraft (QCXR) is developed and maintained by the QCXR team; we also contribute upstream to the open-source tools that we used to make this a reality; make sure to check out **[MCXR](https://github.com/mcxr-org/MCXR)**, the previous VR mod, now replaced with **[VivecraftMod](https://github.com/ferriarnus/VivecraftMod)**, **[PojavLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)** (for [Pojlib](https://github.com/QuestCraftPlusPlus/Pojlib/tree/QuestCraft)!)
- All support questions should be asked inside the **[QuestCraft Discord](discord.gg/questcraft)** for the best experience.
- **questcraft.net is not maintained or owned by anyone on the QuestCraft team**; they could put malware on it anytime. Please do not download anything from or visit questcraft.net. **Our new website is here at [QuestCraft](https://questcraft.org/)**. 
- When installing mods that are not from Mod Manager on your Quest, you may face issues, ranging from unexpected behaviour to crashes! If you experience any, go to the **[Discord server](https://discord.gg/questcraft/), or if there isn't already an issue,  [make a bug report](https://github.com/QuestCraftPlusPlus/QuestCraft/issues)**

# This project is open source...
...but you don't find source code in this repo. You can find the source code for each subproject in their respective repos:
- **[Pojlib (Launcher library)](https://github.com/questcraftplusplus/pojlib)**
- **[Unity Environment (Launcher Wrapper)](https://github.com/QuestCraftPlusPlus/QCXR-XR-Wrapper).** 

## Controls

![Diagram of the table below](/QC_Controls.png)

<details>
  <summary>Show controls table</summary>
  <table>
    <thead>
      <tr>
        <th scope="col">Button</th>
        <th scope="col">Function</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row" align="left">Left thumbstick</th>
        <td>Move (press to sprint)</td>
      </tr>
      <tr>
        <th scope="row" align="left">Right thumbstick</th>
        <td>Left/right turn (press to crouch)</td>
      </tr>
      <tr>
        <th scope="row" align="left">Left trigger</th>
        <td>Place/use</td>
      </tr>
      <tr>
        <th scope="row" align="left">Right trigger</th>
        <td>Break/grab</td>
      </tr>
      <tr>
        <th scope="row" align="left">Left grab</th>
        <td>Hotbar left</td>
      </tr>
      <tr>
        <th scope="row" align="left">Right grab</th>
        <td>Hotbar right</td>
      </tr>
      <tr>
        <th scope="row" align="left">X</th>
        <td>Inventory</td>
      </tr>
      <tr>
        <th scope="row" align="left">Y</th>
        <td>Teleport</td>
      </tr>
      <tr>
        <th scope="row" align="left">A</th>
        <td>Radial menu</td>
      </tr>
      <tr>
        <th scope="row" align="left">B</th>
        <td>Jump</td>
      </tr>
      <tr>
        <th scope="row" align="left">Menu button</th>
        <td>Pause/menu</td>
      </tr>
      <tr>
        <th scope="row" align="left">Meta button</th>
        <td>Meta home</td>
      </tr>
    </tbody>
  </table>
</details>
