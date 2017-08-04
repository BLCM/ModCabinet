# Download
## Patch
Online | Offline
-------|--------
[PatchRegular](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchRegular.txt) | [PatchRegularOffline](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchRegularOffline.txt)
[PatchExtreme](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchExtreme.txt) | [PatchExtremeOffline](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchExtremeOffline.txt)
[PatchVendor](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchVendor.txt) | [PatchVendorOffline](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/PatchVendorOffline.txt)

## Badassify
[Badassify](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/Badassify/Badassify%20v2.1.txt) | [Badassify Extreme](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/Badassify/Badassify%20Extreme%20v2.1.txt)
----|----

## Vendor+
[Vendor+](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/Vendor%2B/Vendor%2B%20v2.1.txt) |
----|

## Enemy Enhancer
[Enemy Enhancer](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/EnemyEnhancer/Enemy%20Enhancer%20v3.2.txt) | [Enemy Enhancer Extreme](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/EnemyEnhancer/Enemy%20Enhancer%20Extreme%20v3.2.txt)
----|----

## UVHM+ base
[UVHM+](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/theNocturni/UVHM%2B/uvhm%2B%20base/UVHM%2B%20v2.6.txt) | [UVHM+(speed)](https://raw.githubusercontent.com/BLCM/BLCMods/master/Borderlands%202%20mods/theNocturni/UVHM%2B/uvhm%2B%20base/UVHM%2B(speed)%20v2.6.txt)
----|----

## Tags
#GameMode

# Description
## How to install
UVHM+ is modularized to an extent, meaning you can choose what to use

EnemyEnhancer/Badassify/Vendor+ are hotfix parts of the mod
choose between the regular and Extreme version(or choose not to use either), and merge them into your community patch hotfix array(you can see how to merge hotfix below)
after youre done merging the hotfix

UVHM+ base is the non-hotfix part of the mod, choose between UVHM+.txt and UVHM+(Speed).txt (once again you can choose not to use either, but I personally recommend it if youre in it for the challenge)
and just execute it after you execute the community patch
### How to merge Hotfix
the ones without the (hotfix) are the console command version code
they can be executed as separate.txts, but they have to applied once your inside the game with the character(Krieg in this case)
and it has to be executed every single time you load up the character(aka it will be reset whenever you exit to the main menu)

## Merging/Filter tool
now you can use LightChaosman's incredible Filter tool to merge hotfixes/mods instead of going through the cumbersome process of doing it manually!
https://www.youtube.com/watch?v=2WSXBABY2nk&t=336s
for how to use and download

## How to merge Hotfix Manually
the ones with (hotfix) are the hotfix version codes
you will not have to execute them everytime you load the game but they cannot be run as a separate file
they have to be put in the main Community Patch file


the hotfix files will be formatted like this:
```
set Transient.SparkServiceConfiguration_6 Keys ("A")

set Transient.SparkServiceConfiguration_6 Values ("a")
```

in the main Community Patch file

there should also be sections that say
```
set Transient.SparkServiceConfiguration_6 Keys ("B","C","D","E",....)

set Transient.SparkServiceConfiguration_6 Values ("b","c","d","e",...)
```
put "A" and "a" (including the quotation marks) inside the parantheses for each respective line

ex:
```
set Transient.SparkServiceConfiguration_6 Keys ("A","B","C","D","E",....)

set Transient.SparkServiceConfiguration_6 Values ("a","b","c","d","e",...)
```
and execute the file in the main menu


## Video Guide
You can also check
https://youtu.be/CGqlI4wqbE4
for a video guide by AngrierPat on how to do it!(probably more helpful than my words here)

## Pre-merged files 
PatchVendor is Community Patch merged with Vendor+ for people who just want the better vendors

PatchExtreme is Community Patch merged with EnemyEnhancerExtreme,BadassifyExtreme,and Vendor+

PatchRegular is Community Patch merged with EnemyEnhancer,Badassify,and Vendor+

with these, you only need to choose which version of uvhm+.txt you want to use, and execute both(uvhm+.txt should be executed after the patchfile) in the console

## Description of each module

### Enemy Enhancer (hotfix)

 1.Enemy Enhancer

  -gives enemy better guns as your OP level goes up
   enemies may spawn with blue/purple/etech/even red text(unique/seraph/legendary/pearlescent) guns, and you will rarely see enemies using white or green gear on OP8

  -some enemies may spawn with blue/purple/Legendary/some red text(see list below) shields

  -makes some enemies roll faster and stagger for a shorter duration

  -doubles Turret/Deathtrap health and makes it unslaggable

 2.Enemy Enhancer Extreme

  -whats in Enemy Enhancer

  -every enemy may spawn with blue/purple/Legendary/some Red text shields (Warning: THIS INCLUDES RAID BOSSES)

### Badassify (hotfix)

 1. Badassify
   -increases badass spawn rates by about 100% on TVHM&UVHM(couldnt make it UVHM only)
   
 2. Badassify extreme
   -increases badass spawn rates by about 500% on TVHM&UVHM

### Vendors+

 1. Vendors+
   -improves vendor to have better stock on UVHM & as your op levels increase

#UVHM+ base (non-hotfix)

1.UVHM+.txt
  -reduces DoT buff to +150% instead of +250% and increases Maliwan SMG/Pistol DoT to compensate
  -increases badass health and shields by about 50%
  -gives enemy double shield recharge rate(not delay/capacity, just rate)
  -(hopefully) increases enemy accuracy
  -reduces enemy gun damage and DoT damage a bit to compensate for much better guns and more frequent DoTs
  -Improves world drop lootpool so that youd have a better chance for blue/purple/legendary, and less whites
  -improves the homing capability of Impaler

2.UVHM+(Speed).txt
  -whats in UVHM+.txt
  -increases player movement speed by 20%(multiplicative)
  -increases enemy movement speed by 50% and gives them 10% bullet speed

Credits and Thanks go to:

shadowevil1996 and his team for figuring out how to mod bl2 via console
once again shadowevil1996 and his team for creating the community patch
Adudney for creating the hotfix tool, giving a lot of advice, and figuring out a lot of stuff
AngrierPat,SirUmnei,Zububu for giving suggestions/advice and playtesting the WIP version of this mod
LightChaosman,MediEvilHero,Mike for giving suggestions/advice for the post-release version of this mod

### Red text gears that enemies can currently spawn with

guns- every red text gear EXCEPT for the following:

Hail
Rapier

Fibber
Lady Fist
Tinderbox
Grog Nozzle

Ahab
ERROR MESSAGE
Boom

Hawkeye

shields-

every legendary that you can obtain via world drop
Blockade
Evolution
Hoplite
Sponge
Cracked Sash
Deadly Bloom
Rough Rider
1340 Shield
Hide of Terramorphous
Manly Man Shield

# Changelog
Enemy Enhancer

v2-2017/06/04
1. added numerous red text guns/shields to enemies
2. made bandits in Digistruct Peak roll faster like their non-peak counterpart
		
v2.3-2017/06/04
1. fixed bugs that prevented enemies from spawning with some shields/made some shields have abnormaly high chance of spawning on enemies
	
v2.4-2017/06/10
1. Added Categories to make it more LightChaosman's Filter tool-friendly.
2. Added Orphan Maker/Teeth of Terramorphous/Manly Man Shield/Hide of Terramorphous to enemy pool.
		
v2.5-2017/06/11
1. fixed loader shield regenning in Extreme version.
2. removed some codes that are no longer necessary.

v3.0-2017/06/24
1. added Gemstone weaponry to enemies
2. removed booster shield/roid shield/blue absorb shields from enemies and increased the chance of enemies using purple shields
3. sped up the rolls of engineers, jumps of various enemies, and made EXPLoader charge up for a shorter time before exploading(it also loses its effect for some reason-will try to fix)
4. doubled the damage of thrown grenades by enemies(hopefully)
		
v3.1-2017/06/24
1. Sheriff now can spawn with a gemstone maliwan pistol, instead of always spawning with a green maliwan pistol
	
UVHM+

v2-2017/06/04
1. increased the homing capability of Impaler

v2.1-2017/06/04
1. removed an unintended line that affected the Impaler.
	
v2.2-2017/06/06

1. fixed vendors(and possibly enemies) being affected in NVHM and TVHM(although level 50 TVHM still may be affected)
	
known bugs: the weapon vendor in Liar's Berg will 'break', having less guns in stock compared to vendors elsewhere
	
v2.3-2017/06/10
	
1. Added Categories to make it more LightChaosman's Filter tool-friendly.
	
v2.4-2017/07/03
	
1. Removed Swap Speed in OP levels.
	
Badassify

v2-2017/06/04
1. initial release
	
v2.1-2017/06/10
1. Added Categories to make it more LightChaosman's Filter tool-friendly.
	
Vendor+

v2-2017/06/04
1. initial release
	
v2.1-2017/06/10
1. reduced the chance for Legendaries and purples in non-IOTD items
2. reduced the chance for Legendaries and increased the chance for purple/Etechs in IOTD items
3. Added Categories to make it more LightChaosman's Filter tool-friendly.