# Rom Patcher GitHub Pages Sample
A sample using RomPatcherJS on GitHub Pages site with customizations.

## Why
Current patches are hosted across many different sites, forums, and Discord servers. The process for applying the patches, though currently fairly painless with the RomPatcherJS site, could be made much simpler for free with currently provided tools.

This repo was made as a guide for setting up a free GitHub repo for distributing ROM patches using customized RomPatcherJS embedded into a GitHub Pages site, which is also how the current RomPatcherJS is setup. But by providing the patch files yourself and customizing a few files, you can make the process much faster and idiot<sup>tm</sup>-proof.

## How To Initialize
- Clone repo
- Upload patch files to ./patches/ (for downloads) and ./patches.zip (for patching) **NOTE: patches directory and patches.zip should be identical**
- Upload custom wide logo as ./logo.webp
- Update index.html as required
- Setup GitHub Pages & distribute link
- (Optional but Recommended) GitHub Actions to auto-update RomPatcherJS

## How to Update Site
- Update ./patches/ with new patches
- Zip ./patches/ as ./patches.zip and upload both
- Update index.html to match

## How To Use To Download Patched Game
- Upload your matching base ROM file
- (Optional but Recommended) The patch for your ROM file hash will be selected automatically
- Click apply patch

## Features
- Validating ROM file hash
- Automatically selecting a patch file by the hash of the provided ROM file
- Providing multiple patches in drop down
- Providing a default output name for each patch (Recommended `Title (Rev vX.Y.Z) (Developer) (Hack)` because I name my files that way)
- Display patch title, description, recommendations, and supporting resources

## Issues & To-Do
- Get Download Patch to work
- Add a latestpatches.zip as default. Switch between latestpatches.zip and patches.zip with a button.  

## [Semantic Versioning](https://semver.org)
- Versions are labeled as MAJOR.MINOR.PATCH (vX.Y.Z)
- Simple & consistent versioning scheme makes the scope of changes clear (and I prefer having a relatively versioning schema in my rom hack file names)
- Patch examples: updating power of an attack, fixing typos
- Minor examples: adding new areas/characters/bosses
- Major examples: an update that is incompatible with saves from prior versions or requires manual intervention from the user like converting the save with a third party tool or taking steps in game to make their existing save compatible

## More Information
- [Embedding Rom Patcher JS](https://github.com/marcrobledo/RomPatcher.js/wiki/Embedding-Rom-Patcher-JS)
- [Github Pages Quickstart](https://docs.github.com/en/pages/quickstart)
- [Semantic Versioning](https://semver.org)

## Projects Used
- [Rom Patcher JS - patches ROMs](https://github.com/marcrobledo/RomPatcher.js)
- [Pokemon Crystal Legacy Rom hack - used as an example patch](https://github.com/cRz-Shadows/Pokemon_Crystal_Legacy)
- [Team Aqua's Patch Cove - modified some customizations they created for their patching site](https://github.com/TeamAquasHideout/tah-patchsite)
