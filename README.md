# Sonic-CD-2011-Script-Decompilation

A full decompilation for the scripts in Sonic CD's 2011 remake.

These scripts have been manually reverted back to what the original scripts could've looked like. This means that:
* Function IDs have been recoverted back to function names
* Some function names have been given proper names
* Functions are in the proper order
* Default aliases have been re-added where possible
* Mobile/Haptic code has been added into scripts via the use of `#platform:` markers

To use these scripts in mods, extract the scripts folder to the exe's root directory: eg `[rootdir]/Scripts/`. If you're using the Steam version of Sonic CD, make sure the mod loader is fully up to date, as the mod loader loads all default scripts from `Scripts/`. Mods are only required to include the scripts that have been changed.

For anyone curious about how Sonic CD's scripting language works, check out the handbook (RetroScript Handbook v3.pdf) we made to help get people into using RetroScript v3. We recommend downloading the handbook as it makes it easier to navigate.
