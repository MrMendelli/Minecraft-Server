# Basics
This section cover preliminary information for understanding how this works and what is recommended to know for installing modded Minecraft clients and installing mods for them. Unless specified otherwise, it is common practice to install and use the latest versions of launchers, Minecraft builds, and mods.

## If you have not migrated your Mojang account to a Microsoft account, you will be required to. Account migration can be done [here](https://www.minecraft.net/en-us/mojang-account-move).

## Launcher
A launcher is a client used for running Minecraft, custom builds, and servers. How to use will depend based on what launcher you use. GDLauncher or Prism Launcher are recommended for managing multiple Minecraft instances with mods and resource packs.

## Mod API
A mod API is a framework developed for making mods. Some mods are only developed for specific frameworks, some are dveloped for all APIs, this will depend on a per-mod basis.

# Default Launcher

## Installation
1. Download the installer [here](https://www.minecraft.net/en-us/download).
2. Login with a <u>Microsoft</u> account.
3. Install Minecraft: Java Edition.

## Installing Fabric
1. Download the latest release [here](https://fabricmc.net/use/installer/).
2. Install using the default path unless you have changed it.
3. Install mods here: `%appdata%\.minecraft\mods\`

## Installing Forge
1. Download the latest release [here](https://files.minecraftforge.net/net/minecraftforge/forge/).
2. Install using the default path unless you have changed it.
3. Install mods here: `%appdata%\.minecraft\mods\`

## Paths
- Default: `%appdata%\.minecraft\`

# GDLauncher

## Installation
1. Download the latest release [here](https://gdlauncher.com/en/download/)
2. Login with a <u>Microsoft</u> account using the account button in the bottom-right of the window.
3. Add a new Minecraft instance with the `+` button in the bottom-left of the window.

## Installing Forge
1. Add a new instance by clicking the `+` button.
2. Select `Vanilla` > `Forge` > _(Minecraft version)_ > _(Forge version)_.
3. Install mods here: `<GdlauncherData>\<Instance>\mods\`
_*See paths below for more information on `<GdlauncherData>`._

## Paths
- Default: `%appdata%\gdlauncher_next\`
- Portable: `<GdlauncherRoot>\data\`

# Prism Launcher

## Installation
1. Download the latest release from [here](https://prismlauncher.org/download/).
2. Login with a <u>Microsoft</u> account with the account manager in the upper-right of the window.
3. Add a new Minecraft instance with the `Add Instance` button in the toolbar.

## Installing Fabric
1. Add a new custom instance.
2. Select `Fabric` in the mod loader list.
3. Select a mod API version. Use the latest unless specified otherwise in the server pack.
4. Name your instance.

## Installing Forge
1. Add a new custom instance.
2. Select `Forge` in the mod loader list.
3. Select a mod API version. Use the latest unless specified otherwise in the server pack.
4. Name your instance. 

## Paths
- Default: `%appdata%\PrismLauncher\instances\`
- Portable: `<PrismLaunsherRoot>\instances\`

# Additional Information

**If you get a synchronization error when connecting to a server with mods, it means a currently installed mod is either no longer located on your end or is out of date. The game should state which mods are the cause and what the reason is.**

If you plan on importing your settings and server lists from one instance to another, you will need to copy or move the following files to your new instance:

 - options.txt
 - servers.dat

If you plan on loading previous worlds, you will have to do the same with the `saves` folder as well.
