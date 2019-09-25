# First attempt at balancing Phoenix Point abilities

## Installation instructions

Go to _Releases_ page on this repo and download the latest files.

* For exe installer run and point to your root game directory (with PhoenixPoint.exe). Installer makes backup copy of changed files (.bak0000) on every apply, which may quickly fill your disk space. 
* For package installer Download [Unity Asset Bundle Extractor](https://github.com/DerPopo/UABE). Choose File->Load Package File. It should open the resources and apply chanes. Close UABE and click Save when prompted.

## Changes:

* Dash - now costs 1 AP to use, and can only be used once per turn
* Quick Aim - costs 2 AP to activate. Still retains bonus accuracy and reduces the actual shot cost by 1 AP, so end result is spending 1 AP more for accuracy. Should be renamed Careful Aim, as soon as I figure out where the localisation strings are stored

## Ideas:
Balance the abilities:
* Abilities that can be used often should not be overpowerd, and should not be used for free (either: end turn, use once per turn or have AP cost)
* Remove ot try to nerf effect of abilities that are broken (eg. Rapid Clearance)

Speclialise soldier gear - balance armor:
* currently there is no incentive to use anything else than sniper armor. Make armor type disinct?
* sniper to +acc, but low armor < 10
* assault +speed, medium armor value (15 - 30?)
* heavy -speed, high armor value (35-50 - should be almost impervious to small arms fire). Maybe also + strength
* berserker - probably even more speed, <10 armor

Specialize soldier gear - limit to only one main weapon
* increase weapon weight?
* balance base str against having 1 main weapon + 1 sidearm + 3 ammo + granade/medkit (but not 2 main weapons)

Limit how much you can control by panic
* Lower willpower cost, so aliens don't loose willpower too fast
* increase base willpower?
* ?

Add smoke/flashbangs granades
* reuse the mist mechanic?
* find a status to limit AP and apply on granade?
* find a status to lower acc and apply on granade?

## License: MIT (see license file)
Do what you want. Please share source. No warranties. Please backup your game files before making changes.
