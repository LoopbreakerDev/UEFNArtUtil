# UEFN (Patched) Art Tools

This is a custom made utility plugin for patched UEFN to speed up the process of using it for art purposes. This is a release of the workflow I made and use  [for my own art.](https://vnova.dev/gallery).

This is not necessary for art creation in UEFN, it only makes it more convenient. The utility is a combination of my own work as well as some classes and functions already available in Fortnite.

## What This Plugin Contains
The main focus of this plugin is one main Editor Utility Widget with the following:
- Quick Character spawner/customizer (FX applied)
- Quick Sidekick spawner/customizer
- Quick Weapon/Pickaxe spawner with good success rate on proper Materials/FX applied
- Quick Sprite spawner (FX applied)
- Template Level for simple character render creation. Comes with Blender-like World presets + optional lighting presets
- Shortcuts to speed up creation and management of organized render folders, Levels, and Level Sequences
- Fortnite Body and Face Control Rigs (ported from an official UEFN template)

This plugin is __not perfect__, but it does work in most cases.

## What is "Patched UEFN"

Patched UEFN is when the standard Unreal Editor for Fortnite is modified to allow the plugins that lock down Unreal Engine to be disabled, among some other fixes. It is required to use this utility.

This utility does NOT patch UEFN on its own. For that, I recommend using Carbon.

Please note that the following are not supported in patched UEFN:
- Kicks
- Vehichle Cosmetics
- LEGO Minifigures

### IMPORTANT NOTE ON PATCHED UEFN:

__UEFN runs off live updates (meaning Fortnite assets may be added, removed, or modified between versions), is beefy as a program, and can easily CRASH. Be aware of this before using it.. and please save often!__

# Installation

Patched UEFN is required before moving on. You can use Carbon to easily do this, download it in their [Discord](https://discord.gg/carbon).

Also install __Frezzi.zip__ from this repo

Extract frezzi.zip and move the folder that houses __Frezzi.uplugin__ to the following location where Fortnite is installed:

`.../Fortnite/FortniteGame/Plugins/GameFeatures/`

You can now launch Carbon in editor mode to launch Patched UEFN

## Your First Launch

With Patched UEFN open, navigate to the following location in the content browser (you can paste this into the top bar)

`/Frezzi/Utility`
_(if using the Content Browser visually, this location will be Plugins->ArtUtil->Utility)_

_Note that while the plugin is called __Frezzi__, its FriendlyName is __ArtUtil__. The FriendlyName is what will be displayed in the Content Browser outside of file path contexts. I didn't want to rename the plugin to not potentially break references._

Right click the Blueprint called __EUW_CosmeticSearch__ and select __"Run Editor Utility Widget"__. You'll want to dock this somewhere in the editor so you can keep it open between sessions.

## Further Unreal Engine Help

Unreal Engine can be hard for a newcomer! I have written up a walkthrough of a very basic process going from a fresh UEFN launch to a finished scene. You can see it [here](./help/help.md).

I suggest checking this out quickly even if you have used UEFN/UE5 before. It includes a small plugin guide as well as tips for helping UEFN not crash.