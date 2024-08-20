# The File Section
Here you can access all finished articles on file formats and files that can aid you in better understanding these games' inner workings.

- [.arc (Game data archives)](./arc.md)

- [.bin (Dataset)](./Dataset.md)

- [.dat (Dialogue Script)](./script.md)

- [.PCTXBIN]()
Procedural Texture Files, these are used to generate new
textures on the fly and are used by the game for clouds, lava,
fire, the sea, and thunder. There is no tool that can edit these

-  [.SHBIN](http://3dbrew.org/wiki/SHBIN)
SHader BINary, these files contain shader programs. Tooling to edit them
can be found at https://github.com/neobrain/nihstro

- [.BCSTM](https://www.3dbrew.org/wiki/BCSTM)
Streamed Audio File, these files contain streamed audio for the
game such as music, voice lines, etc. A tool that can convert to/from
this format can be found at https://github.com/libertyernie/LoopingAudioConverter

- [.BRSAR](https://www.3dbrew.org/wiki/BCSAR)
Streamed Audio File, these files normally contain the sound effects
for a game. Tools to edit them can be found at https://gota7.github.io/Citric-Composer/

- [.BCMDL](https://www.3dbrew.org/wiki/CGFX)
Container for model, texture, animations, and camera data, TDM3 seems to 
only use these for Battle Effects and Status Effects. Many of these files are 
prone to crashing Model Viewers but some will open in Ohana Rebirth/SPICA/Switch Toolbox

- [.BCLIM]()
Texture image, usually used for 2d elements, can be converted to/from with
https://github.com/kwsch/png2bclim

- [.BCLYT](https://www.3dbrew.org/wiki/CLYT_format)
Layout Format, used to create screen elements. EveryFileExplorer can view these, you might be able to edit these with https://github.com/pleonex/Clypo

- [.CGF]()
Equivalent to BCMDL along with its stability, some can be opened by the Model Viewer
trio but most of the time they will crash them.

- [.BCH]()
The main model format used by the game. These files contain most of the major models
for the game and the Model Viewer trio can view and extract these easily.

- [.GSMB]()
GMSG files that contain the text for the game, Kuriimu is the primary tool that can
open these kinds of files, but for whatever reason it fails to open the ones from TDM3.
Hex editing these files is possible as long as you keep your custom message around the
same length as the original.

- [.arc (SARC)]()
Standard Archive format, can be opened by EveryFileExplorer.

- [.DAR](https://3dbrew.org/wiki/DARC)
Standard Archive format, can be opened by EveryFileExplorer. Usually used to contain HUD elements in the BCLYT and
BCLIM Format.

- [.DAT]()
Proprietary Format for DPM3, commonly used to contain BCH models that consist of map parts.
Might also be used for other kinds of files.

- [.ZIP]()
Standard ZIP file, you can easily open these on any OS. They sometimes appear to contain
certain files(Mostly GSMB files).
