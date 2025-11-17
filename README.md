# Rom Patcher GitHub Pages Sample
A sample using RomPatcherJS on GitHub Pages site with customizations.

## Why
Current patches are hosted across many different sites, forums, and Discord servers. The process for applying the patches, though currently fairly painless with the RomPatcherJS site, can be much simpler for free with currently provided tools.

This repo was made as a guide/sample for setting up a free GitHub repo for distributing ROM patches using RomPatcherJS embedded into a GitHub Pages site, which is also how the current RomPatcherJS site is setup. But by providing the patch files and customizing a few files, you can make the process much faster and idiot<sup>tm</sup>-proof while only ever requiring a single link.

## Features
- ROM file hash validation
- Automatic patch file selection using ROM file hash
- Support for multiple patches in a drop down
- Custom output names per patch
- Display patch title, images, description, and supporting resources

## How To
### Initialize
- Clone repo
- Upload patch files to ./patches/ (for downloads) and ./patches.zip (for patching) **NOTE: patches directory and patches.zip should be identical**
- Upload custom, preferably wide, logo as ./logo.webp
- Update index.html as required
- Setup GitHub Pages & distribute link
- (Optional) GitHub Actions to auto-update RomPatcherJS
### Update
- Update ./patches/ with new patches
- Zip ./patches/ as ./patches.zip and upload both
- Update index.html
### Patch
- Upload your matching base ROM file
- Either select the patch for your ROM or the patch will be selected automatically
- Click apply patch to download patched game
- Click download patch to download the patch file (tbd)

## Issues & To-Do
- Get Download Patch to work
- Switch between a recommended patch set & legacy patch set.
- Changing images/text based on the selected patch.

## [Semantic Versioning](https://semver.org)
- Versions are labeled as MAJOR.MINOR.PATCH (vX.Y.Z)
- Simple & consistent versioning scheme makes the scope of changes clear (and I prefer a common versioning schema)
- Patch examples: updating power of an attack, fixing typos
- Minor examples: adding new areas/characters/bosses
- Major examples: an update that is incompatible with saves from prior versions or requires manual intervention from the user like converting the save with a third party tool or taking steps in game to make their existing save compatible

## Front-Ends & Metadata
I personally use [Romm](https://github.com/rommapp/romm) as a front-end for my roms. Romm supports scraping various metadata sources for information about a game to display in the webapp. Selfishly, I like when this data is scraped automatically and I get "official" information like cover art and descriptions, so I'm presenting some of the options here.
### Metadata Sources
- [IGDB International Games Database - Title, Cover, Description, Screenshots, Genres, Companies, Release Dates](https://www.igdb.com)
- [Screenscraper - Art, Covers, Logos, Screenshots, Miximages](https://www.screenscraper.fr), see also [Miximage example](https://www.reddit.com/r/PokemonROMhacks/comments/1lvxeu0/pokemon_odyssey_miximage_for_launchers/)
- [RetroAchievements - Achievements & Verified File Hashes](https://retroachievements.org)
- [Hasheous - Verified File Hashes](https://hasheous.org/index.html)
- [SteamGridDB - Grids, Heroes, Logos, Icons](https://www.steamgriddb.com)
### Rom/Emulator Front-Ends
- [Romm](https://github.com/rommapp/romm)
- [Retrom](https://github.com/jmberesford/retrom)
- [Emulation Station DE](https://es-de.org)
- [Gaseous](https://github.com/gaseous-project/gaseous-server)

## More Information
- [Embedding Rom Patcher JS](https://github.com/marcrobledo/RomPatcher.js/wiki/Embedding-Rom-Patcher-JS)
- [Github Pages Quickstart](https://docs.github.com/en/pages/quickstart)
- [Semantic Versioning](https://semver.org)

## Projects Used
- [Rom Patcher JS - patches ROMs](https://github.com/marcrobledo/RomPatcher.js)
- [Pokemon Crystal Legacy Rom hack - used as an example patch](https://github.com/cRz-Shadows/Pokemon_Crystal_Legacy)
- [Team Aqua's Patch Cove - modified some customizations they created for their patching site](https://github.com/TeamAquasHideout/tah-patchsite)
