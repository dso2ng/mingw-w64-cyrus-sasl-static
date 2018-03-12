# MingW-W64-cyrus-sasl-static

This is a copy from sub directory **cyrus-sasl** below the [Alexpux/MINGW-packages](https://github.com/Alexpux/MINGW-packages). The difference is trying to add static build in the configuration.

#### building the package ####
```
MINGW_INSTALLS=mingw32 makepkg-mingw -sCLf
```
Note that this should be down under the MSYS2 shell.