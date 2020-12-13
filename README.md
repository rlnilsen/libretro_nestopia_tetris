# libretro_nestopia_tetris

Modification of the Nestopia libretro core specifically for use with NES Tetris. A snapshot of the screen (in form of a nametable dump) will be saved in folder 'C:\nestetris\' at every Tetris game start and game over. Use in conjunction with [chewie](https://github.com/rlnilsen/chewie) to automatically generate a text file with data from your NES Tetris games.

## How to install

1. Download zip file from [Releases](https://github.com/rlnilsen/libretro_nestopia_tetris/releases).
2. Extract 'nestopia_tetris_libretro.dll' to your RetroArch 'cores' folder.
3. Extract 'nestopia_tetris_libretro.dll' to your RetroArch 'info' folder.
4. Create folder 'C:\nestetris\'.
5. Start RetroArch and play NES Tetris using the 'Nestopia Tetris' core.
6. Use [chewie](https://github.com/rlnilsen/chewie) to process the generated files in 'C:\nestetris\'.
