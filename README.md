# aria2c1k
[aria2](https://aria2.github.io/) concurrent connection limit lifted, since [tatsuhiro rejected the propose](https://github.com/aria2/aria2/issues/729)

The patch file is the only thing necessary.

Steps:
./download.sh
./build-dep.sh
./build.sh

The binary will be under ../aria2-1.36.0/src/aria2c
