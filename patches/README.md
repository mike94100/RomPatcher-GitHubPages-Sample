# Requirements
* You will need a <b>clean</b> copy of an English `base crystal ROM`.
    * We <b>cannot tell you how or where to get this</b>, as it is illegal. But if you google it, you can quite easily find out.
    * Make sure the ROM is clean. No randomizes, no previous versions of Crystal Legacy or any other hack.

## Resources

* <b>Recommended Patching Tool</b>: https://www.marcrobledo.com/RomPatcher.js/
* If you need further assistance, there is a video guide here: https://www.youtube.com/watch?v=9yxjuwCJbjI
* Alternative generic written guide for all platforms: https://www.pokecommunity.com/threads/how-to-play-rom-hacks.458595/

# Instructions

* Before you get started, load your base crystal ROM into the rom patcher (or a hash checker) and check the SHA-1 hash. This should match the hash for your given version listed below. If it is not exactly this, you have a modified or bootleg ROM and you will have to find a real one.

* Here you have two patch files, one for each version of base crystal.
    * If you have `base Crystal V1.0 / Rev 0 / USA` with SHA-1 hash `f4cd194bdee0d04ca4eac29e09b8e4e9d818c133`, you should use the 1.0 patch file in `Version USA`. 
    * If you have `base Crystal V1.1 / Rev 1 / USA, Europe` with SHA-1 hash `f2f52230b536214ef7c9924f483392993e226cfb`, you should use the 1.1 patch file in `Version USA, Europe Rev 1`.    
    * Use this to patch your base crystal ROM with some patching software. Some people have had trouble or experienced bugs in game from using certain patchers. Our recommendation is given below.
* Alternate language versions are not compatible, as these will cause bugs.
* Once you have patched the file, I would recommend renaming the output ROM to `Pokemon Crystal Legacy` so you can differentiate.

## PC Users
* Recommended emulator for PC: https://mgba.io/downloads.html
* Recommended Patching Tool for PC: https://www.marcrobledo.com/RomPatcher.js/
* This video goes over the full process for patching and running in MGBA on PC: https://www.youtube.com/watch?v=9yxjuwCJbjI

## Android Users
* Recommended emulator for Android: https://play.google.com/store/apps/details?id=com.fastemulator.gbafree&hl=en_CA&gl=US
* Recommended Patching Tool for Android: https://www.marcrobledo.com/RomPatcher.js/
* Here is a detailed tutorial on how to patch the ROM and load it in an emulator on Android: https://forums.serenesforest.net/topic/51094-guide-to-patching-rom-hacks-on-android/
    * Note that this guide doesn't use rom patcher JS, however patching online is generally easier. The patching process using ROM Patcher JS will be exactly the same as IOS below, so you can follow that guide if you wish.

## IPhone Users
* Recommended emulator for Iphone users: https://apps.apple.com/ca/app/delta-game-emulator/id1048524688
* Recommended Patching Tool for IOS: https://www.marcrobledo.com/RomPatcher.js/
* Here is a detailed tutorial on how to patch the ROM and load it in Delta on IOS: https://www.pokemoncoders.com/play-pokemon-rom-hacks-ios-delta-emulator/
    * Some notes:
        * When downloading the patch files, manually select "Send to Files" for it to be saved
        * You should be able to just tap the .zip in Files to extract it
        * Load Rom Patcher JS from the above link, it will be able to see and load the ROM and BPS files and then the download it returns will already be a .gbc file, which will be immediately recognized by Delta.
