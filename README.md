# ssft19-sparrow

This is a slightly modified, older version of sparrow so that it can be built on the ssft19-vm and used for the lab session. (Ubuntu 16.04, Opam 1.2.2, etc.) For the original & live version, please refer to https://github.com/ropas/sparrow.

## Build
On your vm,

```sh
$ git clone https://github.com/ropas/ssft19-sparrow
$ cd ssft19-sparrow
$ ./build.sh
$ eval `opam config env`
$ make
```
## Run
You can run Sparrow for buffer overflow detection on pre-processed C files. For example:
```sh
$ ./bin/sparrow test/test.i
```
