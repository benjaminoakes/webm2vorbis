# webm2vorbis

Extract Ogg Vorbis audio from a WebM file.  It's a simple droplet.  You drop WebM files on it, and Ogg Vorbis files are created in the same directory as the WebM file.

## Installation

    sudo make install

Also, you might copy `application/*.desktop` to someplace you like to keep droplets, e.g. `~/Desktop/Droplets`.

This isn't a proper package (yet), so you'll need `ffmpeg` too.  On Ubuntu:

    sudo apt-get install ffmpeg
