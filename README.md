# Marble Blast Fubar Unity Remake

The unity port of the popular Marble Blast Gold modification Marble Blast Fubar. This project is technically a fork of my Marble Blast Platinum Unity Port. This project started from CyberFox's [MarblePhysics Unity](https://github.com/CyberFoxHax/MarblePhysicsUnity) that already has a faithful marble movement physics, then continued with codes based on [Marble Blast Web Port](https://github.com/Vanilagy/MarbleBlast) and [Marble Blast Haxe Port](https://github.com/RandomityGuy/MBHaxe/). The Unity version used is Unity 6.3 and with High Definition Render Pipeline (HDRP) so you might need to have a decent GPU to run this game.

Below are screenshots of the game (you can see other screenshots in this repository). This repository only for placing build download and level screenshots, the actual project files are private (due to usage of paid assets).

<img src="https://i.imgur.com/Vz3Axl4.jpeg" width="640">
<img src="https://i.imgur.com/NzRP0hT.jpeg" width="640">
<img src="https://i.imgur.com/lweyR6V.jpeg" width="640">
<img src="https://i.imgur.com/Q8a6ZrT.jpeg" width="640">
<img src="https://i.imgur.com/TkqxPBm.jpeg" width="640">

## System Requirements

As this project uses HDRP, you need a decent GPU to run the game at in at least 30 FPS.
**Minimum Requirements**
- OS: Windows 10 (64-bit)
- CPU: Intel Core i5-4460 / AMD Ryzen 3 1200
- RAM: 8 GB
- GPU: NVIDIA GTX 1060 (6GB) / AMD RX 580
- VRAM: 4–6 GB
- Storage: 5 GB of Free Space

**Recommended Requirements**
- OS: Windows 10/11 (64-bit)
- CPU: Intel Core i7-8700 / AMD Ryzen 5 3600 or better
- RAM: 16 GB
- GPU: NVIDIA RTX 2060 or better / AMD RX 5700 XT or better
- VRAM: 8 GB+
- Storage: 5 GB of Free Space

## Download the Windows build [here](https://github.com/NaCl586/marble-blast-fubar-unity/releases/tag/1.0)

Report any bugs by personal message on discord NaCl586#8479.

Special thanks to Vani and RandomityGuy for helping me whenever I have problems when making this project. Special thanks also to Aayrl for giving me permission to remake the mod in unity.

## Save Data

<img src="https://i.imgur.com/u2wAziG.png" width="640">

Save data uses [PlayerPrefs](https://docs.unity3d.com/6000.0/Documentation/ScriptReference/PlayerPrefs.html), which can be accessed via Registry Editor (see picture). All levels are unlocked by default so no need to modify the PlayerPrefs value. The PlayerPrefs essentially is equivalent to prefs.cs in vanilla Marble Blast.
