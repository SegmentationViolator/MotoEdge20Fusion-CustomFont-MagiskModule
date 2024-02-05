# Custom Font for Motorola Edge 20 Fusion

Replace the built-in `Slab` font with a font of your choice (TTF only),
then you can apply yout custom font to the phone by selecting `Slab` in
Moto App > Personalise > Fonts

## How does it work?

It replaces the `/product/fonts/RobotoSlab-Regular.ttf` with the font file of your desire.

### Why RobotoSlab.ttf?

That's the only file I found, which is selectable in the Fonts menu.

### Limitations

I tried adding files to `/product/fonts/` but Moto App doesn't display them, and because there's only one replaceable file (that I know of), at any time you can only have one custom font installed.

#### To-do

- [ ] Add a way to change the installed font without needing to reinstall the module
- [ ] Add a way to install multiple fonts (most probably not more than 4)

## Installation

- Download the `module.zip` file provided in the latest release
- Download a font of your choice (TTF only)
- unzip the `module.zip` into a temporary folder `module`
- Copy your font to `module/system/product/fonts/`, rename it to `RobotoSlab-Regular.ttf` (Replace the already existing `RobotoSlab-Regular.ttf` it's just a placeholder)
- Zip the contents of `module` (DO NOT ZIP THE FOLDER) and install this new zip file as a magisk module
- Reboot
- Done

## Usage

- Open Moto App
- Go to Personalise section
- Go to Fonts
- Select `Slab`
- Done
