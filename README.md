# Rom Patcher GitHub Pages Sample
A sample for using GitHub Pages to provide a publicly accessible link to a rom hack patch file prefilled into Marc Robledo's Rom Patcher JS.

## How To Use To Distribute Patch
- Update index.html
- Upload patch files in .zip
- Setup GitHub Pages & Distribute link
- GitHub Actions to update ./rom-patcher-js
- Update .zip with new patch versions. Update .html to match.

## How To Use To Download Patched Game
- Patch file is preloaded into Rom Patcher JS
- Upload your matching base ROM file and click `Apply Patch`
- Optional: Patch for your ROM file hash will be selected automatically

## Features Used
- Validating ROM file hash
- Automatically selecting a patch file by the hash of the provided ROM file
- Providing multiple patches in drop down
- Providing a default output name for each patch (using format `Title (Rev vX.Y.Z) (Dev) (Hack)`)
- Links to other resources

## More Information
- [Embedding Rom Patcher JS](https://github.com/marcrobledo/RomPatcher.js/wiki/Embedding-Rom-Patcher-JS)
- [Github Pages Quickstart](https://docs.github.com/en/pages/quickstart)

## Projects Used
- [Rom Patcher JS to patch ROMs](https://github.com/marcrobledo/RomPatcher.js)
- [Pokemon Crystal Legacy Rom hack as an example patch](https://github.com/cRz-Shadows/Pokemon_Crystal_Legacy)
