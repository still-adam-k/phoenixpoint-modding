# First attempt at balancing Phoenix Point abilities

## Installation instructions

Go to _Releases_ page on this repo and download the latest files. Copy PhoenixPointBackerBuild. 

* For exe installer run and point to your root game directory (with PhoenixPoint.exe). Installer makes backup copy of changed files (.bak0000) on every apply, which may quickly fill your disk space. 
* For package installer Download [Unity Asset Bundle Extractor](https://github.com/DerPopo/UABE). Choose File->Load Package File. It should open the resources and apply chanes. Save changes to sharedassets0.assets.modded (need to be done in separate file, as it will not allow you to overwrite), close UABE rename original sharedassets0.assets to backup, and sharedassets0.assets.modded to sharedassets0.assets

## Changes:

* Tweaks to ability cost - Dash costs 1AP/3WP to use. Quick Aim renamed to Careful Aim and costs 2 AP to acitave (the shot is still 1 AP less, so in total you spend 1 AP more in exchange for acc bonus). Rage Burst has increased bullet spread (I hope). This should help with spamming them every time.
* Lowered will cost of aliens - kills give less WP, and aliens are less likely to panic
* Renamed Arthon to Crabman. If it looks like a crabman, walks like a crabman, it will be a crabman. Ditto Fishman :) 

## Next: 
Tweak armor values
* currently there is no incentive to use anything else than sniper armor. Make armor type disinct?
* sniper to +acc, but low armor < 10
* assault +speed, medium armor value (15 - 30?)
* heavy -speed, high armor value (35-50 - should be almost impervious to small arms fire). Maybe also + strength
* berserker - probably even more speed, <10 armor

## Ideas:
Specialize soldier gear - limit to only one main weapon
* increase weapon weight?
* balance base str against having 1 main weapon + 1 sidearm + 3 ammo + granade/medkit (but not 2 main weapons)

Tweak weapons values damage/burst values? 

Balance the abilities around status - Limit AP gain from Rapid Clearance. Look at other abilities

Overwatch accurace based on overwatch cone width?

Add smoke/flashbangs granades?

Suppression?

Prevent damage overflow from one part?

Bullets natively passthrough if damage exceed object HP?

Change wounds so headshots more leathal? Add native armour to head part/tweak HP?

Speed up mutations?

Fun things with overwatch cone?

## License: MIT (see license file)
Use how you want. Please attribute. No warranties. Please backup your game files before making changes.
