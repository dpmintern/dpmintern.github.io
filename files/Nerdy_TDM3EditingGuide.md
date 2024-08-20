THE DENPA MEN 3: RISE OF DIGITOLL EDITING GUIDE
===================================================================

## INTRODUCTION:
This guide assumes you have already procured a CIA of DPM3 onto your computer and dumped its romfs either through Citra, or manually.

There are a number of guides on the internet to help you with this if you haven't yet done so.

At the current moment, DPM3 has a number of files that can be edited and some that cannot. With current tools, you can extract and view all of these files either with a hex editor or certain tools.

This guide may or may not be applicable to previous games (DPM & DPM2) or DPMF. This guide is made primarily for DPM3.

> **NOTE**: Some of these tools may be Windows only, if you are on Linux or macOS, try using WINE to run these programs or find alternatives.

> **NOTE**: This guide is not actively maintained. The community may have developed better practices not yet in the document.

## REQUIRED TOOLS
- QUICKBMS & TDM3 Extract Script: Supports Windows/Linux, used to extract
data from the extensionless archives. QuickBms can be found at
http://aluigi.altervista.org/quickbms.htm while the extract script
can be found within the "The Denpa Men" Discord Server.

- Ohana Rebirth/SPICA/Switch Toolbox: Supports Windows, can view and extract
BCH and CGF models. Links to Ohana Rebirth and SPICA can be found at 
https://wiki.vg-resource.com/CGFX while Switch Toolbox can be found at
https://github.com/KillzXGaming/Switch-Toolbox

- EveryFileExplorer: Supports Windows, can view and extract data from ARC
and DARC files. Download can be found at https://gbatemp.net/threads/release-every-file-explorer.373615/
Make sure to unblock the contents of the zip before extracting

- A HEX EDITOR: A hex editor is useful for the rest of the files that either
don't have a tool to open them or aren't understood, there are a wide variety
of hex editors for all platforms so ask around for recommendations.

## FAQ
### Q: How do I extract from the extensionless files?
A: Either run QuickBMS from the commandline or launch the exe and follow the instructions.

### Q: How do I repack back into an extensionless file?
A: This is not yet possible, you may be able to use QuickBMS's reimport feature to replace a file
with a replacement of the same or smaller size. More documentation on the archive format is needed
before a proper repacker can be made.

### Q: How do I test my edited files?
A: The easiest method if you have a powerful enough computer is to use Citra, details can be found here
https://citra-emu.org/help/feature/game-modding/ Otherwise you will need to figure out how to use layeredFS
on hardware.

## Significant Archives

0E820000 -> World Map Models

F5AD0000 -> World Map Texture + Cannon HUD

1D1A0000 -> NPC Models

F9270000 -> Main Island Buildings

E1580000 -> Jump Menu HUD

83B80000 -> Item Textures + Menu Command Text Script

D4270000 -> Furniture Models

28480000 -> Enemy Models

F48B0000 -> Denpa Men Animations

D1210000 -> Clear Text Model + Animation

00910000 -> Catch Denpa Men Mode HUD, Script Text, and Models

A4070000 -> Battle Effects

F8D10000 -> Battle Effects Cont.
