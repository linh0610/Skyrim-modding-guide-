# Skyrim Modding Guide

Welcome to the Skyrim Modding Guide! This guide will help you to mod Skyrim and enhance your gaming experience.

## Table of Contents


- [Installation](#installation)
- [Troubleshooting](#troubleshooting)

## Installation

Here are the steps to install the mods:

1. Step 1 : The set up
1) Get mod manager and install it.
Mod Organizer 2, Vortex Mod Manager, or Nexus Mod Manager (use the.exe file). Each of the three of them has a unique mod management skill that helps the player. What distinguishes the two? NMM is "straightforward yet successful". If we can call it that, MO is a mod manager on steroids with a ton of cool features. Vortex is somewhere in the middle; it is more like MO, but it also has its own advantages and disadvantages (for a comparison, see here). Mod manager can and should be used to install almost all mods. Do not manually install mods. While there are a few exceptional situations in which you may need to manually install a mod or part of a mod, the majority of the time, you should always use the mod manager. These NMM tutorial, MO2 tutorial, and Vortex information pages may also be of use to you. Added note: Before contacting support for troubleshooting, if you're using MO2, make sure you've watched the linked tutorial and know how to use it correctly. Important note #1:
I tested Vortex mod manager and found it to work well. I liked it, but I don't like it as much as MO2 or NMM. You'll have to learn how to use and troubleshoot it yourself because it's not exactly the most popular mod manager. I won't be able to offer Kortex troubleshooting support in Discord for the same reason; however, it is a fantastic mod manager, and you should absolutely feel free to try it.
Significant NOTE #2: The Nexus Mods team is currently working on Vortex, a mod manager. Despite its impressive visual appearance, it remains incredibly glitchy and dysfunctional. If you use it, I won't be able to help you with problems because it can't be used to modify games like FO or TES. Currently, my recommendation is to track it and test it by modding other games with much simpler stages if you really want to. Do not modify Skyrim with Vortex. Once more, DO NOT MODIFY SKYRIM WITH VORTEX. This note is still in effect for 2021, yes. I'll let you know if it goes well one day.

2) Install SKSE by downloading it. Excellent if you already possess it. If not, set it up. It's required.
[Link text Here](https://skse.silverlock.org/)
[Essential] SKSE exists. In addition, stability mods and the vast majority of fantastic gameplay mods are working on it. Consider it a fundamental component of Skyrim's invisible evolution.
Be certain to download the appropriate version! 1.7.3 is for Skyrim LE, which is no longer required. Obtain SKSE for 1.5.97 if you have the exact Skyrim SE version (1.5.97; right-clicking on the game.exe file will reveal the version). Get the most recent AE version and the VR version for virtual reality if you're on AE (it's still called Skyrim Special Edition in your game library; the.exe file is different). Unpack the archive that you downloaded somewhere. Take the.dll,.exe, and Data folders from the folder and move them to your Skyrim SE/AE folder in the manner shown here. Users of MO should archive the Data folder and install it like any other mod through MO (you can also do this in NMM if you want). Launch your game using SKSE (skse64_loader.exe) only now, not the game's normal launcher.
2. Step 2 : Where to get mods
While there are hundreds of websites that provide mods for Skyrim, only a few of them are used by most modders. Here are two websites most fans get their mods from:

Nexus Mods [nexusmod](https://www.nexusmods.com/skyrim): The definitive space to find mods for PC Skyrim fans. Both the original and Special Edition versions of Skyrim have mods on this website.


Bethesda.net: Console players get their mods from here, although PC players can use it as well. Skyrim: Special Edition's in-game mod menu pulls its content from here.

More websites than these two provide Skyrim mods, but these two are the most popular. Both websites have search bars and tags you can use to find mods that interest you.
3. Step 3 : The mods you needed for stability
3) Download and install SkyUI.
As mod itself, SkyUI is basically a "PCfication" of ugly vanilla Skyrim interface. On practice, it's also required by most of well-known mods in addition to SKSE. Also install this fix for it, this ==NEW== (get the ESP version), this ==NEW== and this.
Optionally (but very recommended as it's just looks so much more alive and beautiful) install animated icons mod for it (make sure to choose "Celtic" icons type in SkyUI MCM for this mod to work). Also optionally, install this "wider" addon for MCM look. Also install iHUD.

4) Download and install LOOT.
LOOT is a must-have tool if you're planning to have many mods. It's very easy to install and use.
Its most basic and important function is mod sorting. Many mods should be loaded in strict load order to work properly together. "This mod should be loaded before that mod, but after that", and so on. LOOT makes miracles! You can automatically sort most of your mods properly by just clicking a button twice. Sometimes (it happens rarely, so you probably won't have to think about it) some mods have direct instructions about how they should be loaded, in this case it's also easy to sort them manually using it. Also, LOOT shows you all you need to know about your installed mods - errors, missing records etc. In many cases, if something is not right - it will let you know and it will advise you. In most of cases, you' won't need to read and learn more than this to use it, but if something is unclear or you want to learn advanved usage of LOOT (which can come in handy from time to time), check this awesome video. Use LOOT sorting each time after you've installed a few mods.

5) Install Address Library for SKSE Plugins.
Note: make sure to get a proper mod version, depending on whether your game version is SE or AE. If you're on Skyrim "VR", get this one ==NEW== instead.
This mod is a partial solution to endless game update issues in SE (which breaks dll SKSE mods) - it allows for such mods to keep working properly not depending on the game version. Solution is partial because it doesn't work automatically - each dll SKSE mod must be updated by its author to depend on this one, and as not all authors are aware about this or just active, this solution won't be universal - but it clearly will help you with many mods which are usually broken after every update. Also, install this (make sure to get proper version too, depending on whether you're modding SE or AE).
6) Install SSE Engine Fixes.
Note #1: mods has TWO parts - first main file, the "Part 1" you can install with mod manager. Second, "Part 2", you should download manually, unpack and place all 3 .dll files to your Skyrim root folder (where Skyrim exe is).
Note #2: if you're using Skyrim VR, get this ==NEW== instead.

7) Install Bug Fixes SSE.
Fixes some SE engine bugs. In its configuration file (BugFixesSSE.json), disable the Magic Effect Conditions fix (set magicEffectConditions to false instead of true). Make sure to also install .NET Script Framework which is required for Bug Fixes to work.
8) Install SSEEdit.
It's an awesome tool for cleaning your mods, making changes to mod records (like balancing various values up to your taste, deleting conflicting and/or unneeded objects and so on) and more.
Mods may contain "dirty" records and some other issues, and when you have hundreds of mods, that could be a problem and cause crashes. Clean all mods that have dirty records (until it's directly written by mod author to not do that for some reason) and all Skyrim's DLCs (which have [hundreds] of dirty records. Yeah - Betheshda didn't even bother to do this for the game "remaster"). Don't be afraid of it, it's not as hard to use as it may look. Check these awesome video tutorials about it. Also there is a lot of info and videos on its Nexus page.
Note #1: Make double sure to clean all base game master files (Update.esm and all 3 DLC .esm plugins) - otherwise you'll experience random crashes.
9) Install Wrye Bash.
Get the installer version and install it. WB is an amazing and essential tool to achieve maximum possible compatibility between all your mods.
We will use it later in our journey, so just grab it for now. I'll explain it later in the guide :)
Note: if you'll be noticing you're clearly going above 255 active .esp plugins limit somewhere still in process of adding more and more mods - refer to step #2 in "actions to be made in the end" section at the deep bottom of the guide.

10) Download zMerge (highly recommended) or Merge Plugins.
Yes, Merge Plugins is hosted in Skyrim LE sections and yes, it does work with SE absolutely fine. At the other hand, zMerge (it's a part of zEdit) works just fine with all mod managers, no just MO2 (big thank you Euphemia for once pointing me on this). You will need this if you'll make really heavy load order and reach the 255 plugins (.esp) limit. By merging mods, you can technically have almost endless amounts of mods installed, so you will be limited only by your PC specs and mods themselves (meaning no using broken/dangerous mods and not overloading your game with script-heavy mods). These tool (once again, zMerge is recommended over Merge Plugins) easily merges plugins into one .esp file, drastically decreasing the total amount of plugins and allowing you to install more and more mods.
But why zMerge over Merge Plugins? Simply said, it's more powerful and will allow you to merge more easily compared to Merge Plugins tool. For A to Z simple tutorials about using zMerge or Merge Plugins, watch these tutorials here (for Zmerge) and here (for Merge Plugins).
Note: But what about .esl'fying the mods? It's allegedly a cool feature, so maybe we don't need to merge mods at all anymore? There is a bit more about that - indeed, marking plugins as .esl is a new alternative way of not reaching the 255 plugins limit, but: 1) not all the same mods you can merge can be esl'fied, so sooner or later, you'll eventually need to merge mods anyway 2) esl/ified plugins have some specific bugs 3) Some other mods, especially mods with dynamic patchers (like ASIS, Bashed Patch etc) simply don't recognize .esl plugins [AT ALL], meanining that if you'll, let's say, have 200 esl plugins, and then build a Bashed Patch (which is essential for any medium-to-heavy modded game), all the changes/additions, whatever those plugins are doing, will be not present in your game with utmost chance, making them meaningless to begin with. The sooner you'll learn how to merge mods (guide provides assistance with this), the better it will be for you - moreover, as soon as you'll get the basics, you'll see there's nothing to fear at all :3
SOME mods are fine to be used as esls, and if for some of the mods/patches you're using there's no alternative asides of the esl version of its plugin - install it. The explanation/solution to this will is mentioned in the end of the guide.
11) Install [ONE] of these mods:
- Alternate Start - Live Another Life
Install the voiceover addon ==NEW== on top of the main mod (+ optional addons here , here, here ==NEW== or here ==NEW==).
- Skyrim Unbound Reborn
- RASR - Random Alternate Start Reborn
- Realm of Lorkhan - Freeform Alternate Start
- Optional Quick Start ==NEW==

Why you need this? These mods provide wide amount of alternative starts to the game for those who do not wish to go through the lengthy intro sequence at Helgen. The thing is that vanilla start (scene in Helgen) is VERY heavy-scripted. And when you will install let's say, 200+ mods and start a new game, your Skyrim will be very heavy overloaded. And there's very high chance that your game will crash (because the Papyrus, Skyrim's script engine, was [not] updated in SE and it's same clunky and limited), even if the game itself is absolutely stable. And now these mods save the day! You can just skip this heavy-scripted scene and start anywhere you like. Besides, they have a really wide amount of alternative start, great for roleplay.
Which one to use, what is the difference? Long story short, ASLAL provides more "roleplay-wise" starts - you will appear in a certain cell, depending on your start option choice, and also has plenty of additional start options addons.
Unbound will spawn you randomly, so less "immersive" start, but it allows you highly adjustable character customization (gear, spells etc) which ASLAL doesn't, and the most important - it allows you to play as NON-Dragonborn (but you can "become" it in MCM anytime), which is really a great option.
RASR is somewhat like a mix of these two, a pretty underrated gem and Realm of Lorkhan is a really fresh and unique alternate start mod, which may look note quite "lore-friendly" to some players, but it's really well-designed and give you very interesting starting choices for your character class and even curses - negative attributes to balance class bonuses (if you want so, all these features are entirely optional - my only 2 cents about it is that some class bonuses are still somewhat too strong even with curses, so you may want to adjust them in SSEEdit, which is very simple). Lastly, Realm of Lorkhan has on pretty immersion-breaking (for some players) thing - crystals you appear from after starting the game are not going anywhere and are just scattared across Skyrim. To remove them, use this patch. Also, make sure to install this fix.
Optional Quick Start is a super-simple alternative, which is not quite "alternate start" mod, but rather "skip Helgen into" one.

12) Get the Cathedral Assets Optimizer

This step is optional. Easy-to-use tool to convert meshes/textures from LE to SE (and backwards as well). This tool will help you to have the best from both game version in terms of such kind of mods.

13) The last in this section, but important and mandatory step.
Install all these amazing mods/patches/fixes which are oriented on fixing huge amount of various little bugs or irrational things in game or just to make you your game much more comfortable.

Note: Make sure to install proper versions of mods (where needed) for your SE/AE game version - thus, don't use the "Vortex" download button, but always go to "Files" tab and download proper mod version from there.

Unofficial Skyrim Special Edition Patch

This mod should be already considered as part of vanilla game. It fixes literally thousands glitches and bugs in Skyrim. Note: if you're modding the SE version of the game (1.5.97, not AE), simply use the latest SE version of the patch from here (add the file to your mod manager and install as usually).
.NET Script Framework

Required by some other things. Framework for memory editing, native code hooking and writing DLL plugins in any .NET language. Also provides crash logs which are sometimes and somewhat useful (SE - for AE, install this ==NEW==, can use it in SE/AE instead).

RaceMenu

Character creation menu how it should have been originally and great amount of customization options. For Skyrim SE (1.5.97), get the "RaceMenu Special Edition v0-4-16" version (direct download link in case of what). Also get this ==NEW== (make sure to - but only if you're on SE, not AE) and this.

Stay At The System Page NG ==NEW==

This mod brings back the behavior of original Skyrim's Journal Menu. Whenever you press the Escape key, mod will open the System page instead of Quest page. Muh convenient!

Better Dialogue Controls + Better MessageBox Controls

Ever pick the wrong item in a dialogue with a NPC or struggled with not cozy controls in messagebox popups? No more!

1st Person Candlelight Fix

Have you ever been annoyed that the candlelight spell is much brighter in 3rd person view than 1st person view? This mod aims to reduce that difference and make them more equal. Note: Don't let any other mod overwrite it, in case of what. Also, if you're modding Skyrim "VR", use this one instead.

Better Jumping SE
Allows to jump while sprinting.

Equip Enchantment Fix
Fixes engine bugs where item enchantments don't apply when equipped or stop working while the item is still equipped. SKSE64 plugin.

Major Cities Mesh Overhaul ==NEW==

Improves meshes and also some textures of many buildings, terrain meshes and other objects, which are used in the major cities of Skyrim.
Assorted mesh fixes

Fixes various issues with vanilla Skyrim meshes that caused them to render incorrectly.

Don't Stay in The Water

Fixes the bug that stupid enemies may stay in the water and look at you angrily but just don't come up.
Scrambled Bugs

A collection of several misc engine bug fixes, including couple of dll alternatives to existing plugin form of some bugfifixes. Get the proper version (SE/AE) and read the mod description page for the list of features and (possible) compatibility notes. Also make sure to install .NET 5.0 as it's required for Scrambled Bugs to work.

Note: enable the "attachHitEffectArt" (set to True instead of False) in ScrambledBugs.json file.

powerofthree's Tweaks

Similar thing here as well, as well as plenty optional QOL (quality of life) options. If you're in Skyrim "VR", install VR version ==NEW== instead.

Barter Limit Fix ==NEW==

SKSE plugin that fixes trading with merchants with more than 32,767 gold.

Atlas Map Markers - Updated with MCM

Essential mod that drastically increases amount of map markers. Remember how you was able to fast travel only to Whiterun itself or Dragonsreach? Now you can fast travel to Arcadia's Cauldron, Jorrvaskr etc. More than 700 new map markers! Also grab these small fixes and make sure to endorse the original mod.
Weapons Armor Clothing and Clutter Fixes + Armor and Clothing Extension
These two mod fix hundreds of bugs and inconsistencies for Skyrim's weapons, armors, clothing, jewelry, and clutter items and add more diversity and lore-friendly clothing options and gives NPCs more appropriate attire.

Complete Crafting Overhaul

Essential mod from author of previous two fixes. CCOR is reworking all vanilla craft recipes, offers many options for mining, chopping, smelting and so on - simply making everything crafting-related to be logical and really interesting. That's why you need it even if you never actually crafted a single thing in Skyrim - because now it's not that dull crafting system. Consider it as the vanilla part of the game as it always should have been from the release. Most of mod options can be enabled/disabled and configured via MCM.

Navigator - Navmesh Fixes ==NEW==

Navmesh improvements (read - NPCs getting stuck as idiots in some places) for dozens interiors in Skyrim.

CritterSpawn Congestion Fix ==NEW==

A fix for the critter (bugs, fish etc) spawner that decreases the general script load of your game.

Unequip Quiver

An SKSE plugin which removes the quiver/bolts when equipping weapons and spells or when the character unequips the bow or crossbow. Improved version of "Auto Unequip Ammo" mod.

More Informative Console

This mod edits the UI to show a great deal of additional information on npcs, items, and other objects when the console is opened, similar to the way MFG console worked for Skyrim LE. It may help you in various cases of game testing and possible issues solving.

ConsoleUtilSSE NG==NEW==

Needed for some other mods.

Fuz Ro D-oh - Silent Voice

An SKSE plugin that adds support for unvoiced in-game dialogs. Isn't doing anything by itself, by it's needed for many mods for mod-added dialogues to work properly.

Base Object Swapper ==NEW==

A utility SKSE plugin, will be needed for some other mods further in the guide.

AnimObject Swapper ==NEW==

Mod of a similar kinds for animations, will be used by some mods too.

powerofthree's Papyrus Extender ==NEW==

SKSE64 plugin that extends Papyrus (Skyrim's script engine) functionality - needed for couple dozens mods in this guide, install and forget.
Lightened Skyrim

Gain FPS across Skyrim with no visual difference. Note: install it later, when you'll finish "The Rest" section of the graphics guide.

Congrats, you're ready now!



## Troubleshooting
If you encounter crashing please first refer to the mod website to see if there are any in compatible mods that you are downloading together.

If you cannot find it on the mod page, it is best advised that you should test mods one by one to determine which mod is causing it and remove it
