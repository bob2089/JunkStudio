# JunkStudio (.pkdwin Browser)

I grew up playing PixelJunk games, and PixelJunk Shooter in particular was a massive part of my childhood. I really wanted a solid, modern asset extractor for the `.pkdwin` archives, but I didn’t have the coding background to build a full C# desktop app and binary parser from scratch. 

I used AI to help me generate and assemble the code so I could actually make this tool a reality for myself and anyone else who wants to dig into the game's files.

> **Disclaimer:** PixelJunk is a registered trademark of Q-Games. JunkStudio is an unofficial, non-commercial fan tool built purely for archival, modding, and nostalgic research. All game assets and icons belong to Q-Games.

---

## What it Does

JunkStudio is a custom archive browser and asset extractor. While built with *PixelJunk Shooter* in mind, **it works with any PixelJunk game that uses the `.pkdwin` archive format.**


* **Browse & Search:** Instantly search through archive contents by name, hash, type, or offset.
* **Built-in Previews:** View textures (including `.dds`), preview text scripts, and listen to audio clips directly inside the tool.
* **Batch Exporting:** Export individual assets, extract textures automatically converted to `.png`, or dump entire archives.
* **Map & Model Tools:** Features experimental map and 3D model geometry previews for stage reverse-engineering.

---

## Download & Usage

No need to compile anything if you just want to use the tool!

1. Go to the **Releases** tab on the right and download the latest zip package containing `PixelJunk-Extractor.exe`.
2. Extract the zip to any folder.
3. Run `PixelJunk-Extractor.exe`.
4. Click **Open .pkdwin** and select a `.pkdwin` file from your game directory.
