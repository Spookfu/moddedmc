# Introduction to Minecraft Modding (Player wise)
Hey there! Welcome to the MC Modding Introduction page, which aims to help you better understand or learn how to play and manage mods in Minecraft. 


# **PART 1 - Setting Up**
Before doing **ANYTHING**, you must keep a few things in mind:

## The Basics
### I. Performance & Stability
Minecraft is known to be rather resource-intensive and unoptimized. Adding mods makes the game harder to run, and sometimes on low-end computers, outright unplayable. You may have heard of mods such as Optifine or Sodium/Lithium, which are both mods made to help improve the performance of the game. 

You are **RECOMMENDED** while playing Modded to have **AT LEAST** 4-8GBs of RAM allocated to Minecraft for it to run well. Even if your computer is quite beefy, performance issues will still arise. For both low and high-end computer players, we recommend you refer to this  [Github Page](https://github.com/TheUsefulLists/UsefulMods) for further information/mods to help optimize your game performance if you so need. 

### II. Mod Management
Updating and managing mods is quite a hassle. So to lessen the headaches, here are a few things you can do.
1. Use a Launcher that is not the Vanilla Minecraft Launcher, like [MultiMC](https://multimc.org/), [CurseForge](https://download.curseforge.com/), or [Prism Launcher](https://prismlauncher.org/).
2. Always check if you are using the right mod with the correct: mod loader, mod version, and mod Minecraft version


<details>
<summary>Example</summary>
<br>
  
> [!NOTE]
> Clicking on a file in the Files tab on CurseForge, and clicking a file on the Versions tab on Modrinth, will show you something similar to the images below respectively
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/a96a63c2-8b9b-411e-9be9-697fdd2a5056)
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/2a2b454c-9466-4422-abe3-86cd718c88bb)

</details>


4. Check if the mods have any dependencies that they require. This is usually found in its description, Relations tab, or files tab.


<details>
<summary>Example</summary>
<br>
  
> [!NOTE]
> Mod Dependencies list on a CurseForge and Modrinth mod page respectively. **CurseForge's** dependencies page can be seen in the Relations Tab, and **Modrinth's** dependencies can be seen in a mods file page.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/48100494-f874-4cf5-ac36-9d1058419ad4)
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/b3228188-bceb-40d6-aff8-bdeba7e3e3fc)

</details>


5. Use [Modrinth](https://modrinth.com/) or [Curseforge](https://beta.curseforge.com/minecraft/search?page=1&class=mc-mods&sortType=2&pageSize=20) to download mods from. Other sites are sketchy, not easy to use, or aren’t reliable or popular.
> [!WARNING]
> Please be vigilant when downloading mods, as they may include viruses and the such that the moderators of the websites may not have catched

6. Modders have frequently either stayed on a version indefinitely or only updated to specific versions. These version include as of 8/5/23: 1.7.10, 1.8.9, 1.12.2, 1.16.5, 1.18.2, 1.19.2 and the current latest version 1.20.1. 


## Setting Up Mod Loaders
Now that we have the basics out of the way let's stary Modding! To be able to use mods in minecraft, we'll be using Mod Loaders. There are currently two main Mod Loaders, them being [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), and [Fabric](https://fabricmc.net/). Let's first set up a basic mod profile.

> [!NOTE]
> The other mod loaders include [Quilt](https://quiltmc.org/en/), [NeoForge](https://neoforged.net/), [Rift](https://www.curseforge.com/minecraft/mc-mods/rift), [LiteLoader](http://www.liteloader.com/), and [Risugami's Modloader ](https://ftb.fandom.com/wiki/Risugami's_Modloader) (DISCONTINUED). We will not be going over these mod loaders as most of them are inactive, discontinued, in heavy development, or not very popular.

### Let's first set up a basic mod profile.

<details>
<summary> FORGE </summary>
<br>

Select the Client you are using.

 <details>
 <summary> Vanilla </summary>
 <br>
   
 **Vanilla**
 1. Go to the Minecraft Launcher, and launch your preferred version. After it has loaded into the Title Screen, exit out of the game.
 1. Go to the [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/) Website
 2. Click on your perferred version and Download the Recommended INSTALLER (If you wish to, you can choose the Latest Installer). Upon completion open the downloaded file. 
    
  ![image](https://github.com/Spookfu/moddedmc/assets/75686139/34322acb-3c17-41ef-b495-643728718a02)
  ![image](https://github.com/Spookfu/moddedmc/assets/75686139/e3bfd223-a390-47d4-9173-18e2b13d3ee2)
  
 3. You should now see this! Click on `OK` and wait for it to install. (The Black mark is your profile name.) Wait for Forge to be installed.
    
    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/d5f4db67-f617-4247-b547-4e8a4e1f627d)

    You should see this after the download has been completed.
    
    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/1062f50b-d06a-4a1e-ad55-935541690146)

 5. Open the Minecraft Launcher and you should see a forge profile in your Installations List.
    
    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/3917a696-0635-4b07-9cab-eff39cfbc8cf)

    <details>
    <summary>If not, click here! </summary>
    <br>

    1. Click on the Installations Tab

    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/2060fce6-c3ca-4ade-bb86-c49780e5fdb9)
    

    2. Check the Box called `MODDED` on the top, than click on `New Installation`.
     
    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/5c5f817c-6692-4c3f-8d56-05e9d1644ff5)

    3. Click on Versions, and scroll down until you see the desired Version, than click create.
  

    ![image](https://github.com/Spookfu/moddedmc/assets/75686139/a8491cef-477f-4496-b657-7f7e66aab522)
    
    You're done!

    </details>
</details>


<details>
<summary> MultiMC / Prism Launcher </summary>
<br>

**MultiMC / Prism Launcher**
1. Open the Launcher and click `Add Instance`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/0c2afcc7-fee0-42db-b06c-d67c9c8ebf45)

2. Choose your preferred version, and click on `Forge` than press `OK`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/e1c932b2-573c-4620-a709-cbda175aa1fc)

You should see this now!

![image](https://github.com/Spookfu/moddedmc/assets/75686139/fa75ab44-7f1c-4119-9aeb-39195fa925bf)


You're done!

</details>

<details>
<summary> CurseForge </summary>
<br>

1. Open CurseForge, and click on `Create Custom Profile`
   
![image](https://github.com/Spookfu/moddedmc/assets/75686139/3b316a7f-75dd-4a0a-8b13-c6430fd01122)

2. Enter a Name for your profile, choose your preferred version, and click on Forge. Once you're satisfied, click `Create`

   ![image](https://github.com/Spookfu/moddedmc/assets/75686139/3962e942-de17-4834-bd75-e0096f59a342)

   You should see this when it finishes downloading.

   ![image](https://github.com/Spookfu/moddedmc/assets/75686139/02a83e66-9686-40dc-a30e-db7966612374)


You're good to go!

</details>

Now that you've setup a simple mod loader, it's time to add mods!
</details>

#

<details>
<summary> FABRIC </summary>
<br>

<details>
<summary> Vanilla </summary>
<br>
  
**Vanilla**
1. Go to the Minecraft Launcher, and launch your preferred version. After it has loaded into the Title Screen, exit out of the game.
2. Go to the [Fabric](https://fabricmc.net/) Website
3. Click on `download here`
   
![image](https://github.com/Spookfu/moddedmc/assets/75686139/94fc2ba2-5390-4897-aeb8-f85478b18d7f)

4. Click on `Download for Windows` (or `Download universal jar` if you're not using Windows),and open the downloaded file.
> [!NOTE]
> Fabric has their own [Installation guide](https://fabricmc.net/wiki/install) that you can look through instead of here.

![image](https://github.com/Spookfu/moddedmc/assets/75686139/8fee7f0d-4ccc-4dea-9247-96cb2e8b2003)

5. You should see this now! Choose your perferred version (Check the Show Snapshots buttom for Snapshot versions), and check `Create Profile`, if it isn't already, and press `Install`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/85c9883e-5eec-4865-a95a-bb0b74705a05)

You should see this after the download has been completed.

![image](https://github.com/Spookfu/moddedmc/assets/75686139/e25d039f-365a-4c33-b0be-527345b67bfe)

6. Open the Minecraft Launcher and you should see a fabric profile in your Installations List.
![image](https://github.com/Spookfu/moddedmc/assets/75686139/b97c938f-015a-4e05-a4b7-851dd876c8e4)

</details>

<details>
<summary> MultiMC / Prism Launcher </summary>
<br>

**MultiMC / Prism Launcher**
1. Open the Launcher and click `Add Instance`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/0c2afcc7-fee0-42db-b06c-d67c9c8ebf45)

2. Choose your preferred version, and click on `Fabric` than press `OK`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/6196df41-c5a3-418f-890c-4a3a3bd8d20d)


You should see this now!

![image](https://github.com/Spookfu/moddedmc/assets/75686139/4ddeabb6-a739-4b31-aec5-71be6ee87ec6)


You're done!

</details>

<details>
<summary> CurseForge </summary>
<br>

1. Open CurseForge, and click on `Create Custom Profile`
   
![image](https://github.com/Spookfu/moddedmc/assets/75686139/3b316a7f-75dd-4a0a-8b13-c6430fd01122)

2. Enter a Name for your profile, choose your preferred version, and click on Fabric. Once you're satisfied, click `Create`

   ![image](https://github.com/Spookfu/moddedmc/assets/75686139/73400613-a09a-4f9e-a8f7-592ade0feb57)

   You should see this when it finishes downloading.

   ![image](https://github.com/Spookfu/moddedmc/assets/75686139/ec721cfa-2f12-477d-851e-e3d658133f0d)


You're good to go!

</details>

Now that you've setup a simple mod loader, it's time to add mods!
</details>


# PART 3 - Issues
## Debugging Issues
Crashes and other issues are bound to happen. The easiest way to debug issues is by looking at your Logs. Here’s how to view them:

**Using Vanilla Launcher:**
1. Press `Windows + R`
2. Type in `%appdata%`
> [!NOTE]
> This is what you should see right now.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/c82b00bd-bac0-4164-b31f-246842247aec)
   
4. Go into the folder called `.minecraft`
5. Go into the folder called `logs`
6. You can either look through past logs or the latest instance log in `latest.log`



    



