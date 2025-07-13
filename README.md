#### SkyGround-Chronicles

![](https://raw.githubusercontent.com/ItzIvy05/SkyGround-Chronicles/refs/heads/main/Resources/Main.png)

<p align="center">
  <a href="https://www.nexusmods.com/skyrimspecialedition/mods/147012">Nexus</a> |
  <a href="https://loadorderlibrary.com/lists/skyground-chronicles-2">Load Order﻿﻿</a> |
  <a href="https://discord.gg/FB62v6whbh">Discord</a>
</p>

#### Introduction

SkyGround Chronicles is a Wabbajack modlist built around Requiem, Legacy of the Dragonborn, and BFCO with its full Stance system, all while pushing visuals to the limit. It supports both ENB and Community Shaders, delivering a visually stunning and deeply immersive RPG experience.

If you're curious about the specific mods in the list, the full modlist can be viewed [here](https://loadorderlibrary.com/lists/skyground-chronicles-2).

### System Requirements

**DISCLAIMERS:**
- SkyGround Chronicles only supports English Steam versions of full Skyrim AE. GOG and other languages are not supported.
- HDD and external SSD installs are absolutely not supported.
- Any remote PC / desktop services or apps are not supported. (Including Steam Link)
- Only Windows 10/11 operating systems are supported. Windows LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK.**
- At least 8GB of GPU VRAM minimum is recommended for the list (1080p), otherwise you'll experience frequent stutters in exteriors. Higher resolutions may require even more.

![](https://raw.githubusercontent.com/ItzIvy05/SkyGround-Chronicles/refs/heads/main/Resources/SYS-RQ.png)


## Installation

**⚠ WARNINGS ⚠:**
- **You must update Skyrim Special Edition to the latest version on Steam to install this list. DO NOT DOWNGRADE YOUR GAME TO INSTALL THIS LIST!**

### Pre-Installation

#### General Utilities
Preventing Major Meyhem

Before installing SkyGround Chronicles, please complete the following steps:<br/>
[**.NET 8.0 SDK**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.404-windows-x64-installer)
.NET is a free, cross-platform, open-source developer platform for building many different types of applications. This is required for Synthesis and Scrambled Bugs to function properly.<br/>
[.NET 8.0 SDK (v8.0.404) - Windows x64 Installer](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.404-windows-x64-installer)<br/>

**Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022**
The Visual C++ Redistributable installs Microsoft C and C++ (MSVC) runtime libraries. These libraries are required by many applications built by using Microsoft C and C++ tools. This is required for Mod Organizer 2 and LOOT to function properly. Download both of them from:<br/>
[Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022 - x86](https://aka.ms/vs/17/release/vc_redist.x86.exe)<br/>
[Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022 - x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)<br/>

#### Official Bethesda Content
Complete With Official Bethesda Bugs<br/>

**Steam Overlay**<br/>
The Steam Overlay is known to cause issues while playing Skyrim Special Edition, and you are advised to disable it; to do this perform the following:<br/>

    Load Steam.
    In the toolbar at the top of the window, click Steam.
    In the dropdown menu, click Settings.
    Then, in the pop-up box, select the In-Game menu item.
    Uncheck Enable the Steam overlay while in-game.

Alternatively, if you would just like to disable the Overlay for Skyrim Special Edition, you may:<br/>

    Load Steam.
    Click LIBRARY.
    In your games list, look for The Elder Scrolls V: Skyrim Special Edition and right-click on it.
    In the dropdown menu, click Properties.
    Then, in the pop-up box, uncheck Enable the Steam Overlay while in-game.

Important: Do not install Skyrim in `C:\Program Files` or `C:\Program Files (x86)` — this can cause permission issues.
If it is already installed there, reinstall it to a different location to something like `C:\Games` works if you only have one drive, but if you have multiple, something like `D:\Modlist\` is preferred.<br/>
You can also use LostDragonist’s Steam Library Setup Tool to easily move or create a new library.<br/>

#### Antiviruses
Bad Antivirus...e<br/>

Remove or disable any 3rd party antiviruses such as `Webroot` or `Bitdefender`. These programs can cause issues with your installation due to how MO2's Virtual File Staging works.<br/>
You’ll also need to add the Wabbajack list folder to your antivirus exclusion list. Otherwise, the game may have trouble loading scripts, which can lead to crashes.<br/>
<img src="https://i.imgur.com/raiU13r.png" />

#### Few Other Small Tips
1. Set your Skyrim language to English: Right click on your Skyrim in Steam > Click `Properties` > Click the drop down box next to `Language` > Set the language to English<br/>
2. (Soft Requirement) A Nexus Premium account is recommended. Without Premium, you will need to manually click the `Slow Download` button for each mod.

#### Pagefile and Crash Prevention

Larger Skyrim modlists require a significant amount of memory and running out of memory **will** result in crashes and other potential issues. 

Due to SkyGround Chronicles's size and number of files required to be handled for the list, this step is **NOT** optional. **Regardless of how much RAM or VRAM you have, please do this step.**

 To set up your pagefile:

     1. Press **Win Key + R**
     2. Type *sysdm.cpl ,3* and hit **ENTER**
     3. Navigate to *Performance* and click the box "Settings..."
     3. Click the *Advanced* tab at the top
     4. Under *Virtual Memory* click the box "Change..."
     5. Uncheck *Automatically manage* if it is checked
     6. Select your disk drive, ideally your fastest solid state drive.
     7. Click the **Custom size:** button
     8. In the box next to **Initial Size (MB)** type `40960`
     9. In the box next to **Maximum Size (MB)** type `40960`
     10. Click the *Set* button
     11. Click *OK*
     12. Click *Apply*
     13. Click *OK*
     14. Restart your computer in order for your new pagefile to take effect.`

<img width="430" height="603" alt="7A2ZcYL" src="https://github.com/user-attachments/assets/f5fd7ee0-202c-4cce-ae3f-4d44da71e726" />

---

#### Setting Shader Cache Size (NVIDIA Graphics Cards Only)

 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following:

 1. Right-click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner.
 6. You may exit out of the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

---

![](https://i.imgur.com/y2T6I94.png)  
![](https://i.imgur.com/AH2BMyp.png)  

[MissileMann](https://www.nexusmods.com/skyrimspecialedition/users/51322576): I owe the majority of my mods to him. I asked him for help so often, he’s probably tired of me by now.

[ChickenMike](https://www.nexusmods.com/skyrimspecialedition/users/70500678): A true navmesh expert — Mike taught me nearly everything I know about working with navmeshes.

**Sharks:** My friendly (and slightly sassy) beta tester and build master.

[CozySienna](https://www.twitch.tv/cozysienna): Thanks to her, I found a really cozy Discord and a safe, welcoming space to work on my mod list. I also got to meet some truly awesome people. Thanks, Sienna!

[Biggie_Boss](https://www.youtube.com/@biggie_boss): Thank you for creating [LoreRim](https://www.nexusmods.com/skyrimspecialedition/mods/112590) and making Requiem mainstream. Thank you for making useful tutorials.

[MoogieVT](https://www.twitch.tv/moogievt): We shall protect her at all cost. Super fun chill streamer and good friend anyone can ask for.

[Gonzeh](https://next.nexusmods.com/profile/Gonzeh84): Super cool (and yeah, a little horny) mod author with a ridiculous amount of knowledge. Taught me so much about working with NIF files and encouraged me to learn navmeshing instead of relying on navcuts.

[Vektile](https://www.twitch.tv/vektile): Thanks to him, I had the chance to meet Missilemann, Chickenmike, and Jayserpa. He was the one who opened the door for someone like me who doesn’t enjoy using a mic by creating a no-mic text channel. He shared an incredible amount of knowledge, from the smallest details to the biggest concepts, without ever gatekeeping anything — and most of all, I’ve become skilled at analyzing crash logs. :P

[Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) and the Wabbajack Team for their amazing platform that allows me to create and host lists like these.

**Bethesda Game Studios** for Skyrim and the Creation Kit.

[ElminsterAU](https://www.patreon.com/ElminsterAU) and the xEdit team for SSEEdit.

[Waking Dreams](https://github.com/Oghma-Infinium/modlists) For README and installation. Thank you [aljoxo](https://next.nexusmods.com/profile/aljoxo/mods?gameId=1704) for helping me with Wabbajack.

[Noggog](https://www.nexusmods.com/skyrim/users/862590) for Mutagen and Synthesis.  

[perchik71](https://www.nexusmods.com/starfield/users/113904913) for Creation Kit Platform Extended for Skyrim.


This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
