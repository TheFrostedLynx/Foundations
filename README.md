# Requirements

### SSE v1.5.97
  Foundations utilizes SKSE v2.0.20 which requires SSE v1.5.97, so it is reccomended that you use the [SSE Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618).

###  .NET 5.0 Runtime
Foundations includes [Scramble Bug Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/43532) which requires [.NET 5.0 Runtime](https://dotnet.microsoft.com/download/dotnet/5.0/runtime). Download the x64 Desktop version.

# Installation

Download "Foundations.wabbajack" from [here] (INSERT LINK HERE) or up above. Download and open up [Wabbajack](http://www.wabbajack.org/#/) and click "Install from Disk." Select "Foundations.wabbajack" as the "Target Modlist" and set your "Installation Location" to where ever you want (I suggest outside of ProgramFiles(x86)). Afterwards, just sit back and let Wabbajack do its thing. Since Foundations uses the Stock Game System there is no files you should have to move into your game folder.

# Customizing Your List

Foundations is meant to be just that, a foundation for you to build your own modlist.
It could be played as is if you are looking for just a very (very, very) plain vanilla plus playlist.
Even though it has a rather large installion size, it is mostly from the [Unofficial High Definition Audio Project](https://www.nexusmods.com/skyrimspecialedition/mods/18115), [Cleaned Skyrim SE Textures](https://www.nexusmods.com/skyrimspecialedition/mods/38775), and [Skyrim Special Edition Upscaled Textures (SSEUT)](https://www.nexusmods.com/skyrimspecialedition/mods/34560) which just cleans up/increases the definition of textures and audio while still keeping it vanilla, and copying your installation of SSE.
None of the mods installed should edit the game from being far from vanilla. It was designed this way so that anyone could either have a fixed vanilla playthrough or a very simple foundation to build off of.
Foundations comes with premade seperators to help guide people who are still learning to mod. These can be used, ignored/deleted, rearranged or whatever, these are just the seperators I personally use for my modlist.
Another rule of thumb I use when making my own modlist is to match my plugin loader (list on the right) with my mod order (list on the left) with exceptions for mods that need them.

# Setting It Up

Foundations uses [Kezyma's Root Builder](https://www.nexusmods.com/skyrimspecialedition/mods/31720?tab=description) to help keep your game installation clean. Follow the intructions in the description of the mod page to set up any mods you may need to install directly into your game folder (such as ENBs or some .dll files). 
I recommend creating an empty mod in MO2 and name it "[Insert Mod Name] (Root Packed)" and then add only the files that need to be packed separately to the mod. 
Afterwards, everything should be good to go. 
If you are having problems with MO2 not being able to find SKSE, head to Plugins > Root Builder > Build, and it will create a back-up of your game folder and then add the root packed files to the folder.
Once you are done, or if you want to clean out your game folder for a different modlist, go to Plugins > Root Builder > Clean, and the root packed files will be removed and your game folder restored.

# Playing the Game

Once everything is to your liking, all you have to do is start the game through the SKSE executable in Mod Organizer.

You are now free to enjoy the game, have fun!
