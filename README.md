# Minecraft Collections

> 📝 The curated collections of awesome Minecraft-related things

## Contents

- [Mod Loaders](#mod-loaders)
- [Plugin Loaders](#plugin-loaders)

## Mod Loaders

_Mod Loaders allow you to load mods that can change [Minecraft][minecraft]'s game content in some way, such as to make
minor adjustments to the game's mechanics or implement entirely new features._

| Name                     | Author(s)                          | License                  | Links                                           |
|--------------------------|------------------------------------|--------------------------|-------------------------------------------------|
| [Minecraft Forge][forge] | [Minecraft Forge][minecraft-forge] | [LGPL-2.1][lgpl-2.1]     | [download][forge-download] [docs][forge-docs]   |
| [Fabric][fabric]         | [FabricMC][fabricmc]               | [Apache-2.0][apache-2.0] | [download][fabric-download] [wiki][fabric-wiki] |
| [Quilt][quilt][^wip]     | [QuiltMC][quiltmc]                 | [Apache-2.0][apache-2.0] | [download][quilt-download] [usage][quilt-usage] |

<!-- @formatter:off -->

[forge]: https://minecraftforge.net/
[minecraft-forge]: https://twitter.com/forgedevteam
[forge-download]: https://files.minecraftforge.net/
[forge-docs]: https://docs.minecraftforge.net/

[fabric]: https://fabricmc.net/
[fabricmc]: https://github.com/FabricMC
[fabric-download]: https://fabricmc.net/use/installer/
[fabric-wiki]: https://fabricmc.net/wiki/

[quilt]: https://quiltmc.org/
[quiltmc]: https://quiltmc.org/en/about/
[quilt-download]: https://quiltmc.org/en/install/
[quilt-usage]: https://quiltmc.org/en/usage/

<!-- @formatter:on -->

## Plugin Loaders

_Servers that implement (based on) vanilla [Minecraft][minecraft] server._

| Name                             | Authors                        | License              | Links                                                   |
|----------------------------------|--------------------------------|----------------------|---------------------------------------------------------| 
| [Spigot][spigot]                 | [SpigotMC][spigotmc]           | [LGPL-3.0][lgpl-3.0] | [download][spigot-download] [wiki][spigot-wiki]         | 
| [Paper][paper]                   | [PaperMC][papermc]             | [LGPL-3.0][lgpl-3.0] | [download][paper-download] [docs][paper-docs]           | 
| [Purpur][purpur]                 | [PurpurMC][purpurmc]           | [MIT][mit]           | [download][purpur-download] [docs][purpur-docs]         |
| [Sponge Vanilla][sponge-vanilla] | [SpongePowered][spongepowered] | [MIT][mit]           | [download][sponge-vanilla-download] [docs][sponge-docs] |
| [Folio][folia][^wip]             | [PaperMC][papermc]             | [GPL-3.0][gpl-3.0]   | [github][folia-github] [docs][folia-docs]               |

<!-- @formatter:off -->

[spigot]: https://www.spigotmc.org/
[spigotmc]: https://www.spigotmc.org/XenStaff/
[spigot-download]: https://www.spigotmc.org/link-forums/31/
[spigot-wiki]: https://www.spigotmc.org/wiki/

[paper]: https://papermc.io/software/paper
[papermc]: https://papermc.io/team
[paper-download]: https://papermc.io/downloads/paper
[paper-docs]: https://docs.papermc.io/paper

[purpur]: https://purpurmc.org/
[purpurmc]: https://github.com/PurpurMC
[purpur-download]: https://purpurmc.org/downloads
[purpur-docs]: https://purpurmc.org/docs/

[sponge-vanilla]: https://www.spongepowered.org/
[spongepowered]: https://docs.spongepowered.org/stable/en/about/staff.html
[sponge-vanilla-download]: https://www.spongepowered.org/downloads/spongevanilla
[sponge-docs]: https://docs.spongepowered.org

[folia]: https://papermc.io/software/folia
[folia-github]: https://github.com/PaperMC/Folia
[folia-docs]: https://docs.papermc.io/folia

<!-- @formatter:on -->

## Platforms

_There are Minecraft modding platforms._

### Servers

_[Minecraft][minecraft]'s servers allow players to play online or via a local area network with other people._

#### Third-party

_Servers that have written from scratch._

- [Glowstone](https://glowstone.net/) — A fast, customizable and compatible open source server for Minecraft: Java
  Edition.
- [Cuberite](https://cuberite.org/) — A lightweight, fast and extensible game server for Minecraft.
- [flying-squid](https://flying-squid.prismarine.js.org/) - Create Minecraft servers with a powerful, stable, and
  high-level JavaScript API.
- [Minestom](https://minestom.net/)[^2] — A Minecraft server implementation, open-source and without any code from
  Mojang.
- [Krypton](https://kryptonmc.org/)[^wip] — A fast, lightweight Minecraft server written in Kotlin.
- [Valence](https://github.com/valence-rs/valence)[^wip] — A Rust framework for building Minecraft servers.
- [feather](https://github.com/feather-rs/feather)[^wip] — A Minecraft server implementation in Rust.
- [MCHPRS](https://github.com/MCHPR/MCHPRS)[^wip] — A multithreaded Minecraft server built for redstone.

#### Hybrids

_Hybrid servers allow loads both mods and plugins in the same server._

- [Sponge Forge](https://spongepowered.org/) — The implementation of the Sponge API on the Minecraft Forge platform.
- [Mohist](https://www.mohistmc.com/) — Minecraft Forge Hybrid server implementing the Spigot/Bukkit API, formerly known
  as Thermos/Cauldron/MCPC+.
- [CatServer](https://catmc.org/) — A high-performance Bukkit and Forge hybrid minecraft server.
- [Arclight](https://github.com/IzzelAliz/Arclight) — A Bukkit(1.16/1.18/1.19) server implementation on Forge using
  Mixin.

#### Minecraft: Bedrock Edition

_Server software for [Minecraft: Bedrock Edition][mcbe]._

- [Nukkit](https://cloudburstmc.org/) — Nuclear-Powered Minecraft: Bedrock Edition Server Software.
- [PowerNukkit](https://powernukkit.org/) — A Nukkit fork which supports new Minecraft Bedrock features.
- [PocketMine-MP](https://pmmp.io/) — The highly customisable, open source server software for Minecraft: Bedrock
  Edition written in PHP.
- [Dragonfly](https://github.com/df-mc/dragonfly) — The heavily asynchronous server software for Minecraft Bedrock
  Edition written in Go.

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

## Websites

**Note**: This section may have BREAKING CHANGES in the near future.

### Wikis

- [Minecraft Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki) — Unofficial Minecraft Wiki maintained by
  community.
- [Feed The Beast Wiki](https://ftb.fandom.com/wiki/FTB_Wiki) — Official wiki for mods, modpacks, and maps related to
  FTB related to FTB.
- [Spigot Wiki](https://www.spigotmc.org/wiki/index/) — The SpigotMC community wiki.
- [wiki.vg](https://wiki.vg/Main_Page) — A wiki which stored technical documentation on reverse engineering efforts for
  the popular Minecraft game.

### Content Distribution Platforms

- [CurseForge Minecraft](https://beta.curseforge.com/minecraft) - The Home for the Best Minecraft Mods, also for
  other content in Minecraft.
- [Modrinth](https://modrinth.com/) - The place for Minecraft mods, plugin, data packs, shaders, resource packs,
  modpacks.
- [SpigotMC Resources](https://www.spigotmc.org/resources/) - The Spigot plugin distribution platform.

<!-- @formatter:off -->

[mit]: https://spdx.org/licenses/MIT.html
[apache-2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[lgpl-2.1]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
[lgpl-3.0]: https://www.gnu.org/licenses/lgpl-3.0.html
[gpl-3.0]: https://www.gnu.org/licenses/gpl-3.0.html

<!-- @formatter:on -->

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
[mcbe]: https://minecraft.fandom.com/wiki/Bedrock_Edition
