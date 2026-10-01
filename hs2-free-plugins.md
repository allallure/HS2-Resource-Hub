# 📚 HS2 FREE PLUGINS

> **Creation Date:** Sept 25, 2026
> **Version:** 1.0.0
> **Author:** allallure
---

- [📚 HS2 FREE PLUGINS](#-hs2-free-plugins)
  - [BepInEx](#bepinex)
  - [IllusionModdingAPI](#illusionmoddingapi)
  - [BepisPlugins](#bepisplugins)
    - [BGMLoader](#bgmloader)
    - [ExtensibleSaveFormat](#extensiblesaveformat)
    - [InputUnlocker](#inputunlocker)
    - [Screencap / Screenshot Manager](#screencap--screenshot-manager)
    - [Sideloader](#sideloader)
    - [SliderUnlocker](#sliderunlocker)
  - [BepInEx ConfigurationManager](#bepinex-configurationmanager)
  - [HSPlugins](#hsplugins)
  - [RuntimeUnityEditor](#runtimeunityeditor)
  - [ABMX](#abmx)
  - [KK\_Plugins (HS2)](#kk_plugins-hs2)
    - [StudioSceneLoadedSound](#studiosceneloadedsound)
    - [InvisibleBody](#invisiblebody)
    - [UncensorSelector](#uncensorselector)
    - [Subtitles](#subtitles)
    - [PoseTools](#posetools)
    - [ListOverride](#listoverride)
    - [FreeHRandom](#freehrandom)
    - [Colliders](#colliders)
    - [MaterialEditor](#materialeditor)
    - [MaleJuice](#malejuice)
    - [StudioObjectMoveHotkeys](#studioobjectmovehotkeys)
    - [FKIK](#fkik)
    - [AnimationOverdrive](#animationoverdrive)
    - [CharacterExport](#characterexport)
    - [StudioSceneSettings](#studioscenesettings)
    - [Pushup](#pushup)
    - [PoseQuickLoad](#posequickload)
    - [StudioImageEmbed](#studioimageembed)
    - [MakerDefaults](#makerdefaults)
    - [StudioCustomMasking](#studiocustommasking)
    - [Autosave](#autosave)
    - [EyeControl](#eyecontrol)
    - [AccessoryQuickRemove](#accessoryquickremove)
    - [DynamicBoneEditor](#dynamicboneeditor)
    - [AccessoryClothes](#accessoryclothes)
    - [LightingTweaks](#lightingtweaks)
    - [MoreOutfits](#moreoutfits)
    - [TwoLut](#twolut)
    - [AccessoriesToStudioItems](#accessoriestostudioitems)
    - [HairShadowColorControl](#hairshadowcolorcontrol)
    - [TimelineFlowControl](#timelineflowcontrol)
    - [StudioWindowResize](#studiowindowresize)
    - [ClothesToAccessories](#clothestoaccessories)
    - [Boop](#boop)
    - [ShaderSwapper](#shaderswapper)
    - [CharaMakerLoadedSound](#charamakerloadedsound)
    - [StudioSceneLoadedSound](#studiosceneloadedsound-1)
    - [ForceHighPoly](#forcehighpoly)
    - [ReloadCharaListOnChange](#reloadcharalistonchange)
    - [InvisibleBody](#invisiblebody-1)
    - [UncensorSelector](#uncensorselector-1)
  - [IllusionFixes](#illusionfixes)
  - [XUnity.AutoTranslator](#xunityautotranslator)
  - [KeelPlugins](#keelplugins)
    - [DefaultStudioScene \[KK\]\[AI\]\[HS2\]](#defaultstudioscene-kkaihs2)
    - [ItemLayerEdit \[KK\]\[KKS\]\[AI\]\[HS2\]](#itemlayeredit-kkkksaihs2)
    - [TitleShortcuts \[KK\]\[KKS\]\[AI\]\[HS\]\[HS2\]](#titleshortcuts-kkkksaihshs2)
  - [MakerJumpToSelectionPlugin](#makerjumptoselectionplugin)
  - [Illusion Overlay Mods](#illusion-overlay-mods)
  - [BepInEx Graphics Settings](#bepinex-graphics-settings)
  - [QuickAccessBox](#quickaccessbox)
  - [FPS counter](#fps-counter)
  - [HS2 Sandbox Plugin](#hs2-sandbox-plugin)
    - [CopyScript (HS2Sandbox.CopyScript.dll)](#copyscript-hs2sandboxcopyscriptdll)
    - [HS2 Sandbox — Timeline (HS2Sandbox.Timeline.dll)](#hs2-sandbox--timeline-hs2sandboxtimelinedll)
    - [HS2 Sandbox — SearchBarManager (HS2Sandbox.SearchBarManager.dll)](#hs2-sandbox--searchbarmanager-hs2sandboxsearchbarmanagerdll)
    - [HS2 Sandbox — Son scale (HS2Sandbox.SonScale.dll)](#hs2-sandbox--son-scale-hs2sandboxsonscaledll)
    - [HS2 Sandbox — Workspace tree lock (HS2Sandbox.WorkspaceTreeLock.dll)](#hs2-sandbox--workspace-tree-lock-hs2sandboxworkspacetreelockdll)
    - [HS2 Sandbox — Notebook (HS2Sandbox.Notebook.dll)](#hs2-sandbox--notebook-hs2sandboxnotebookdll)
    - [HS2 Sandbox — Pose Browser (HS2Sandbox.PoseBrowser.dll)](#hs2-sandbox--pose-browser-hs2sandboxposebrowserdll)
  - [HooahPlugins](#hooahplugins)
    - [Hooah Components](#hooah-components)
    - [Hooah Utility](#hooah-utility)
    - [Hooah Launch](#hooah-launch)
    - [Hooah Heelz](#hooah-heelz)
    - [Hooah Smug Face](#hooah-smug-face)
    - [Hooah Rand Mutation](#hooah-rand-mutation)
  - [KineMod](#kinemod)

---

## BepInEx

**Link:** https://github.com/BepInEx/BepInEx

BepInEx is a plugin / modding framework for Unity Mono, IL2CPP and .NET framework games (XNA, FNA, MonoGame, etc.)

---

## IllusionModdingAPI

https://github.com/IllusionMods/IllusionModdingAPI

This is an API designed to make writing plugins for recent UnityEngine games made by the company Illusion easier and less bug-prone. It abstracts away a lot of the complexity of hooking the game save/load logic, creating interface elements at runtime, and many other tasks. All this while supplying many useful methods and tools. Supported games:

---

## BepisPlugins

https://github.com/IllusionMods/BepisPlugins

A collection of essential BepInEx plugins for Koikatu / Koikatsu Party, EmotionCreators, AI-Shoujo / AI-Girl, HoneySelect2, HoneyCome, SamabakeScramble / Summer Vacation Scramble, Aicomi, AmanatsuLocation and other games by Illusion/Illgames. Check plugin descriptions below for a full list of included plugins.

### BGMLoader
Loads custom BGMs and clips played on game startup. Stock audio is replaced during runtime by custom clips from BepInEx\BGM and BepInEx\IntroClips directories.

Tutorial on how to replace sound clips and background music using BGMLoader.

### ExtensibleSaveFormat
Allows additional data to be saved to character, coordinate and scene cards. The cards are fully compatible with non-modded game, the additional data is lost in that case. This is used by sideloader to store used mod information.

### InputUnlocker
Allows user to input longer than normal values to InputFields. This allows longer names and other properties stored as text.

### Screencap / Screenshot Manager
Creates screenshots based on settings. Can create screenshots of much higher resolution than what the game is running at. It can make screen (F9 key) or character (F11 key) screenshots.

Screencap has a public API that can be used by other plugins to create screenshots or adjust the game screen as it is being captured (e.g. to disable effects that do not get captured correctly). Check the "Public API" region near the top of ScreenshotManager.cs.

### Sideloader
Loads mods packaged in .zip archives from the Mods directory without modifying the game files at all. You don't unzip them, just drag and drop to Mods folder in the game root.

It prevents mods from colliding with each other thanks to the UniversalAutoResolver subsystem (i.e. 2 mods have same item IDs and can't coexist; Sideloader automatically assigns correct IDs). It also makes it easy to disable/remove mods with no lasting effects on your game install (just remove the .zip, no game files are changed at any point).

### SliderUnlocker
Allows user to set values outside of the standard 0-100 range on all sliders in the editor.

---

## BepInEx ConfigurationManager

https://github.com/BepInEx/BepInEx.ConfigurationManager

An easy way to let user configure how a plugin behaves without the need to make your own GUI. The user can change any of the settings you expose, even keyboard shortcuts. The configuration manager can be accessed in-game by pressing the hotkey (by default F1). Hover over the setting names to see their descriptions, if any.

---

## HSPlugins

https://github.com/IllusionMods/HSPlugins

A collection of useful studio plugins.

---

## RuntimeUnityEditor

https://github.com/ManlyMarco/RuntimeUnityEditor

In-game inspector, editor and interactive console for applications made with Unity3D game engine. It's designed for debugging and modding Unity games, but can also be used as a universal trainer. Runs under BepInEx5, BepInEx6 IL2CPP and UMM.

**Features**
- Works on most games made in Unity 4.x or newer that use either the mono or IL2CPP runtime (currently IL2CPP support is in beta)
- Minimal impact on the game - no GameObjects or Components are spawned (outside of the plugin component loaded by the mod loader) and no hooks are used (except if requested for profiler)
- GameObject and component browser
- Object inspector (allows modifying values of objects in real time) with clipboard
- REPL C# console with autostart scripts
- Simple Profiler
- Object serialization/dumping
- dnSpy integration (navigate to member in dnSpy)
- Mouse inspect (find objects or UI elements by clicking with mouse)
- Gizmos (Transform origin, Renderer bounds, Collider area, etc.)
- All parts are integrated together (e.g. REPL console can access inspected object, inspector can focus objects on GameObject list, etc.)
- Right click on most objects to bring up a context menu with more options
- and many other...

---

## ABMX

https://github.com/ManlyMarco/ABMX

Plugin that adds more character customization settings to character maker of various games made by Illusion. These additional settings are saved inside the card and used by the main game and studio. It is possible to change male height, make good-looking thick necks, customize skirts, adjust hand and feet size and much more. 

---

## KK_Plugins (HS2)

https://github.com/IllusionMods/KK_Plugins

Plugins for Koikatu, Koikatsu Sunshine, EmotionCreators, AI Girl, HoneySelect2, and some other games.

### StudioSceneLoadedSound
Plays a sound when a Studio scene finishes loading or importing. Useful if you spend the load time for large scenes alt-tabbed.

### InvisibleBody
Set the Invisible Body toggle for a character in the character maker to hide the body. Any worn clothes or accessories will remain visible.

Select characters in the Studio workspace and Anim->Current State->Invisible Body to toggle them between invisible and visible. Any worn clothes or accessories and any attached studio items will remain visible. Invisible state saves and loads with the scene.

### UncensorSelector
Allows you to specify which uncensors individual characters use and removes the mosaic censor. Select an uncensor for your character in the character maker in the Body/General tab or specify a default uncensor to use in the plugin settings. The default uncensor will apply to any character that does not have one selected.

Requirements:
- Marco's KKAPI
- Marco's Overlay Mods
- BepisPlugins ExtensibleSaveFormat and Sideloader.

For makers of uncensors, see the template for how to configure your uncensor for UncensorSelector compatibility.

Make sure to remove any sideloader uncensors and replace your oo_base with a clean, unmodified one to prevent incompatibilities!

### Subtitles
For Koikatsu, adds subtitles for H scenes, spoken text in dialogues, and character maker.

### PoseTools
This plugin is aimed at increasing the usability of poses. You can create new folders in userdata/studio/pose and place the pose data inside them and those folders will show up in your list of poses in Studio. It also saves poses as .png files instead of .dat so you see can see what the content of the pose is. The list of poses is ordered by filename and the pose name is added to the file name so the list will be ordered alphabetically. It also saves skirt FK and facial expressions, though these can be disabled in plugin settings if you prefer.

Ported from Essu's NEOpose List Folders plugin for Honey Select.

### ListOverride
Allows you to override vanilla list files. Comes with some overrides that enable half off state for some vanilla pantyhose.

Overriding list files can allow you to do things like enable bras with some shirts which don't normally allow it, or skirts with some tops, etc. Any part of of the list can be changed except for ID.

### FreeHRandom
Adds buttons to Free H selection screen to get random characters for your H session.

### Colliders
Adds floor, breast, hand, and skirt colliders. Colliders can be toggled on and off in Studio and their state saves with the scene.

### MaterialEditor
MaterialEditor is a plugin that allows you to edit many properties of objects that aren't usually accessible in game. Much like Marco's clothing overlays you can replace the texture of an item, however with MaterialEditor you can edit much more than clothes. Edit clothes, accessories, hair, and even Studio items.

### MaleJuice
Enables juice textures for males in H scenes and Studio.

### StudioObjectMoveHotkeys
Allows you to move objects in studio using hotkeys. Press Y/U/I to move along the X/Y/Z axes. You can also use these keys for rotating and scaling, and when scaling you can also press T to scale all axes at once. Hotkeys can be configured in plugin settings.

### FKIK
Enables FK and IK at the same time. Pose characters in IK mode while still being able to adjust skirts, hair, and hands as if they were in FK mode.

### AnimationOverdrive
Type in to the animation speed box in Studio for gimmicks and character animations to go past the normal limit of 3.

### CharacterExport
Press Ctrl+E (configurable) to export all loaded character. Used for exporting characters from Studio scenes and such.

### StudioSceneSettings
Allows you to adjust a few more settings for scenes. Changes save and load with the scene data.

### Pushup
Provides sliders and setting to shape the breasts of characters when bras or tops are worn. The basic set of sliders will modify the shape of the breasts if the breast sliders are below the specified threshhold. Advanced mode lets you fully customize the shape of the breasts.

### PoseQuickLoad
A plugin that lets you load saved poses in Studio just by clicking on the pose. Vanilla behavior requires you to select the pose and then press the load button which can be pretty tedious if you have a lot of poses, especially since saved poses have no preview image.

Note: You MUST enable this option in the plugin settings (press F1 and search the plugin). This plugin is disabled by default so people don't accidentally load poses when they don't intend to, overwriting all their posing work. Use with caution.

### StudioImageEmbed
This plugin will save .png files from your userdata folder to the scene data so anyone else can load the scene properly without needing the same .png file.

### MakerDefaults
Allows you to set default settings of the character maker so you don't have to set the same values manually every time.

### StudioCustomMasking
Allows you to add map masking functionality for maps made out of items in Studio.

### Autosave
Automatically saves cards in the character maker and scenes in Studio every few minutes.

### EyeControl
Allows you to set a max eye openness, setting it to zero would let you create a character with permanently closed eyes. Can also disable a character's blinking.

### AccessoryQuickRemove
Quickly remove accessories by pressing the delete key in the character maker.

### DynamicBoneEditor
Edit properties of Dynamic Bones for accessories in the character maker.

### AccessoryClothes
Allows clothes to function in accessory slots.

### LightingTweaks
Increase shadow resolution for better quality and fix a shadow strength mismatch between main game and Studio.

### MoreOutfits
Allows characters to have more than the default number of outfit slots.

### TwoLut
Allows you to freely mix two studio shades (luts), instead of one always being set to Midday (based on plugin by essu). Also adds next/previous lut buttons next to the dropdown.

### AccessoriesToStudioItems
Plugin for studio that makes normal character accessories available as items. They are visible in the Item list and in QAB just like normal items. To see all accessories in QAB, search for ao_.

### HairShadowColorControl
Convenient controls for changing the shadow color of character hair in maker. Uses ME underneath.

### TimelineFlowControl
Adds simple logic to Timeline that allows for controlling playback, mostly to create limited animation loops. Requires the latest versions of BepInEx, Timeline and ModdingAPI.

### StudioWindowResize
Makes studio selection windows (e.g. item and animation lists) larger so more items are visible. The size is configurable in plugin settings.

### ClothesToAccessories
Allows using normal clothes and hair as accessories. New accessory types are added to the Type dropdown list. Body masks from normal top clothes will be used if available, otherwise masks from top clothes added as accessories will be used.

### Boop
Boop the character by moving mouse over parts of their body, hair and clothes. Upgraded version of the original Boop by essu.

### ShaderSwapper 
By default, swap all shaders to the equivalent Vanilla Plus shader in the character maker or studio by pressing right ctrl + P.

Custom rules for swapping shaders can be provided in xml files. Check the "Mapping" category in plugin's settings. Optional premade XML configurations are included for swapping to Az Standard, USS, and UTS shaders.

> [!CAUTION]
> Probable incompatibility with Hanmen's version (?)

### CharaMakerLoadedSound

Plays a sound when the Chara Maker finishes loading. Useful if you spend the load time alt-tabbed.

### StudioSceneLoadedSound

Plays a sound when a Studio scene finishes loading or importing. Useful if you spend the load time for large scenes alt-tabbed.

### ForceHighPoly

Forces all characters to load in high poly mode, even in the school exploration mode.

### ReloadCharaListOnChange

Reloads the list of characters and coordinates in the character maker when any card is added or removed from the folders. Supports adding and removing large numbers of cards at once.

### InvisibleBody

Set the Invisible Body toggle for a character in the character maker to hide the body. Any worn clothes or accessories will remain visible.

Select characters in the Studio workspace and Anim->Current State->Invisible Body to toggle them between invisible and visible. Any worn clothes or accessories and any attached studio items will remain visible. Invisible state saves and loads with the scene.

### UncensorSelector

Allows you to specify which uncensors individual characters use and removes the mosaic censor. Select an uncensor for your character in the character maker in the Body/General tab or specify a default uncensor to use in the plugin settings. The default uncensor will apply to any character that does not have one selected.

---

## IllusionFixes

https://github.com/IllusionMods/IllusionFixes

A collection of fixes for common issues found in Koikatu, Koikatsu Party, EmotionCreators, AI Girl and HoneySelect2

---

## XUnity.AutoTranslator

https://github.com/bbepis/XUnity.AutoTranslator

This is an advanced translator plugin that can be used to translate Unity-based games automatically and also provides the tools required to translate games manually.

It does (obviously) go to the internet, in order to provide the automated translation, so if you are not comfortable with that, don't use it.

If you intend on redistributing this plugin as part of a translation suite for a game, please read this section and the section regarding manual translations so you understand how the plugin operates.

---

## KeelPlugins

https://github.com/IllusionMods/KeelPlugins

Various plugins for Illusion's Unity games like Koikatu, Honey Select, PlayHome and AI Syoujyo.
Not all of these plugins exist or are even possible to make for all of the games.
Configuration Manager is recommended to make changing the numerous settings from these plugins easier.

**Selection of HS2 Plugins**

### DefaultStudioScene [KK][AI][HS2]
Load the scene specified in the config automatically when starting studio.

### ItemLayerEdit [KK][KKS][AI][HS2]
Adds a hotkey that switches the currently selected objects layer between the character layer and the map layer.
This allows for more in-depth editing of lighting in studio.

### TitleShortcuts [KK][KKS][AI][HS][HS2]
Title menu keyboard shortcuts to open different modes.
For example, press F to open the female editor.

---

## MakerJumpToSelectionPlugin

https://github.com/OrangeSpork/MakerJumpToSelectionPlugin

Adds a button to the various maker panels to jump the selection scroll windows to the position of the selected item. It's the little down triangle next to the X close button. Most windows have it to the left of the X, but some windows have that spot taken so it's just under instead.

---

## Illusion Overlay Mods

https://github.com/elusivecake/Illusion-Overlay-Mods

Plugin that allows adding overlay textures (tattoos) to character's face, body and clothes in games made by Illusion. This lets you create unique characters and clothes easily without needing to make mods for the game. These additional textures are saved inside the card and used by the main game and studio. Previously named Koikatsu Overlay Mods and KSOX (KoiSkinOverlayX) + KCOX (KoiClothesOverlayX).

---

## BepInEx Graphics Settings

https://github.com/BepInEx/BepInEx.GraphicsSettings

Exposes unity's graphics settings and some other values for editing in ConfigurationManager.

---

## QuickAccessBox

https://github.com/ManlyMarco/QuickAccessBox

Plugin for Koikatu / Koikatsu Party and AI-Shoujo / AI-Girl studio that adds a quick access list for searching through all of the items, both stock and modded. The plugin comes with thumbnails for the items, unlike the original studio interface. It's also instant and has low resource footprint, no need to wait for menus to open.

---

## FPS counter

https://github.com/ManlyMarco/FPSCounter

A BepInEx plugin that measures many performance statistics of Unity engine games. It can be used to help determine causes of performance drops and other issues.

---

## HS2 Sandbox Plugin

https://github.com/SuitIThub/HS2-Sandbox#requirements

BepInEx plugins for Honey Select 2, Koikatsu Sunshine, and Koikatsu that add quality-of-life tools to StudioNeoV2 / Chara Studio: automation helpers, pose and animation libraries, notes, search bars on long lists, and finer control over character scaling.

Install the individual modules you want. After installation, most tools appear as buttons on the Studio left sidebar; open a window from there and work as usual in Studio.

### CopyScript (HS2Sandbox.CopyScript.dll)

Connects Studio to an external CopyScript service on your PC. From the CopyScript Control window you can work with tracked files, counters, lists, and batch rules without leaving the game.

Typical use: run your CopyScript server, open the window from the sidebar, and point it at the correct host/port. If nothing connects, check firewall settings and that the server is actually running.

> [!NOTE]
> Version r2026-07-04: the sidebar button is missing a proper icon or just fails to load it. Just a blank button is shown, but it works.

### HS2 Sandbox — Timeline (HS2Sandbox.Timeline.dll)

An action timeline for Studio: ordered steps (waits, screenshots, Studio actions, CopyScript calls, variables, and more), with run / pause / stop. Handy for repeatable scene setup or light automation.

Many timeline commands that talk to other plugins (for example VNGE, FashionLine, or similar) expect a modified build of that plugin with extra hooks or APIs exposed. Those manipulated versions are not included in this repository—you need to obtain and install them separately if you use those commands.

Typical use: build a timeline in the window, then play it when you want the sequence to run. Stick to Studio-native steps unless you already have the matching modified plugins installed.

### HS2 Sandbox — SearchBarManager (HS2Sandbox.SearchBarManager.dll)

Adds search fields on long Studio lists (for example wear/custom categories) so you can filter items quickly instead of scrolling forever.

Typical use: install this module when you want search bars. There is no separate sidebar button—the bars appear on the panels they attach to.

### HS2 Sandbox — Son scale (HS2Sandbox.SonScale.dll)

Separate sliders for overall size, length, and girth on the selected character’s Son (member), under Manipulate → Chara → State. Works with or without Studio Better Penetration; with BP installed, length scaling integrates more cleanly.

Typical use: select a character in the workspace, open Son scale from the sidebar, enable split scaling, then adjust sliders in the Manipulate panel.

### HS2 Sandbox — Workspace tree lock (HS2Sandbox.WorkspaceTreeLock.dll)

In the Studio object list, middle-click a nested row to pin it. Pinned rows stay visible when you collapse parent groups (they get a cyan border). Middle-click again to unpin.

Typical use: pin deep items you need to reach often so collapsing the tree does not hide them.

### HS2 Sandbox — Notebook (HS2Sandbox.Notebook.dll)

A simple in-game notepad for ideas, shot lists, and reminders—opened from the sidebar. Notes are saved automatically to BepInEx/config/com.hs2.sandbox/notebook.json and restored the next time you start Studio.

Typical use: keep the window open while you work; edits are debounced to disk (~0.5s) and flushed when you close the window or exit the game.

### HS2 Sandbox — Pose Browser (HS2Sandbox.PoseBrowser.dll)

Browse, tag, favorite, save, and apply poses from your UserData/studio/pose folder. Folder tree, thumbnails, search, and file operations (move, copy, delete with backup) from one window.

Typical use: open from the sidebar, pick a folder, filter or tag poses, apply to selected characters. Optional HS2Wiki adds extra help on F3 when installed. More detail: docs/PoseBrowser-HS2Wiki-Manual.md.

---

## HooahPlugins

https://github.com/HooahPlugins/HooahPlugins

### Hooah Components
Extended studio items

### Hooah Utility
Common utilities for all plugins

### Hooah Launch
Fast search actions and items

### Hooah Heelz
Add heels. about to get more stable integration between abmx and heelz.

### Hooah Smug Face
Add faces

### Hooah Rand Mutation
Adds ability to mix and randomize character sliders and ABMX modifiers. Also you can use this as lightweight character slider save format.

---

## KineMod

https://github.com/krypto5863/Illusion.KineMod

A simple plugin meant mostly for us IK users who have noticed there's a painful lack of control over certain body parts that FK has.

IK can now work with FK.
Toggle individual FK bones such as clavicle, toes, etc,.
Easy to use control over the IK effectors.
SOON: MotionTimeline Support

**IK & FK?**

FK does not play nice with IK, using FK will render IK useless. This is because FK makes it's pose changes after IK has solved the pose. The result is IK is basically overwritten. To solve this, I patched the FK controller to force it to change the pose before IK has read the pose, allowing both to work perfectly, though FK does now have deference to IK.

However, if you made scenes or poses that have IK on but really poses with FK, you may find they're mangled. Simply disable IK and they'll be back to normal.

**Effectors?**

Effectors control the effect an IK target has over the pose. When you set all effectors to 1, you basically pin the joint to the IK target. This is unfortunate because FinalIK is very advanced and can sometimes pose better than you can if you let it, since it has it's own defined joint angle limits. A pose that might take you several minutes, could take you less if you loosen your effectors and just move the one you want, allowing the body to follow the joint's movement. Below is an example of the pulling effect you can achieve when you just let the hand effector influence the pose.

> [!IMPORTANT]
> Incompatible with FKIK from KK Plugins. Backup and remove it: (BepInEx\Plugins\HS2_Plugins\HS2_FKIK.dll)

---

Meina Plugin  ???











