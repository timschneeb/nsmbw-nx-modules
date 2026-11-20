# NSMBW-Switch modules

Source code available at [nsmbw-nx](https://github.com/timschneeb/nsmbw-nx).

This repo contains individual mod packs & updates downloaded by the launcher.

> [!IMPORTANT]
> This repo does NOT contain copyrighted assets, only custom assets from community mods. It is unusable, unless you provide your personal Wii disc dump.

## Manual installation

If you don't want to use the launcher for some reason, you can install mod packs manually.
This release asset layout was designed in a way to make automated updates possible while saving bandwidth, so no all-in-one ZIP pack is provided.

* On the SD card, create folder: `sdmc:/switch/nsmbw/games/`
* In that folder, create another folder for each game you want to install (e.g. `vanilla` or `newersmbw`)
* Copy the game NRO of the mod you want to that sub-folder and rename the file to `game.nro`
* If one exists, extract the romfs resource pack (`*.romfs.zst`) for the mod using a ZSTD-capable extractor and copy the extracted `*.romfs` file into that sub-folder alongside the NRO.
* Create folder `sdmc:/switch/nsmbw/banners/` and copy the PNG banner files for all mod packs you want to install into it. Rename the banner file names to remove `-banner` from their file names.

## Release assets

- `launcher.nro` - launcher self-update payload
- `vanilla-game.nro` - vanilla runtime update payload
- `vanilla-debug-symbols.zip` - vanilla crash symbols
- `newersmbw-game.nro` - Newer runtime
- `newersmbw.romfs.zst` - compressed Newer resource image
- `newersmbw-banner.png` - Newer catalogue banner
- `newersmbw-debug-symbols.zip` - Newer crash symbols
