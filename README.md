# Minecraft Collections

> 📝 A curated list of awesome Minecraft-related things

## Contents

* [Loaders](#loaders)
    * [Mods](#mods)

## Platforms

_There are Minecraft modding platforms._

### Mod Loaders

_Mod Loaders allow you to load mods that can change [Minecraft][minecraft]'s game content in some way, such as to make
minor adjustments to the game's mechanics or implement entirely new features._

- [Minecraft Forge](https://github.com/MinecraftForge/MinecraftForge) – Modifications to the Minecraft base files to
  assist in compatibility between mods.
- [Fabric](https://fabricmc.net/) – A lightweight, experimental modding toolchain for Minecraft.
- [Quilt](https://quiltmc.org/)[^wip] – A modding toolchain developed primarily for Minecraft that has been forked from
  The Fabric Project.

### Servers

_[Minecraft][minecraft]'s servers allow players to play online or via a local area network with other people._

#### Wrappers

_Servers that implement (based on) vanilla [Minecraft][minecraft] server._

- [Spigot](https://www.spigotmc.org/) – High performance Minecraft server implementation.
- [Paper](https://papermc.io/) – High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.
- [Purpur](https://purpurmc.org/) – A drop-in replacement for Paper servers designed for configurability and new, fun,
  exciting gameplay features.
- [Sponge Vanilla](https://spongepowered.org/) – The implementation of the Sponge API on top of Vanilla Minecraft.

#### Third-party

_Servers that have written from scratch._

- [Glowstone](https://glowstone.net/) – A fast, customizable and compatible open source server for Minecraft: Java
  Edition.
- [Cuberite](https://cuberite.org/) – A lightweight, fast and extensible game server for Minecraft.
- [flying-squid](https://flying-squid.prismarine.js.org/) – Create Minecraft servers with a powerful, stable, and
  high-level JavaScript API.
- [Minestom](https://minestom.net/)[^2] – A Minecraft server implementation, open-source and without any code from
  Mojang.
- [Krypton](https://kryptonmc.org/)[^wip] – A fast, lightweight Minecraft server written in Kotlin.
- [Valence](https://github.com/valence-rs/valence)[^wip] – A Rust framework for building Minecraft servers.
- [feather](https://github.com/feather-rs/feather)[^wip] — A Minecraft server implementation in Rust.
- [MCHPRS](https://github.com/MCHPR/MCHPRS)[^wip] – A multithreaded Minecraft server built for redstone.

#### Hybrid

_Hybrid servers allow loads both mods and plugins in the same server._

- [Sponge Forge](https://spongepowered.org/) – The implementation of the Sponge API on the Minecraft Forge platform.
- [Mohist](https://www.mohistmc.com/) – Minecraft Forge Hybrid server implementing the Spigot/Bukkit API, formerly known
  as Thermos/Cauldron/MCPC+.
- [CatServer](https://catmc.org/) – A high-performance Bukkit and Forge hybrid minecraft server.
- [Arclight](https://github.com/IzzelAliz/Arclight) – A Bukkit(1.16/1.18/1.19) server implementation on Forge using
  Mixin.

#### Minecraft: Bedrock Edition

_Server software for [Minecraft: Bedrock Edition][mcbe]._

- [Nukkit](https://cloudburstmc.org/) – Nuclear-Powered Minecraft: Bedrock Edition Server Software.
- [PowerNukkit](https://powernukkit.org/) – A Nukkit fork which supports new Minecraft Bedrock features.
- [PocketMine-MP](https://pmmp.io/) – The highly customisable, open source server software for Minecraft: Bedrock
  Edition written in PHP.
- [Dragonfly](https://github.com/df-mc/dragonfly) – The heavily asynchronous server software for Minecraft Bedrock
  Edition written in Go.

## License

[![Creative Commons Zero v1.0 Universal][cc-zero-badge]][repo-license]

<!-- SECTION: FOOTNOTES -->

[^wip]: Project is currently in development.

[^2]: As Minestom is a Java library, it must be loaded the same way any other Java library may be loaded.

<!-- SECTION: DECLARATIONS -->

<!-- MEDIA SOURCES -->

[cc-zero-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg "CC0 1.0 Universal"

<!-- LINKS -->

[repo-license]: https://github.com/GrassMC/minecraft-collections/blob/main/LICENSE

[minecraft]: https://minecraft.net/

[mcbe]: https://minecraft.fandom.com/wiki/Bedrock_Edition
