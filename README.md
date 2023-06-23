# DMDReader

This is a repository just to collect documentation and links to all kinds of projects around the DMDReader

## Software

The software consist of several parts:

- [DMDReader](https://github.com/pinballpower/code_dmdreader) The software that runs on a Raspberry Pi and deals with high-level processing the DMD frames (and much more). It includes features like colorisation, PUP playback, triggers and more
- [DMDReader Pico](https://github.com/pinballpower/code_dmd) The low-level firmware for the RP2040 that deals with the DMD interface. It reads data from the 14-pin DMD interface and sends it to rthe Raspberry Pi for further processing.
- [PinballOS](https://github.com/pinballpower/pbos) A minimal Linux distribuition for the Raspberry Pi that just includes everything to use the DMDReader software. For software development, it is recommended to use use Raspberry Pi OS. However, if you're looking for a small distribution just to run rthe software PinballOS is the choice.

## Hardware

- [αDMD](https://github.com/pinballpower/alpha_dmd) A 128x32 DMD that is based on DMDReader
