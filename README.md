# Installing Mingw-w64-x86_64 on Windows


### With msys2:
goto https://www.msys2.org/ and download installer.
run installer and install msys2.

### then run msys2 shell and type that commands:
```bash
$ pacman -Syu
```
close MSYS2, run it again, then type:
```bash
$ pacman -Su
$ pacman -S mingw-w64-x86_64-toolchain mingw-w64-x86_64-cmake
```
the required components are now installed.
you need to run mingw64 or create a shortcut to the desktop.

you need set the PATH variable in settings environment variables be adding '[path to msys2 install folder]/mingw64' for detect the compiler by other programs.
