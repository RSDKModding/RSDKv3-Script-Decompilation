# Sonic-CD-2011-Script-Decompilation

a full decompilation for the scripts in Sonic CD (2011)'s PC port

- these scripts have been manually reverted back to what the original scripts could've looked like.
- that means that:
* function IDs have been recoverted back to function names
* some function names have been given proper names
* functions are in the proper order
* default aliases have been re-added where possible
* mobile/haptic code has been added into scripts via the use of `#platform:` markers




- to use these scripts in mods, first extract the scripts folder to the exe's root directory: eg [rootdir]/Scripts/, then make sure the sonic CD mod loader is fully up to date, since the mod loader loads all default scripts from scripts/ so mods are only required to include the scripts that have been changed

- for anyone curious about how Sonic CD's scripting language works, check out the handbook (Handbook.pdf) I made to help get people into using RSDKv3 & CD's scripting language
