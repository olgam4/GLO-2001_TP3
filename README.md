# TP3
File system for UNIX

## Requirements
* [libfuse-dev](https://packages.debian.org/sid/libfuse-dev)

### How to run on linux
```
mkdir /tmp/glo
make clean
make ufs
make glofs
mkdir /tmp/glo
./glofs /tmp/glo -f -ouse_ino
```

## Authors
* Olivier Gamache
* Édouard Carré

## Thanks to
* François Pomerleau
* Philippe Giguère
