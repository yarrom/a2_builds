# Binary builds of A2 Operating System

**A2 Operating System ([A2 OS home](http://a2.inf.ethz.ch/) | [A2 OS community in Telegram](https://t.me/A2OperatingSystem )) – former AOS (Active Objects System) / Bluebottle OS, modular Operating System written on high level Active Oberon programming language with a few amount of assembly code. A2 OS may run on the bare hardware (Intel x86 / AMD x64 / ARM) or as an application under Win / Linux / macOS.** 

**Active Oberon programming language ([ETH Oberon (2019) Language Report](http://cas.inf.ethz.ch/projects/a2/repository/raw/trunk/LanguageReport/OberonLanguageReport.pdf)) – result of evolution of Oberon programming language, that encapsulates multithreading and synchronization primitives by utilizing the concept of Active Objects and Exclusive / Await blocks respectively. Active Oberon programming language includes such modern features as operator overloading, generics and mathematical matrix extensions.**


# Legend

**A2_(x86|x64)_rev_XXXXX.7z** – Full A2 bootable ISO image (Live-CD).

**A2HDD_(x86|x64)_rev_XXXXX.7z** – Full A2 bootable HDD image.

**A2USB_(x86|x64)_rev_XXXXX.7z** – Full A2 bootable USB image.

**A2mini_(x86|x64)_rev_XXXXX.7z** – Mini A2 bootable ISO image. A2 Operating System image with minimal amount of applications and without contributed code. Despite the minimum size this build includes the whole A2 OS component library, compiler and development environment – all this in source and compiled form!

**WinA2mini_(x86|x64)_rev_XXXXX.exe** – The installer for build of A2 Operating System with minimal amount of applications and without contributed code. Despite the minimum size this build includes the whole A2 OS component library, compiler and development environment – all this in source and compiled form! You can easily rebuild the whole system from sources just by several mouse clicks! Click the **Rebuild** button in the **Develop** section of the main menu and then double click by **System.DoCommands** text (such texts called _commands_) in the opened window.

**WinA2mini_(x86|x64)_rev_XXXXX.7z** – The same WinA2 mini build as .zip archive.

**DarwinA2 (32|64) Installer.dmg** – The drive image with installer for Mac OS X / macOS. Installer uses [builds](http://www.informatik.uni-bremen.de/~fld/UnixAos/) maintained by Guenter Feldmann. **Important note**: _X11 is no longer included with macOS, but X11 server and client libraries are available from the XQuartz project. Install XQuartz manually before installation of A2 (Use a community-supported version of the X11 windowing system for Mac OS-X 10.6.3 or later. Please visit http://www.xquartz.org for more information)_.
