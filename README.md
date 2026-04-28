# Midi2Building v0.9

A tool for making a plugin timing a MIDI file to the construction of a Minecraft build.

## Usage

1. Gather a [midi](https://slatedigital.com/what-is-midi/) file. This tool was designed for drum midi files. Melodic instruments will take more finagling.
2. Gather a [structure .nbt](https://minecraft.wiki/w/Structure_file) file.
3. Compile and run `src/main/java/me/melonboy10/midi2building/Main.java`
4. Click on the crafting table to select a midi file (currently broken on mac)
5. Select a block for as many notes as you want (ie. C2 is wood plank). The program will tell you how many of each note the midi file has.
6. Click on the structure block to select a structure file. The program will tell you how many of each block exist in the structure file.
7. Click the lever to generate the output file.
8. Move the generated `.mcmeta` file to your world file.
9. Run the `/load` command in your world.

### Current bugs
* The midi load window doesn't work on Mac.

### Requested Features
* Make some smart way to control the order of the blocks placed.

## Contributing

If you want to contribute, wonderful! Please see `Contributing.md`. If you want to see more of the technical side of things, take a peak in there, too. Most of the technical work has been confined there.

