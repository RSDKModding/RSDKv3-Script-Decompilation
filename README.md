# Sonic CD 2011 Script Decompilation (WIP Cleanup Branch)

## **Please don't use this branch for your mods, as we're still bug testing!**

A full decompilation for the scripts in Sonic CD's 2011 remake.

These scripts have been manually reverted back to what the original scripts could've looked like. This means that:
* Function IDs have been recovered back to proper function names
* Functions are in the proper order
* Default aliases have been re-added where possible
* Added editor renders and variables for (almost) every object
* Origins/Haptic/Renderer code have all been included via the use of `#platform:` markers

Some portions of the code have been slightly modified for compatibility purposes.

To use these scripts in mods: 
* RSDKv3/RSDKv5U Decompilation: Extract the `Scripts` folder to the exe's root directory: eg `[rootdir]/Scripts/`.
* Sonic Origins (Requires [HedgeModManager](https://github.com/thesupersonic16/HedgeModManager)):
  * Navigate to game's executable directory. The easy way to get to it is by clicking `Open Game Directory` in the Settings tab of HedgeModManager.
  * Once you're there, extract the `Scripts` folder into a folder named `SonicCDu` in the exe's root directory: eg `[rootdir]/SonicCDu/Scripts/`.
* Standalone Steam release (Requires the latest version of the [Sonic CD Steam Mod Loader](https://gamebanana.com/tools/6446)): The mod loader will automatically download and install the scripts upon launch.

Mods are only required to include the scripts that have been changed.

For anyone curious about how Sonic CD's scripting language works, check out the handbook (RetroScript Handbook v3.pdf) we made to help get people into using RetroScript v3. We recommend downloading the handbook as it makes it easier to navigate.
