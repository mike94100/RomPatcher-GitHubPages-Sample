# Rom Patcher GitHub Pages Sample
A sample using RomPatcherJS on GitHub Pages site with customizations.

## Why
Currently patches are hosted across many different sites, forums, or Discord servers. The process for applying the patches can be made simpler at no cost and minimal prior knownledge. This repo was made as a guide & sample for using GitHub, GitHub Pages, and RomPatcherJS to distribute patches (same as the main RomPatcherJS site).

### Patching Differences
| Standard | Embedded |
| --- | ---|
| Open link to patch file | Open link to patcher site |
| Download patch file | |
| Open RomPatcherJS site | |
| Navigate to & upload base ROM file | &larr; |
| Navigate to & upload patch file | |
| Download patched ROM file | &larr; |
| Rename patched ROM file | |

### Features over standard RomPatcherJS site
- Customize the HTML/CSS (Logo, images, descriptions, links)
- Automatic patch selection (i.e. to select appropriate patch for a revision)
- Multiple patches in dropdown (different versions of a game, multiple revisions of base ROM, legacy revisions of patch)
- Custom file names (instead of patchname.ext or romname (patched).ext)

## How To
### Initialize
- Clone repo
- Upload patch file(s) as patches.zip
- Update index.html as required
- Setup GitHub Pages & distribute link
### Update
- Update patches.zip
- Update index.html

## To-Do
- Download from .zip or GitHub Releases (or other URLs) instead of /patches to limit repo size.

## Projects Used
- [Rom Patcher JS](https://github.com/marcrobledo/RomPatcher.js)
- [Pokemon Crystal Legacy](https://github.com/cRz-Shadows/Pokemon_Crystal_Legacy)
- [Team Aqua's Patch Cove](https://github.com/TeamAquasHideout/tah-patchsite)

## More Information
- [Embedding Rom Patcher JS](https://github.com/marcrobledo/RomPatcher.js/wiki/Embedding-Rom-Patcher-JS)
- [Github Pages Quickstart](https://docs.github.com/en/pages/quickstart)
- [Semantic Versioning](https://semver.org)
### Metadata Sources
- [IGDB International Games Database](https://www.igdb.com)
- [Screenscraper](https://www.screenscraper.fr)
- [RetroAchievements](https://retroachievements.org)
- [Hasheous](https://hasheous.org/index.html)
- [SteamGridDB](https://www.steamgriddb.com)
### Rom/Emulator Front-Ends
- [Romm](https://github.com/rommapp/romm)
- [Retrom](https://github.com/jmberesford/retrom)
- [Emulation Station DE](https://es-de.org)
- [Gaseous](https://github.com/gaseous-project/gaseous-server)
