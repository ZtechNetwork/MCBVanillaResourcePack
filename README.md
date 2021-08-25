# Minecraft: Bedrock Edition Resource Pack
## Repository Status
![GitHub All Releases](https://img.shields.io/github/downloads/ZtechNetwork/MCBVanillaResourcePack/total) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/ZtechNetwork/MCBVanillaResourcePack) ![GitHub last commit](https://img.shields.io/github/last-commit/ZtechNetwork/MCBVanillaResourcePack/master)

## Game Music Warning
Game music will no longer be included in our package for copyright reasons. If you need any reference to music, use the `sounds_definitions.json` file in the `sounds` directory.

## Resource Pack Changelogs
As of v1.17 and up, specific changelogs for resource packs will be included for every release on the [releases](https://github.com/ZtechNetwork/MCBVanillaResourcePack/releases) page and on this README. Since all of the specific changes are not documented by Mojang, some listed will be based off of speculation. If any information is missing, please create an issue.

## Changelogs
### v1.17.10
#### New Textures:
- Candle (White, Orange, Magenta, Light Blue, Yellow, Lime, Pink, Gray, Light Gray, Cyan, Purple, Blue, Brown, Green, Red, Black)
- Potted Azalea
#### Changes:
- The Ender Dragon rendering and animations are now fully data-driven.
- The Ender Crystal rendering and animations are now fully data-driven.
- The Horse rendering and animations are now fully data-driven.
- This work supports all Horse variants (Horse, Mule, Donkey, Zombie Horse, Skeleton Horse) and all Horse versions including:
    - v1 (engine version 1.2.5 and earlier)
    - v2 (engine version 1.2.6 to 1.17.0)
    - v3 (engine version 1.17.10 and onward). This will be a cleaner version of the v2 model, with less confusing bone naming.
- Updated UI (New Realms Menu)
- View the official changelog [here](https://feedback.minecraft.net/hc/en-us/articles/4404454406285-Minecraft-1-17-10-Bedrock-).

### v1.17.0
#### New Textures:
- **Mobs:**
    - Axolotl
    - Goat
    - Glow Squid
- **Blocks/Items:**
    - Powder Snow
    - Glow Lichen
    - Amethyst
    - Amethyst Cluster/Bud
    - Budding Amethyst
    - Amethyst Shards
    - Glow Inc Sac
    - Glow Item Frame
    - Glow Berries
    - Tinted Glass
    - Copper (Exposed, Weathered, Oxidized)
    - Cut Copper (Stairs & Slabs included)
    - Waxed Cut Copper (Stairs & Slabs included)
    - Copper Ore
    - Copper Ingot
    - Lightning Rod
    - Spyglass
    - Raw Ore (Copper, Iron & Gold)
    - Deepslate
    - Infested Deepslate
    - Cobbled Deepslate (Stairs, Fences and Slabs included)
    - Polished Deepslate (Stairs, Fences and Slabs included)
    - Chiseled Deepslate (Stairs, Fences and Slabs included)
    - Deepslate Tiles (Stairs, Fences and Slabs included)
    - Cracked Deepslate Tiles
    - Deepslate Bricks
    - Cracked Deepslate Bricks
    - Deepslate Ore (Coal, Copper, Iron, Gold, Diamond, Lapis, Redstone, Emerald)
    - Tuff
    - Smooth Basalt
    - Dripstone
    - Pointed Dripstone
    - Dripleaf (Big & Small)
    - Moss Block
    - Moss Carpet
    - Azalea
    - Flowering Azalea
    - Azelea Leaves
    - Flowering Azalea Leaves
    - Rooted Dirt
    - Hanging Roots
    - Cave Vines
    - Spore Blossom
    - Bucket Axolotl
    - Tinted Glass
#### Changes
- Added two new variables to the `biomes_client.json` file: `remove_all_prior_fog` and `inherit_from_prior_fog`, which control fog merging and/or inheritance.
- `remove_all_prior_fog`, when true, will clear all previous fog definitions stored on the stack, making the current pack the new `starting point` for fogs.
- `inherit_from_prior_fog`, when true, will merge a biome's fog definition with matching biomes on the stack then create a new merged definition for it.
- `transparentattachable` tag should only affect rendering in first person camera perspective.
- Fixed Enchanted Bow's textures being too dark.
- Updated UI (Settings Menu, Marketplace)
- Added animation controllers for Goats, Axolotls & Glow Squids.
- Added new sound effects.
- Modified some block & mob textures.
- View the official changelog [here](https://feedback.minecraft.net/hc/en-us/articles/4402427632013-Minecraft-Caves-Cliffs-Part-I-1-17-0-Bedrock-).

```
    All assets belong to Mojang & Microsoft.
```