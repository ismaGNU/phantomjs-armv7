## PhantomJS Linux Armv7

PhantomJS 2.0.1, compiled on Debian Jessie.

Note: Due to a change on libjpeg this binary may not work on an older Debian based distro.

### Devices tested
- Raspberry PI 2 (Raspbian "jessie").
- Bq Aquaris E5

### Dependencies
If you find that the binary throws any exception like "error while loading shared libraries ...". You need to install the following dependencies.

For Debian-based distros:

`sudo apt-get install libfontconfig1-dev libicu-dev libfreetype6 libssl-dev libpng-dev libjpeg-dev libX11-dev libxext-dev`


