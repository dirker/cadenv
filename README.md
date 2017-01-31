# CADENV

Simple as it gets software package version manager for Unix (Linux).

Quick current feature overview:
  * Support packacke repo via $CADENV_ROOT
  * Allow to select per-shell package version via
    $CADENV_PACKAGE_<name>="<version>", where name is an
    uppercase package name

An example package repo layout can be seen in the test directory.

Test via:
```
$ CADENV_ROOT=test ./bin/cadenv rehash
$ export CADENV_PACKACKAGE_ARMRVDS=4.1b867
$ CADENV_ROOT=test ./test/bin/armcc
```
