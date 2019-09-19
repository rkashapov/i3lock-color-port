# i3lock-color port for FreeBSD

This repository contans a port of [i3lock-color](https://github.com/PandorasFox/i3lock-color) for FreeBSD

## Build
Be sure you have the ports tree on your machine. If not, run the following commands:

``` shell
# portsnap fetch
# portsnap extract
```

Clone this repository with git command and build/install vs code:

``` shell
git clone https://github.com/rkashapov/i3lock-color-port
cd i3lock-color-port/x11/i3lock-color
make install clean
```

## Platform
- The port tested on FreeBSD 12 amd64.
