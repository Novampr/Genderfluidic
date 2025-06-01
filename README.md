# Genderfluidic

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/613163671870242838.svg?color=%237289da&label=discord)](https://discord.gg/geysermc)
[![Crowdin](https://badges.crowdin.net/geyser/localized.svg)](https://translate.geysermc.org/)

> [!NOTE]
> The project is currently being renamed from Hydraulic to Genderfluidic, this is for pride month, this won't actually remain :)
> 
> Check the `master` branch for *actual* changes

Genderfluidic is a companion to Geyser which allows for Bedrock players to join modded Minecraft: Java Edition servers.

Genderfluidic is an open collaboration project by [CubeCraft Games](https://cubecraft.net).

## What is Genderfluidic?
Genderfluidic is a server-side mod, which allows for Bedrock players to join modded Minecraft: Java Edition servers. This project works alongside [Geyser](https://github.com/GeyserMC/Geyser) to make this possible.

### This project is still in very early development and should not be used on production setups! As such, there are no binaries currently distributed, and they must be retrieved by following the Project Setup instructions below!

## Contributing
Any contributions are appreciated. Please feel free to reach out to us on [Discord](https://discord.gg/geysermc) if
you're interested in helping out with Genderfluidic.

### Project Setup
1. Clone the repo to your computer.
2. Navigate to the Genderfluidic root directory and run `git submodule update --init --recursive`. This command downloads all the needed submodules for Genderfluidic and is a crucial step in this process.
3. The project should import into your IDE after the loom setup is complete. For more detailed information, see the [Fabric setup](https://fabricmc.net/wiki/tutorial:setup)
4. Use `./gradlew build` to compile a jar file, or use `./gradlew :fabric:runServer` or `./gradlew :neoforge:runServer` to run a server with Hydraulic installed. Make sure to install the Custom Item API V2 branch of Geyser (Experimental! Here be dragons!) into your `mods` folder as Hydraulic is designed around that new API! Any other build of Geyser is not guaranteed to work.

## Links:
- Website: https://geysermc.org
- Docs: https://wiki.geysermc.org/geyser/
- Download: https://geysermc.org/download
- Discord: https://discord.gg/geysermc
- Donate: https://opencollective.com/geysermc
