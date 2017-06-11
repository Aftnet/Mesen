Mesen is a cross-platform NES/Famicom emulator for Windows & Linux built in C++ and C#.

If you want to support this project, please consider making a donation:  
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=W97QP2LYC9H4W"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" title="Donate to this project using Paypal" alt="Donate to this project using Paypal"/></a>

[Website (https://www.mesen.ca)](https://www.mesen.ca)

# Releases #

### Windows ###

The latest version is available on the [website](https://www.mesen.ca).  Older releases are available from the [releases tab on GitHub](https://github.com/SourMesen/Mesen/releases).

### Ubuntu ###
The official releases (same downloads as the Windows builds above) also contain the Linux version of Mesen, built under Ubuntu 16 - you should be able to use that in most cases if you are using Ubuntu.  

The Linux version is a standard .NET executable file and requires Mono to run - you may need to configure your environment to allow it to automatically run .exe files through Mono, or manually run Mesen by using mono (e.g: "mono Mesen.exe").  

The following packages need to be installed to run Mesen:
* mono-complete
* libsdl2-2.0
* gnome-themes-standard

### Arch Linux ###  
Packages are available here: https://aur.archlinux.org/packages/mesen

# Roadmap #
Things that ***may or may not*** be added in the future, in no particular order:

-Support for more UNIF boards and more NES/Famicom input devices  
-Debugger improvements (APU state display, scripting, etc.)  
-Shaders  
-Improvements to movie file format to support a few things that currently do not work  
-Libretro support  
-TAS editor  

# Compiling #

### Windows ###
1) Open the solution in VS2015/2017
2) Compile as Release/x64 or Release/x86  
3) Run  

### Linux ###

To compile and run Mesen under Linux, you will need:
* A recent version of clang/gcc
* Mono 4.2.1+  (package: mono-devel)
* SDL2  (package: libsdl2-dev)

The makefile contains some more information at the top.  Running "make" will build the x64 version by default, and then "make run" should start the emulator.  


## LICENSE ##

Mesen is available under the GPL V3 license.  Full text here: http://www.gnu.org/licenses/gpl-3.0.en.html

Copyright (C) 2017 M. Bibaud


This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
