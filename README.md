# ncmpcpp-icat

![ncmpcpp-icat](img/demo.gif)

`ncmpcpp-icat` displays ncmpcpp album art using the [Kitty](https://github.com/kovidgoyal/kitty) terminal's [icat kitten](https://sw.kovidgoyal.net/kitty/kittens/icat/). This is based off of tom-carre's [ncmpcpp-ueberzug](https://github.com/tam-carre/ncmpcpp-ueberzug), which I slightly modified because ueberzug does not work on Wayland. 

## Install

Dependencies:

- kitty
- ncmpcpp
- mpc
- ffmpeg

Follow the instructions on the [Setup](https://github.com/alnj/ncmpcpp-ueberzug/wiki/Setup) wiki page.

Check out [sacad](https://github.com/desbma/sacad) if you want to automatically download cover art for your music library.

## Compatibility

#### Working:
* `kitty` (might use wrong terminal if using `--single-instance` flag)

## TODO & Known Issues

* Auto resizing causes crashing so it is temporarily disabled
* I have not thoroughly tested everything out so there may be some more bugs
