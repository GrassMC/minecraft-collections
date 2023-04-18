# Minecraft Collections

> 📝 A curated list of awesome Minecraft-related things

## Contents

- [Wikis & Docs](#wikis--docs)
- [Mod Loaders](#mod-loaders)
- [Server Wrappers](#server-wrappers)
- [Third-party Servers](#third-party-servers)
- [Hybrid Servers](#hybrid-servers)
- [Bedrock Servers](#bedrock-servers)

## Wikis & Docs

| Name                                                                                                     | Description                                                                                                                                                     |
|----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Minecraft Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki)                                       | Unofficial Minecraft Wiki maintained by community.                                                                                                              | 
| [Official Feed The Beast Wiki](https://ftb.fandom.com/wiki/FTB_Wiki)                                     | Official wiki for mods, modpacks, and maps related to FTB related to FTB.                                                                                       |
| [wiki.vg](https://wiki.vg/)                                                                              | A wiki which stored technical documentation on reverse engineering efforts for the popular Minecraft game.                                                      |
| [Minecraft: Bedrock Edition Creator Documentation](https://learn.microsoft.com/en-us/minecraft/creator/) | Learn how to mod Minecraft with Add-Ons. Create skins, design unique experiences, discover the latest features, and develop your skills as a Minecraft creator. |
| [bedrock.dev](https://bedrock.dev/)                                                                      | A technical Minecraft: Bedrock Edition documentation.                                                                                                           |
| [Bedrock Wiki](https://wiki.bedrock.dev/)                                                                | A knowledge-sharing website for Technical Bedrock, containing documentation, tutorials, and general how-to information.                                         |
| [Minecraft CreepyPasta Wiki](https://minecraftcreepypasta.fandom.com/wiki/Minecraft_Creepypasta_Wiki)    | A wiki for Minecraft Creepypastas.                                                                                                                              |

## Mod Loaders

_Mod Loaders allow you to load mods that can change [Minecraft][minecraft]'s game content in some way, such as to make
minor adjustments to the game's mechanics or implement entirely new features._

| Name                     | Description                                                                                         | Status | Links                                           |
|--------------------------|-----------------------------------------------------------------------------------------------------|--------|-------------------------------------------------|
| [Minecraft Forge][forge] | Modifications to the Minecraft base files to assist in compatibility between mods.                  | ✅      | [download][forge-download] [docs][forge-docs]   |
| [Fabric][fabric]         | A lightweight, experimental modding toolchain for Minecraft.                                        | ✅      | [download][fabric-download] [wiki][fabric-wiki] |
| [Quilt][quilt]           | A modding toolchain developed primarily for Minecraft that has been forked from The Fabric Project. | 🚧     | [install][quilt-install]                        |

<!-- @formatter:off -->

[forge]: https://github.com/MinecraftForge
[forge-download]: https://files.minecraftforge.net/
[forge-docs]: https://docs.minecraftforge.net/en/latest/

[fabric]: https://fabricmc.net/
[fabric-download]: https://fabricmc.net/use/
[fabric-wiki]: https://fabricmc.net/wiki/

[quilt]: https://quiltmc.org/
[quilt-install]: https://quiltmc.org/install/

<!-- @formatter:on -->

## Server Wrappers

_Servers that implement (based on) vanilla [Minecraft][minecraft] server._

| Name                             | Description                                                                                                    | Status | Links                                                           |
|----------------------------------|----------------------------------------------------------------------------------------------------------------|--------|-----------------------------------------------------------------|
| [Spigot][spigot]                 | High performance Minecraft server implementation.                                                              | ✅      | [usage][spigot-usage] [wiki][spigot-wiki]                       |
| [Paper][paper]                   | High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.                          | ✅      | [download][paper-download] [docs][paper-docs]                   |
| [Purpur][purpur]                 | A drop-in replacement for Paper servers designed for configurability and new, fun, exciting gameplay features. | ✅      | [download][purpur-download] [docs][purpur-docs]                 |
| [Pufferfish][pufferfish]         | A high-performance fork of Paper designed for large servers.                                                   | ✅      | [download][pufferfish-download] [docs][pufferfish-docs]         |
| [Sponge Vanilla][sponge-vanilla] | The implementation of the Sponge API on top of Vanilla Minecraft.                                              | ⚠️     | [download][sponge-vanilla-download] [docs][sponge-vanilla-docs] |

<!-- @formatter:off -->

[spigot]: https://www.spigotmc.org/
[spigot-usage]: https://www.spigotmc.org/wiki/buildtools/
[spigot-wiki]: https://www.spigotmc.org/wiki/spigot/

[paper]: https://papermc.io/software/paper
[paper-download]: https://papermc.io/downloads/paper
[paper-docs]: https://docs.papermc.io/paper

[purpur]: https://purpurmc.org/
[purpur-download]: https://purpurmc.org/downloads
[purpur-docs]: https://purpurmc.org/docs/

[pufferfish]: https://pufferfish.host/
[pufferfish-download]: https://pufferfish.host/downloads
[pufferfish-docs]: https://docs.pufferfish.host/

[sponge-vanilla]: https://spongepowered.org/
[sponge-vanilla-download]: https://spongepowered.org/downloads/spongevanilla
[sponge-vanilla-docs]: https://docs.spongepowered.org/

<!-- @formatter:on -->

## Third-party Servers

_[Minecraft][minecraft]'s servers that have written from scratch._

| Name                   | Description                                                                         | Languages | Status | Links                                                   |
|------------------------|-------------------------------------------------------------------------------------|-----------|--------|---------------------------------------------------------|
| [Glowstone][glowstone] | A fast, customizable and compatible open source server for Minecraft: Java Edition. | Java      | ✅      | [download][glowstone-download] [docs][glowstone-docs]   |
| [Cuberite][cuberite]   | A lightweight, fast and extensible game server for Minecraft.                       | C++       | ✅      | [download][cuberite-download] [manual][cuberite-manual] |
| [Limbo][limbo]         | Standalone Limbo Minecraft Server                                                   | Java      | ✅      | [download][limbo-download]                              |
| [NanoLimbo][nanolimbo] | The lightweight, high performance Minecraft limbo server                            | Java      | ✅      | [download][nanolimbo-download]                          |
| [Krypton][krypton]     | A fast, lightweight Minecraft server written in Kotlin.                             | Kotlin    | 🚧     | [download][krypton-download] [wiki][krypton-wiki]       |
| [MCHPRS][mchprs]       | A multithreaded Minecraft server built for redstone.                                | Rust      | 🚧     | [usage][mchprs-usage]                                   |
| [Obsidian][obsidian]   | A C# implementation of the Minecraft server protocol.                               | C#        | 🚧     | [usage][obsidian-usage]                                 |
| [feather][feather]     | A Minecraft server implementation in Rust.                                          | Rust      | 🚧     | [download][feather-download]                            |

<!-- @formatter:off -->

[glowstone]: https://glowstone.net/
[glowstone-download]: https://glowstone.net/#downloads
[glowstone-docs]: https://docs.glowstone.net/en/latest/index.html

[cuberite]: https://cuberite.org/
[cuberite-download]: https://cuberite.org/download-links/
[cuberite-manual]: https://book.cuberite.org/

[limbo]: https://github.com/LOOHP/Limbo
[limbo-download]: https://ci.loohpjames.com/job/Limbo/

[nanolimbo]: https://github.com/Nan1t/NanoLimbo
[nanolimbo-download]: https://github.com/Nan1t/NanoLimbo/releases

[krypton]: https://kryptonmc.org/
[krypton-download]: https://api.kryptonmc.org/downloads/v1/krypton/latest/download
[krypton-wiki]: https://wiki.kryptonmc.org/api/

[mchprs]: https://github.com/MCHPR/MCHPRS
[mchprs-usage]: https://github.com/MCHPR/MCHPRS#building

[obsidian]: https://github.com/ObsidianMC/Obsidian
[obsidian-usage]: https://github.com/ObsidianMC/Obsidian#-development-builds 

[feather]: https://github.com/feather-rs/feather
[feather-download]: https://github.com/feather-rs/feather/releases

<!-- @formatter:on -->

_Hybrid servers allow loading both mods and plugins in the same server._

## Hybrid Servers

| Name                         | Description                                                                                                              | Status | Links                                                       |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------|--------|-------------------------------------------------------------|
| [Sponge Forge][sponge-forge] | The implementation of the Sponge API on the Minecraft Forge platform.                                                    | ✅      | [download][sponge-forge-download] [docs][sponge-forge-docs] | 
| [Magma][magma]               | the most powerful Forge server providing you with mods and Plugins using Spigot and Paper for Performance and Stability. | ✅      | [download][magma-download] [wiki][magma-wiki]               |
| [Mohist][mohist]             | Minecraft Forge Hybrid server implementing the Spigot/Bukkit API, formerly known as Thermos/Cauldron/MCPC+.              | ✅      | [download][mohist-download] [wiki][mohist-wiki]             |
| [CatServer][catserver]       | A high-performance Bukkit and Forge hybrid minecraft server.                                                             | ✅      | [download][catserver-download] [docs][catserver-docs]       |
| [Arclight][arclight]         | A Bukkit(1.16/1.18/1.19) server implementation on Forge using Mixin.                                                     | ✅      | [download][arclight-download] [wiki][arclight-wiki]         |

<!-- @formatter:off -->

[sponge-forge]: https://spongepowered.org/
[sponge-forge-download]: https://spongepowered.org/downloads/spongeforge
[sponge-forge-docs]: https://docs.spongepowered.org/

[magma]: https://magmafoundation.org/
[magma-download]: https://magmafoundation.org/#downloads
[magma-wiki]: https://git.magmafoundation.org/magmafoundation/Magma/-/wikis/home

[mohist]: https://www.mohistmc.com/
[mohist-download]: https://www.mohistmc.com/download
[mohist-wiki]: https://wiki.mohistmc.com/

[catserver]: https://catmc.org/
[catserver-download]: https://github.com/Luohuayu/CatServer/releases
[catserver-docs]: https://github.com/Luohuayu/CatServer/blob/1.16.5/docs/README_EN.md

[arclight]: https://github.com/IzzelAliz/Arclight
[arclight-download]: https://github.com/IzzelAliz/Arclight/releases
[arclight-wiki]: https://github.com/IzzelAliz/Arclight/wiki

<!-- @formatter:on -->

## Bedrock Servers

_Server software for [Minecraft: Bedrock Edition][minecraft-bedrock]._

| Name                         | Description                                                                                         | Languages  | Status | Links                                                       |
|------------------------------|-----------------------------------------------------------------------------------------------------|------------|--------|-------------------------------------------------------------|
| [Nukkit][nukkit]             | Nuclear-Powered Minecraft: Bedrock Edition Server Software.                                         | Java       | ✅      | [download][nukkit-download] [wiki][nukkit-wiki]             |
| [PowerNukkit][powernukkit]   | A Nukkit fork which supports new Minecraft Bedrock features.                                        | Java       | ✅      | [download][powernukkit-download] [usage][powernukkit-usage] |
| [PocketMine-MP][pmmp]        | The highly customisable, open source server software for Minecraft: Bedrock Edition written in PHP. | PHP        | ✅      | [download][pmmp-download] [docs][pmmp-docs]                 |
| [Dragonfly][dragonfly]       | The heavily asynchronous server software for Minecraft Bedrock Edition written in Go.               | Go         | ✅      | [usage][dragonfly-usage] [wiki][dragonfly-wiki]             |
| [JSPrismarine][jsprismarine] | Dedicated Minecraft Bedrock Edition server written in TypeScript.                                   | TypeScript | 🚧     | [download][jsprismarine-download] [docs][jsprismarine-docs] |

<!-- @formatter:off -->

[nukkit]: https://cloudburstmc.org/
[nukkit-download]: https://ci.opencollab.dev/job/NukkitX/job/Nukkit/job/master/
[nukkit-wiki]: https://cloudburstmc.org/wiki/nukkit

[powernukkit]: https://powernukkit.org/
[powernukkit-download]: https://powernukkit.org/#download
[powernukkit-usage]: https://github.com/PowerNukkit/PowerNukkit#readme 

[pmmp]: https://pmmp.io/
[pmmp-download]: https://github.com/pmmp/PocketMine-MP/releases
[pmmp-docs]: https://doc.pmmp.io/en/rtfd/index.html

[dragonfly]: https://github.com/df-mc/dragonfly
[dragonfly-usage]: https://github.com/df-mc/dragonfly/wiki/Installation
[dragonfly-wiki]: https://github.com/df-mc/dragonfly/wiki

[jsprismarine]: https://avalanchepowered.org/
[jsprismarine-download]: https://github.com/JSPrismarine/JSPrismarine/releases
[jsprismarine-docs]: https://docs.avalanchepowered.org/

<!-- @formatter:on -->

## Platforms

_There are Minecraft modding platforms._

### Proxies

_Proxies allow linking together multiple [Minecraft servers](#servers), so they may appear as one._

- [Velocity](https://velocitypowered.com/) — The modern, next-generation Minecraft server proxy.
- [BungeeCord](https://www.spigotmc.org/wiki/bungeecord/) — Efficiently proxies and maintains connections and transport
  between multiple Minecraft servers.
- [Waterfall](https://github.com/PaperMC/Waterfall) — BungeeCord fork that aims to improve performance and stability.
- [Gate](https://gate.minekube.com/) — An extensible lightweight high-performance Minecraft reverse proxy with
  flexibility & excellent server version support - ready for the cloud!
- [Infrared](https://github.com/haveachin/infrared) — An ultra lightweight minecraft reverse proxy and idle placeholder.
- [VIAaaS](https://github.com/ViaVersion/VIAaaS) — ViaVersion as a Service - standalone ViaVersion proxy.
- [Geyser](https://geysermc.org/)[^3] — A bridge/proxy allowing you to connect to Minecraft: Java Edition servers with
  Minecraft: Bedrock Edition.

## Mods

### Optimization

- [Sodium (Fabric)](https://modrinth.com/mod/sodium) — Modern rendering engine and client-side optimization mod for
  Minecraft.
- [Lithium (Fabric)](https://modrinth.com/mod/lithium) — No-compromises game logic/server optimization mod.
- [Phosphor (Fabric)](https://modrinth.com/mod/phosphor) — No-compromises lighting engine optimization mod.
- [Iris Shaders (Fabric)](https://modrinth.com/mod/iris) — A modern shaders mod for Minecraft intended to be compatible
  with
- [FerriteCore](https://modrinth.com/mod/ferrite-core) — Memory usage optimizations.
  existing OptiFine shader packs.
- [OptiFine](https://www.optifine.net/home) — A Minecraft optimization mod.
- [OptiFabric](https://beta.curseforge.com/minecraft/mc-mods/optifabric) — A mod that can be used to run OptiFine on the
  Fabric Mod Loader.

### Maps

- [JourneyMap](https://modrinth.com/mod/journeymap) — Real-time mapping in game or in a web browser as you explore.
- [Xaero's Minimap](https://beta.curseforge.com/minecraft/mc-mods/xaeros-minimap) — Displays the nearby world terrain,
  players, mobs, entities in the corner of your screen.

### Storages

- [Storage Drawers (Forge)](https://beta.curseforge.com/minecraft/mc-mods/storage-drawers) — Interactive compartment
  storage for your workshops.
- [Refined Storage (Forge)](https://beta.curseforge.com/minecraft/mc-mods/refined-storage) — An elegant solution to your
  hoarding problem.
- [Applied Energistics 2](https://modrinth.com/mod/ae2) — AE2: A popular automation and storage mod.

### Utilities

- [Just Enough Items](https://modrinth.com/mod/jei) — JEI: View Items and Recipes.
- [Mouse Tweaks](https://modrinth.com/mod/mouse-tweaks) — Enhances inventory management by adding various functions to
  the mouse buttons.
- [AppleSkin](https://modrinth.com/mod/appleskin) — Food/hunger-related HUD improvements.
- [Carry On](https://modrinth.com/mod/carry-on) — Allows you to pick up Tile Entities and Mobs and carry them around.
- [Controlling](https://beta.curseforge.com/minecraft/mc-mods/controlling) — Adds a search bar to the Key-Bindings menu.
- [CraftTweaker](https://beta.curseforge.com/minecraft/mc-mods/crafttweaker) — Allows modpacks and servers to customize
  the game.

## License

[![Creative Commons Zero v1.0 Universal][cc-zero-badge]][repo-license]

<!-- SECTION: FOOTNOTES -->

[^wip]: Project is currently in development.
[^2]: As Minestom is a Java library, it must be loaded the same way any other Java library may be loaded.
[^3]: Hybrid proxy that enables clients from Minecraft Bedrock Edition to join your Minecraft Java server.

<!-- @formatter:off -->
<!-- SECTION: DECLARATIONS -->

<!-- Media sources -->

[cc-zero-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg "CC0 1.0 Universal"

<!-- Links -->

[repo-license]: https://github.com/GrassMC/minecraft-collections/blob/main/LICENSE
[minecraft]: https://minecraft.net/
[minecraft-bedrock]: https://minecraft.fandom.com/wiki/Bedrock_Edition
