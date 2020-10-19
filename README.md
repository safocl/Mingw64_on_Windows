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

You need to set the PATH variable in the environment variable settings by adding '[path to msys2 installation folder]/mingw64' to detecting the compiler by other programs.
