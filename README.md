# SPORE MODS!
Various releases for Spore mods, most of which will be sporemod files requiring the [Spore Mod API](https://launcherkit.sporecommunity.com/).

<br>

## Current mods
### BetterCrashReports
Popup windows on crashes to help diagnose problems.

Press CTRL+SHIFT+F10 if the game has hung, it may be able to find some useful information for you!

Crash signatures are created, it might help categorise crashes in the future and help people with similar issues!

The mod works by keeping a rolling log which is shared to a lightweight process that remains running after Spore exists. When the game crashes, the reporter displays the log information.

<br>

### CreaturePartOpacity
Tools to decrease the opacity of parts, limbs and the body between 0% and 100%. 

"Creature" is somewhat misleading of a name because it works on buildings, vehicles and outfitters too! 

Heavily designed to be used alongside [Advanced Creature Paint](https://github.com/emd4600/advanced-creature-paint) as it provides a new opacity slider when clicking parts. Alternatively, select a part, limb or body, then use numpad / and * to increment & decrement opacity by 10%.

When used with Advanced Creature Paint, if you just want to change the opacity and NOT paint the part, use the no paint button.

**This should be share safe!**

The mod works by storing opacity information within creatures, akin to Advanced Creature Paint. These opacities are then loaded with some alpha blending magic, which probably could have been done better!!

<br>

### CreatureShareSafety
Finds share issues before they become a problem, introducing a share state button to the left of the save button.

**This does not prevent saving**, it's designed to show the share status of a creature whilst you're building it.

The mod works by comparing the creature against part definitions, paints, part limits, and other factors that may affect sharing. Green is goood, red is bad!

<br>

### EditorPanStability
Reduces snapping when using EditorEnablePanning, which is automatically turned on.

This pairs very nicely with [Valla's camera fixes](https://github.com/Valla-Chan/Spore-Mods/releases/tag/SporeEditorCameraFix), it actually exists to enhance this mod!

The mod works by preserving horizontal and vertical positions during calls which attempt to reset them. These resets may still happen, but on my end, they're incredibly rare now.

<br>

## Credits & Notices
- [emd4600](https://github.com/emd4600/)'s Advanced Creature Paint was incredibly insightful for learning modding as well as storing data against creatures.
- AI was used throughout these mods to assist with my understanding and development. These mods were built to solve problems I encountered myself, rather than with the intention of public release, so bugs may be encountered! I figured others might appreciate the same solutions :]
