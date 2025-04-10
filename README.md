# SkyGround-Chronicles

![](https://raw.githubusercontent.com/ItzIvy05/SkyGround-Chronicles/refs/heads/main/Resources/Main.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/147012">Nexus</a> |
  <a href="loadorderlibrary.com/lists/skyground-chronicles">Load Order﻿﻿</a>]
</p>
## Introduction

SkyGround Chronicles is a Wabbajack modlist built around Requiem, Legacy of the Dragonborn, and BFCO with its full Stance system, all while pushing visuals to the limit. It supports both ENB and Community Shaders, delivering a visually stunning and deeply immersive RPG experience.

If you're curious about the specific mods in the list, the full modlist can be viewed [here](loadorderlibrary.com/lists/skyground-chronicles).

### System Requirements

**DISCLAIMERS:**
- SkyGround Chronicles only supports English Steam versions of Skyrim SE. GOG and other languages are not supported.
- HDD and external SSD installs are absolutely not supported.
- Any remote PC / desktop services or apps are not supported. (Including Steam Link)
- Only Windows 10/11 operating systems are supported. Windows LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK.**
- At least 8GB of GPU VRAM minimum is recommended for the list (1080p), otherwise you'll experience frequent stutters in exteriors. Higher resolutions may require even more.

![](https://raw.githubusercontent.com/ItzIvy05/SkyGround-Chronicles/refs/heads/main/Resources/SYS-RQ.png)


## Installation

**⚠ WARNINGS ⚠:**
- **You must update Skyrim Special Edition to latest version on Steam to install this list. DO NOT DOWNGRADE YOUR GAME TO INSTALL THIS LIST!**

### Pre-Installation

#### Prerequisites
Prior to installing SkyGround Chronicles, please complete the following steps:

 1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v6 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.29-windows-x64-installer).
 2. Reinstall Skyrim into a location that is not Program Files. Locations such as `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
 3. Disable the Steam Overlay: Right click on Skyrim SE in Steam and click on `Properties` > Untick the `Enable Steam Overlay while in-game` option
 4. Set your Skyrim language to English: Right click on your Skyrim in Steam > Click `Properties` > Click the drop down box next to `Language` > Set the language to English
 5. Remove or disable any 3rd party antiviruses such as Webroot or Bitdefender. These programs can cause issues with your installation due to how MO2's Virtual File Staging works.
 6. (Soft Requirement) A Nexus Premium account is recommended. Without Premium, you will need to manually click the `Slow Download` button for each mod.

#### Pagefile and Crash Prevention

Larger Skyrim modlists require a significant amount of memory and running out of memory **will** result in crashes and other potential issues. 

Due to SkyGround Chronicles's size and number of files required to be handled for the list, this step is **NOT** optional. **Regardless of how much RAM or VRAM you have, please do this step.**

 To set up your pagefile:

 1. Press **Win Key + R**
 2. Type *sysdm.cpl ,3* and hit **ENTER**
 3. Navigate to *Performance* and click the box "Settings..."
 4. Click the *Advanced* tab at the top
 5. Under *Virtual Memory* click the box "Change..."
 6. Uncheck *Automatically manage* if it is checked
 7. Select your disk drive, ideally your fastest solid state drive.  
  
    > This **can't** be a HDD or an external SSD.
 
 8. Click the **Custom size:** button
 9. In the box next to **Initial Size (MB)** type `40960`
 10. In the box next to **Maximum Size (MB)** type `40960`
 11. Click the *Set* button
 12. Click *OK*
 13. Click *Apply*
 14. Click *OK*
 15. Restart your computer in order for your new pagefile to take effect.

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

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
