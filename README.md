# NeedleScratch
This is a project to teach myself how to use TensorFlow and ML. It is inspired by a writeup I saw on the VinylEmulator project

https://www.hackster.io/mark-hank/sonos-spotify-vinyl-emulator-3be63d

The end goal is to be able to show an album cover to a camera, have it recognize the album, and begin playing it.

## Platform
As a hardware platform, I'm using a Raspberry Pi 4 (4 GB RAM) with a Coral USB Accelerator and a USB camera for the image processing.

To play the music, I'm using a Raspberry Pi 3 with an ALLO Boss DAC running Volumio with local FLAC files for music.  Theoretically, I could combine these into a single system, but separation allows me to be more flexible with where I put stuff in my house.

https://coral.ai/products/accelerator

https://www.amazon.com/Allo-C1021-Boss-DAC/dp/B07191SYFH

https://volumio.org

