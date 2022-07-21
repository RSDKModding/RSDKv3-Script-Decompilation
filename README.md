# Sonic CD 2011 Script Decompilation (WIP Cleanup Branch)

## **Please don't use this branch for your mods, as it's a heavy work-in-progress and is only here for testing!**

A full decompilation for the scripts in Sonic CD's 2011 remake.

These scripts have been manually reverted back to what the original scripts could've looked like. This means that:
* Function IDs have been recoverted back to proper function names
* Functions are in the proper order
* Default aliases have been re-added where possible
* Origins/Haptic/Renderer code has been added into scripts via the use of `#platform:` markers

To use these scripts in mods: 
* RSDKv3 Decompilation: Extract the scripts folder to the exe's root directory: eg `[rootdir]/Scripts/`.
* Steam (2011 Release): If you're using an up-to-date version of the mod loader, it will download and install these scripts automatically.

Mods are only required to include the scripts that have been changed.

For anyone curious about how Sonic CD's scripting language works, check out the handbook (RetroScript Handbook v3.pdf) we made to help get people into using RetroScript v3. We recommend downloading the handbook as it makes it easier to navigate.