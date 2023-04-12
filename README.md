<img align="right" alt="The ctrmus icon" src="meta/icon.png">

# Phonograph3DS is a music player for the Nintendo 3DS (fork of ctrmus)


## Features
* Plays PCM WAV, AIFF, FLAC, Opus, Vorbis and MP3 files.
* Pause and play support.
* Plays music via headphones whilst system is closed.
* Ability to browse directories.

## Controls
L+R or L+Up: Pause

L+B: Stop

L+Left: Show Controls

A: Play file or change to selected directory

B: Go up folder

Up & down = Move cursor

Left & right = Move cursor skipping 13 files at a time.

Start: Exit


## Compiling

Build dependencies:
- GNU Make
- [makerom](https://github.com/3DSGuy/Project_CTR)
- [bannertool](https://github.com/Steveice10/bannertool)
- [devkitARM](https://devkitpro.org/wiki/Getting_Started), with the following packages installed:
  - libctru
  - 3ds-libmpg123
  - 3ds-libopus
  - 3ds-libopusfile
  - 3ds-libogg
  - 3ds-libvorbisidec
  - 3ds-libsidplay

To build, type `make` in the project folder.

### Planned features
[ ] Graphic UI
[ ] Playlist support.
[ ] Repeat and shuffle support.
[ ] Metadata support.

#### Notes
Due to limitations in [ctrulib](https://github.com/smealum/ctrulib/issues/328), only ASCII characters are displayed correctly. Other characters will appear garbled, but functionality is not affected.

Banner music uses a modified version of ["Rad Adventure" by Scott Holmes](http://freemusicarchive.org/music/Scott_Holmes/).
