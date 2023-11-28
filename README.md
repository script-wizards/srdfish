# srdfish
use fuz to search rpg rules

## Usage

This repo contains a bunch of submodules to assist in searching for specific entries in an RPG System Reference Document.  

```sh
git clone --recurse-submodules https://github.com/script-wizards/srdfish.git # clone this repo with submodules
```

Be sure to install all the [requirements for fuz](https://github.com/Magnushhoie/fuz#requirements-pick-one-option).

```sh
./fuz/fuz -p ./ose # search through OSE srd
```

## WIP

- Preview Markdown files in Glow instead of Bat for pretty formatting
- Install script
- Add your own files

## Credits

This would not be possible without the work of OldManUmby for converting SRD into the Markdown format, and Magnushhoie for fuz.  
The code for the SRDs and fuz are licensed under their respective authors.
