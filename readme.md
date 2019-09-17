# First attempt at balancing Phoenix Point abilities

## Installation instructions

Go to _Releases_ page on this repo and download the latest files.

*For exe installer* run and point to your root game directory (with PhoenixPoint.exe). Installer makes backup copy of changed files (.bak0000) on every apply, which may quickly fill your disk space. 
*For package installer* Download [Unity Asset Bundle Extractor](https://github.com/DerPopo/UABE). Choose File->Load Package File. It should open the resources and apply chanes. Close UABE and click Save when prompted.

## Changes:

* Dash - now costs 1 AP to use, and can only be used once per turn
* Quick Aim - costs 2 AP to activate. Still retains bonus accuracy and reduces the actual shot cost by 1 AP, so end result is spending 1 AP more for accuracy. Should be renamed Careful Aim, as soon as I figure out where the localisation strings are stored

## License: MIT (see license file)
Do what you want. Please share source. No warranties. Please backup your game files before making changes.
