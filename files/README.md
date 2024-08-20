# The File Section
Here you can access all finished articles on file formats and files that can aid you in better understanding these games' inner workings.

- [Game data archives](./arc.md)

- [monsterIDs](./monsterIDs.md)

- [BodyColorData](./BodyColorData.md)

- [Dialogue Script](./script.md)

## FILE FORMATS
### PCTXBIN
Procedural Texture Files, these are used to generate new
textures on the fly and are used by the game for clouds, lava,
fire, the sea, and thunder. There is no tool that can edit these

### SHBIN
SHader BINary, these files contain shader programs. Documentation
can be found at http://3dbrew.org/wiki/SHBIN and a tool to edit them
can be found at https://github.com/neobrain/nihstro

### BCSTM
Streamed Audio File, these files contain streamed audio for the
game such as music, voice lines, etc. Documentation can be found at
https://www.3dbrew.org/wiki/BCSTM and a tool that can convert to/from
this format can be found at https://github.com/libertyernie/LoopingAudioConverter

### BRSAR
Streamed Audio File, these files normally contain the sound effects
for a game. Documentation can be found at https://www.3dbrew.org/wiki/BCSAR
and tools to edit them can be found at https://gota7.github.io/Citric-Composer/

### BCMDL
Container for model, texture, animations, and camera data, TDM3 seems to 
only use these for Battle Effects and Status Effects. Many of these files are 
prone to crashing Model Viewers but some will open in Ohana Rebirth/SPICA/Switch Toolbox
Documentation can be found at https://www.3dbrew.org/wiki/CGFX

### BCLIM
Texture image, usually used for 2d elements, can be converted to/from with
https://github.com/kwsch/png2bclim

### BCLYT
Layout Format, used to create screen elements. Documentation can be found at
https://www.3dbrew.org/wiki/CLYT_format EveryFileExplorer can view these, you might
be able to edit these with https://github.com/pleonex/Clypo

### CGF
Equivalent to BCMDL along with its stability, some can be opened by the Model Viewer
trio but most of the time they will crash them.

### BCH
The main model format used by the game. These files contain most of the major models
for the game and the Model Viewer trio can view and extract these easily.

### GSMB
GMSG files that contain the text for the game, Kuriimu is the primary tool that can
open these kinds of files, but for whatever reason it fails to open the ones from TDM3.
Hex editing these files is possible as long as you keep your custom message around the
same length as the original.

### ARC
Standard Archive format, can be opened by EveryFileExplorer.

### DAR
Standard Archive format, documentation can be found at https://3dbrew.org/wiki/DARC
can be opened by EveryFileExplorer. Usually used to contain HUD elements in the BCLYT and
BCLIM Format.

### DAT
Proprietary Format for TDM3, commonly used to contain BCH models that consist of map parts.
Might also be used for other kinds of files.

### ZIP
Standard ZIP file, you can easily open these on any OS. They sometimes appear to contain
certain files(Mostly GSMB files).
