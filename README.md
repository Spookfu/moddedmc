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
> ![Modrinth File Page](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20at%2018-55-43%2023w33a%20Fabric%20API%200.87.1%201.20.2%20-%20Fabric%20API.png?raw=true)
> ![CurseForge File Page](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20at%2019-03-36%20CurseForge%20-%20the%20home%20for%20modding%20communities.png?raw=true)

</details>


4. Check if the mods have any dependencies that they require. This is usually found in its description, Relations tab, or files tab.


<details>
<summary>Example</summary>
<br>
  
> [!NOTE]
> Mod Dependencies list on a CurseForge and Modrinth mod page respectively. **CurseForge's** dependencies page can be seen in the Relations Tab, and **Modrinth's** dependencies can be seen in a mods file page.
> 
> ![Modrinth File Page](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20at%2019-18-54%201.19.2-440-fabric%20-%20Botania.png?raw=true)
> ![CurseForge Relations Tab](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20at%2019-18-01%20Related%20Dependencies%20-%20Botania%20-%20Mods%20-%20Projects%20-%20CurseForge.png?raw=true)
> Some mods may not have included their dependencies in the two locations shown above, but rather in the Mods Description

</details>


5. Use [Modrinth](https://modrinth.com/) or [Curseforge](https://beta.curseforge.com/minecraft/search?page=1&class=mc-mods&sortType=2&pageSize=20) to download mods from. Other sites are sketchy, not easy to use, or aren’t reliable or popular.
> [!WARNING]
> Please be vigilant when downloading mods, as they may include viruses and such that the moderators of the websites may not have caught.

6. Modders have frequently either stayed on a version indefinitely or only updated to specific versions. These version include as of 8/5/23: 1.7.10, 1.8.9, 1.12.2, 1.16.5, 1.18.2, 1.19.2 and the current latest version 1.20.1. 


## Setting Up Mod Loaders
Now that we have the basics out of the way let's start Modding! To be able to use mods in Minecraft, we'll be using Mod Loaders. There are currently two main Mod Loaders, them being [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), and [Fabric](https://fabricmc.net/). Let's first set up a basic mod profile.

> [!NOTE]
> Other mod loaders include [Quilt](https://quiltmc.org/en/), [NeoForge](https://neoforged.net/), [Rift](https://www.curseforge.com/minecraft/mc-mods/rift), [LiteLoader](http://www.liteloader.com/), and [Risugami's Modloader ](https://ftb.fandom.com/wiki/Risugami's_Modloader) (DISCONTINUED). We will not be going over these mod loaders as most of them are inactive, discontinued, in heavy development, or not very popular.

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
 2. Click on your preferred version and Download the Recommended INSTALLER (If you wish to, you can choose the Latest Installer). Upon completion open the downloaded file. 
    
  ![Forge Download Page](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20at%2019-32-45%20Minecraft%20Forge%20downloads.png?raw=true)
  
 3. You should now see this! Click on `OK` and wait for it to install. (The Black mark is your profile name.) Wait for Forge to be installed.
    
  ![Forge Download Prompt](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20194112.png?raw=true)

You should see this after the download has been completed.

  ![Download Complete](https://github.com/Spookfu/moddedmc/blob/main/IMGS/Screenshot%202023-08-19%20194234.png?raw=true)

 5. Open the Minecraft Launcher and you should see a forge profile in your Installations List.
    
    ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/fol-test.png?raw=true)

    That's it! Now that you've set up a simple mod loader, it's time to add mods!
    
    <details>
    <summary>If not, click here! </summary>
    <br>

    1. Click on the Installations Tab

    ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/istall-test.png?raw=true)
    

    2. Check the Box called `MODDED` on the top, then click `New Installation`.
     
    ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/ew-istall-test.png?raw=true)

    3. Click on Versions, and scroll down until you see the desired Version, then click `Create`.

    ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/forge-fial.png?raw=true)
    
    You're done! Now that you've set up a simple mod loader, it's time to add mods!

    </details>
</details>


<details>
<summary> MultiMC / Prism Launcher </summary>
<br>

**MultiMC / Prism Launcher**
1. Open the Launcher and click `Add Instance`

![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-1.png?raw=true)

2. Choose your preferred version, click on `Forge` then press `OK`

![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-2.png?raw=true)

3. You should see this now!

![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-3.png?raw=true)

You're done! Now that you've set up a simple mod loader, it's time to add mods!
You can learn more on how to use Prism Launcher [HERE](https://prismlauncher.org/wiki/getting-started/)

</details>

<details>
<summary> CurseForge </summary>
<br>

1. Open CurseForge, and click on `Create Custom Profile`
   
![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/curseforge-1.png?raw=true)

2. Enter a Name for your profile, choose your preferred version, and click on Forge. Once you're satisfied, click `Create`

   ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/curseforge-forge.png?raw=true)

3. You should see this now.
   ![image](https://github.com/Spookfu/moddedmc/assets/75686139/02a83e66-9686-40dc-a30e-db7966612374?raw=true)

You're good to go! Now that you've set up a simple mod loader, it's time to add mods!

</details>


</details>


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
   
![image](https://github.com/Spookfu/moddedmc/assets/75686139/94fc2ba2-5390-4897-aeb8-f85478b18d7f?raw=true)

4. Click on `Download for Windows` (or `Download universal jar` if you're not using Windows), and open the downloaded file.
> [!NOTE]
> Fabric has their own [Installation guide](https://fabricmc.net/wiki/install) that you can look through instead of here.

![image](https://github.com/Spookfu/moddedmc/assets/75686139/8fee7f0d-4ccc-4dea-9247-96cb2e8b2003?raw=true)

5. You should see this now! Choose your preferred version (Check the Show Snapshots button for Snapshot versions), check `Create Profile`, if it isn't already, and press `Install`

![image](https://github.com/Spookfu/moddedmc/assets/75686139/85c9883e-5eec-4865-a95a-bb0b74705a05?raw=true)

> [!NOTE]
> This is what you should see right now.
> 
> You should see this after the download has been completed.
>
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/e25d039f-365a-4c33-b0be-527345b67bfe?raw=true)

6. Open the Minecraft Launcher, and you should see a fabric profile in your Installations List.
![image](https://github.com/Spookfu/moddedmc/assets/75686139/b97c938f-015a-4e05-a4b7-851dd876c8e4?raw=true)

That's it! Now that you've set up a simple mod loader, it's time to add mods!

</details>

<details>
<summary> MultiMC / Prism Launcher </summary>
<br>

**MultiMC / Prism Launcher**
1. Open the Launcher and click `Add Instance`

![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-1.png?raw=true)

2. Choose your preferred version, click on `Fabric` then press `OK`

![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-faric.png?raw=true)


3. You should see this now!
   
> ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/prism-3.png?raw=true)

You're done! Now that you've set up a simple mod loader, it's time to add mods!
You can learn more on how to use Prism Launcher [HERE](https://prismlauncher.org/wiki/getting-started/)

</details>

<details>
<summary> CurseForge </summary>
<br>

1. Open CurseForge, and click on `Create Custom Profile`
   
   ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/curseforge-1.png?raw=true)

2. Enter a Name for your profile, choose your preferred version, and click on Fabric. Once you're satisfied, click `Create`

   ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/curseforge-faric-start.png?raw=true)

3. You should see this now.
  
   ![image](https://github.com/Spookfu/moddedmc/blob/main/IMGS/curseforge-faric-fial.png?raw=true)


You're good to go! Now that you've set up a simple mod loader, it's time to add mods!

</details>

</details>

# PART 2 - Installing Mods
Now that you've set up a way to load mods, it's time to actually add mods. Remember the points listed at the [start](https://github.com/Spookfu/moddedmc#ii-mod-management)!

<details>
<summary> Vanilla </summary>
<br>

**Using Vanilla Launcher:**
1. Press `Windows + R`
2. Type in `%appdata%`
   
> [!NOTE]
> This is what you should see right now.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/c82b00bd-bac0-4164-b31f-246842247aec)
   
4. Go into the folder called `.minecraft`
5. Create a folder named `mods` if it doesn't exist.

> [!NOTE]
> The other contents of your folder do not need to look exactly like this. The important part is that `mods` folder EXISTS.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/5244affd-8dc4-4887-bbd2-2b8d486feed1)

6. Go to either [Modrinth](https://modrinth.com/) or [Curseforge](https://beta.curseforge.com/minecraft/search?page=1&class=mc-mods&sortType=2&pageSize=20) and download the mods you wish to play.

> [!IMPORTANT]
> Remember the points listed at the [start](https://github.com/Spookfu/moddedmc#ii-mod-management)!

7. Once the mods are downloaded, drag the files into the `mods` folder

![image](https://github.com/Spookfu/moddedmc/assets/75686139/c4ce8f2d-e2c4-40a9-9ebe-9a148a42f91c)

8. Test if your game runs!


</details>

<details>
<summary> MultiMC / Prism Launcher </summary>
<br>

1. Go to the `Mods` tab, and click either `Download Mods` or `Add File`
> [!NOTE]
> If you wish to manually add mods, the `Add File` button is the way to go.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/9294586d-dacd-4ef2-b1e4-9ebe78b4472b)

2. Search the mods you want to play with, select the mod version, press `Select mod for download`, and press `Review and Confirm`.
> [!NOTE]
> 1. Unlike CurseForge, MultiMC/Prism Launcher does not automatically download the mod's dependencies. You will need to manually search and install the mods dependencies.
> 2. You can select multiple mods at once and install them simultaneously. Select mods titles are bolded and underlined.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/7675e2ab-e382-4aaf-8650-87072100e2c4)

3. Review your mods, once you're satisfied click `Ok`.

![image](https://github.com/Spookfu/moddedmc/assets/75686139/d418a5ba-55d0-4058-9626-d5ed722672ec)

3. Confirm that you've installed the mod.

> [!NOTE]
> You can update your mods in bulk by selecting your mods and clicking `Check for Updates
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/81842caf-c7ad-4ed5-8c72-f475a976def4)

5. Test if your game runs!

</details>

<details>
<summary> CurseForge </summary>
<br>

1. Click the Puzzle Icon
   
![image](https://github.com/Spookfu/moddedmc/assets/75686139/9082a1f7-c73a-4ed3-8a34-07c1246eb173)

2. Search the mods you wish to download, and click the `Install` Button
> [!NOTE]
> 1. You can also install/add Resource Packs and even Worlds
> 2. CurseForge automatically installs the correct version and any required dependencies of the mod you installed
> 3. Client Mods are mods that do not need to be on a server if you are playing a Modded SMP
>
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/f2258026-11fc-4d55-ac56-3cc8e73a23a9)

3. Confirm that you've installed the mod.
> [!NOTE]
> If a mod has an update available, an update button will appear.
> 
> ![image](https://github.com/Spookfu/moddedmc/assets/75686139/72ade405-c22f-4104-a9f6-b566bfefdc05)

8. Test if your game runs!


</details>



# PART 3 - Issues
## Debugging Issues
Crashes and other issues are bound to happen. The easiest way to debug issues is by looking at your Logs. Here is how to view them:

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



    



