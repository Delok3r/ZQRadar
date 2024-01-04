[![Discord](https://img.shields.io/discord/1191823969167352039?style=for-the-badge&logo=discord&label=Discord)](https://discord.gg/XAWjmzeaD3)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Zeldruck/Albion-Online-ZQRadar/main?style=for-the-badge&label=Last%20Commit)]()
[![GitHub issues](https://img.shields.io/github/issues-raw/Zeldruck/Albion-Online-ZQRadar?style=for-the-badge&label=Issue)](https://github.com/Zeldruck/Albion-Online-ZQRadar/issues)
[![GitHub Repo stars](https://img.shields.io/github/stars/Zeldruck/Albion-Online-ZQRadar?style=for-the-badge)]()

## ❓ What is ZQRadar?

ZQRadar is a radar type tool for the game Albion Online.
\
Albion ZQRadar provides a real-time map, helping players detect other players, creatures, resources and more, nearby.

## 🎯 Features

- No injections, less risk of banning
- Display a lot of information about other players (health, items, mounted or not, ...)
- Display customizable resources (select tiers and enchantments for each)
- Display customizable living resources (select tiers and enchantments for each)
- Display customizable enemies
- Display mist beasts
- Display chests (types)
- Display mist portals (solo/duo, enchantments)
- Display dungeons (solo/duo, enchantments)
- Display background map on radar

And much more to come!
\
Join the [Discord](https://discord.gg/XAWjmzeaD3) to look at the to-do list.

## 🔰 How to run (Windows)

1. Download Node.js v18.18.2:
- [Node.js v18.18.2 (64-bit)](https://nodejs.org/dist/v18.18.2/node-v18.18.2-x64.msi)
2. Download Npcap:
- [Npcap 1.72](https://npcap.com/dist/npcap-1.72.exe)
3. Download the source code of the latest release
- [Releases](https://github.com/Zeldruck/Albion-Online-ZQRadar/releases)
4. Open the file `_INSTALL` and wait for the line:
```
Press any key to continue . . .
```
5. Open the file `_APP` and wait for the line:
```
Server is running on http://localhost:5001
```
6. You can now access the radar features by going to `http://localhost:5001` in your browser.

## ✨ Image Packs
**⚠️(This is not mandatory for the radar to work)⚠️**
\
You can download the Image Packs to enhance the radar.
\
\
**Packs:**
- **Ressource Pack v1.0**: Installed by default
- **Items Pack v0.0**: [Link](https://github.com/Zeldruck/Albion-Online-ZQRadar/releases/tag/item-pack-v0.0)
- **Animals & Harvestables Pack v0.0**: [Link](https://github.com/Zeldruck/Albion-Online-ZQRadar/releases/)
- **Enemies Pack v0.0**: [Link](https://github.com/Zeldruck/Albion-Online-ZQRadar/releases/)
- **Maps Pack v0.1**: [Link](https://github.com/Zeldruck/Albion-Online-ZQRadar/releases/tag/map-pack-v0.1)

\
Once downloaded, exitract the folder into `Albion-Online-ZQRadar/images/`.
\
\
Example:
\
If you have downloaded the Map Pack, you should have `Albion-Online-ZQRadar/images/Maps/*.png`.


## Credits
[@Zeldruck](https://github.com/Zeldruck)
\
Based on [QRadar](https://github.com/FashionFlora/Albion-Online-Radar-QRadar) by [@FashionFlora](https://github.com/FashionFlora?)
\
Use of [photon-packet-parser](https://github.com/0xN0x/photon-packet-parser) to parse packets.