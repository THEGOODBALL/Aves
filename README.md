[![Latest Version](https://img.shields.io/github/v/release/BaseMC/Aves)](https://github.com/BaseMC/Aves/releases)

# Aves
A Minecraft deobfusctor / code generator

Generates deobfuscated code based on the [emitted obfuscation files from mojang](https://www.minecraft.net/article/minecraft-snapshot-19w36a) (since 19w36a) in about 5 minutes

``platform independent`` ``no local installation of Minecraft required``

### [Download](https://github.com/BaseMC/Aves/releases/latest)

#### Requirements
* You have to agree to the [license under which the obfuscation map files are licensed](https://minecraft.gamepedia.com/Obfuscation_map#License)
* Recommended: 1.5-2 GB of RAM for the [decompiler](https://github.com/Vineflower/vineflower)
* Supported MC-versions: 1.14.4 or ``>=``19w36a (1.15+)

### Why?
This project is designed for people that want to quickly take a look at a part of the code and understand what is going on.

This is very useful e.g.<br/>- for quickly inspecting new versions<br/>- if you find a bug and want to know what causes it <br/>- if you are just interested in how things work :smile:<br/>
No need to wait for someone to release new mappings or a version.

The generated code is not perfect, but it's readable and that's what it's meant for.

The project trys to work as automated as possible.<br/>
So if Mojang doesn't do any (breaking) changes, it should work a long time :t-rex:

### [Usage](docs/Usage.md)

### [Developing](docs/Developing.md)

### [Building](docs/Building.md)
