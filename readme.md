# Awesome DOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Operating system for x86-based personal computers that was popular during the 1980s and early 1990s.

[<img src="logo.svg" align="right" width="100">](https://github.com/balintkissdev/awesome-dos)

A curated list of references for development of DOS applications and learning about the system itself. This includes
list of compilers, tutorials, videos, links to free and paid books and source code to DOS games. The goal of this list
is to collect information and act as a starting point for someone who wants to start out retro-programming for the DOS
platform.

## Contents

- [DOS compilers](#dos-compilers)
- [Development IDEs](#development-ides)
- [Tutorials and programming resources](#tutorials-and-programming-resources)
- [Books](#books)
- [Videos](#videos)
- [Open source DOS libraries](#open-source-dos-libraries)
- [Open source DOS games](#open-source-dos-games)


## DOS compilers

- [bcc - Bruce's Compiler](https://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.2/repos/pkg-html/bcc.html)
  - Bruce's C compiler is a simple C compiler that produces 8086 assembler for tiny/small models.
- [DJGPP](http://www.delorie.com/djgpp/) - DJ Delorie's complete 32-bit C/C++ development environment for Intel 80386.
  - Used for Quake.
- [Open Watcom](http://openwatcom.org/) - Formerly commercial C/C++ development environment for 16- and 32-bit DOS and
  Windows. The current official version is 1.9. A GitHub fork is also available.
  - The [documentation](http://openwatcom.org/doc.php) is very valuable to understand working with both version 1.9 and
    the V2 fork.
  - [Arch Wiki page](https://wiki.archlinux.org/index.php/Open_Watcom)
  - Used for Doom I-II, Warcraft I-II, Duke Nukem 3D, Full Throttle, Dark Forces and Retro City Rampage
- [Open Watcom V2](https://github.com/open-watcom/open-watcom-v2) - GitHub fork which is actively maintained and is
  ported to 64-bit Windows and Linux.
- [Turbo C 2.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tc201.zip) - C IDE and compiler from Borland first released in 1987.
- [Turbo C++ 1.01](http://www.doshaven.eu/wp-content/uploads/2014/08/tcpp101.zip) - C++ IDE and compiler from Borland released in 1991.

## Development IDEs

- [DIV Games Studio 2](https://archive.org/details/div2_iso) - IDE to develop DOS games in 2d, mode 7 and 3d. Released in 1998. [Online](http://js.mikedx.co.uk/DIV2.html) version.

## Tutorials and programming resources

### History

- [The Life of MS-DOS by Brendan Byers](https://b13rg.github.io/Life-of-MS-DOS/)

### Compiling

#### Open Watcom

- [32bit DOS development with Open Watcom](http://tuttlem.github.io/2015/10/04/32bit-dos-development-with-open-watcom.html)
- [80x86 16-bit Compiling How-to by Alexei A. Frounze](http://alexfru.narod.ru/os/c16/c16.html)

### General

- [David Brackeen - 256-Color VGA Programming in C](http://www.brackeen.com/vga/)
- [640k Really is Enough for Anyone by Robert W. Oliver II](https://blog.sourcerer.io/640k-really-is-enough-for-anyone-314f393ca5b8)
- [DOS programming resources by DOS HAVEN](http://www.doshaven.eu/sources/)
<!--lint disable no-repeat-punctuation-->
- [Just keeping it real... old skool style - Scali's OpenBlog](https://scalibq.wordpress.com/2011/11/23/just-keeping-it-real-old-skool-style/)
<!--lint enable no-repeat-punctuation-->
- [Alex Russell's Dos Game Programming in C for Beginners](https://web.archive.org/web/20201112023702/http://www3.telus.net/alexander_russell/course/introduction.htm)
  - This series contains a tutorial for making [buffered input handling](https://web.archive.org/web/20200203195410/http://www3.telus.net/alexander_russell/course/chapter_4.htm)
- [PC Game Programmer's Encyclopedia on the Web](https://web.archive.org/web/20201111164240/http://bespin.org/~qz/pc-gpe/)
- [The Art of Demomaking by flipcode](http://web.archive.org/web/20190123060222/http://www.flipcode.com/archives/The_Art_of_Demomaking-Issue_02_Introduction_To_Computer_Graphics.shtml)
  - Series from 1999 that introduces to graphics programming under DOS. The home site contains other late 90s/early 2000s game programming articles as well.

### DOS API

- [bios.h header documentation by Digital Mars](https://digitalmars.com/rtl/bios.html)
- dos.h header documentation by Digital Mars [Part 1](https://digitalmars.com/rtl/dos.html) [Part 2](https://digitalmars.com/rtl/dos2.html)

### Interrupts

- [Ralph Brown's Interrupt List - HTML version](https://web.archive.org/web/20201111162212/http://www.ctyme.com/rbrown.htm)
  - Original in downloadable .zip files from [Ralph Brown's website](https://web.archive.org/web/20201108093425/http://www.cs.cmu.edu/~ralf/files.html)

### Video

- [Values for standard video mode](https://web.archive.org/web/20200214123701/http://www.columbia.edu/~em36/wpdos/videomodes.txt)

#### CGA

- [Color Graphics Adapter: Notes](https://web.archive.org/web/20201112020351/https://www.seasip.info/VintagePC/cga.html)

#### VGA

- [VGA Hardware - OSDev wiki](https://wiki.osdev.org/VGA_Hardware)

#### SVGA

- [DOS Super VGA / VESA programming notes - by Myles](https://web.archive.org/web/20200724153658/http://www.faqs.org/faqs/pc-hardware-faq/supervga-programming/)
- [VESA Video Modes - OSDev wiki](https://wiki.osdev.org/Getting_VBE_Mode_Info)
- [DJGPP VESA guide](http://www.delorie.com/djgpp/doc/ug/graphics/vesa.html.en)
- [High-res high-speed VESA tutorial](https://web.archive.org/web/20200128180543/http://www.monstersoft.com/tutorial1/)
- [C code sample for drawing in VESA 2.0 mode](https://web.archive.org/web/20200121065447/http://www.codenet.ru/progr/video/vesa20ex.php)

### Sound

#### PC Speaker

- [Frequencies of Musical Notes](https://web.archive.org/web/20201129091353/https://pages.mtu.edu/~suits/notefreqs.html)
- [Making some noise with the PC speaker!](http://heim.ifi.uio.no/~inf3150/grupper/1/pcspeaker.html)
- [Programming the PC Speaker by Mark Feldman](https://web.archive.org/web/20150302161648/http://heim.ifi.uio.no/~inf3150/grupper/1/pcspeaker.html)
- [Sound Programming with PC Speaker - Chapter 23 of A to Z of C](https://web.archive.org/web/20171115162742/http://guideme.itgo.com/atozofc/ch23.pdf)

#### AdLib/OPL2

- [Yamaha YM3812 (OPL2) sound chip Wikipedia article](https://en.wikipedia.org/wiki/Yamaha_YM3812)
- [The Ad Lib Music Synthesizer Card Programming Guide - by Tero Töttö](https://web.archive.org/web/20200427145810/http://www.vgmpf.com/Wiki/images/4/48/AdLib_-_Programming_Guide.pdf)

#### Sound Blaster/OPL3

- [Programmer's Guide to the Yamaha YMF 262/OPL3 FM Music Synthesizer](https://web.archive.org/web/20200509082459/http://www.fit.vutbr.cz/~arnost/opl/opl3.html)
- [Sound Blaster 16 Programming Document 3.5 by Ethan Brodsky](https://web.archive.org/web/20201130110457/http://homepages.cae.wisc.edu/~brodskye/sb16doc/sb16doc.html)
  - version 3.4 on [GameDev.net archive](http://archive.gamedev.net/archive/reference/articles/article444.html)
- [Sound Blaster Hardware Programming Guide](https://web.archive.org/web/20180507161514/http://archive.gamedev.net/archive/reference/articles/article444.html)
- [Soundblaster Programming Information v0.90](https://web.archive.org/web/20191020222313/http://www.intel-assembler.it/portale/5/soundblaster-programming-information/sb-reference-for-programming-sound.asp)

### Other

- [How to build DOS COM files with GCC by Chris Wellons](https://nullprogram.com/blog/2014/12/09/)
- [Table of DOSBox cyclecounts according to processor types](https://www.alternatewars.com/Games/DOSBox/DOSBox.htm)

## Books

### Free

- [Game Engine Black Book: Wolfenstein 3D - by Fabian Sanglard](http://fabiensanglard.net/gebbwolf3d_v2.1.pdf)
- [Game Engine Black Book: Doom - by Fabian Sanglard](http://fabiensanglard.net/gebbdoom_v1.1.pdf)
- [A to Z of C - a book on C/DOS programming by K. Joseph Wesley and R. Rajesh Jeba Anbiah](https://web.archive.org/web/20201109033646/http://guideme.itgo.com/atozofc/)
- [Michael Abrash's Graphics Programming Black Book Special Edition](https://web.archive.org/web/20201112020812/http://www.phatcode.net/res/224/files/html/index.html)

### Paid

- [Tricks of the Game-Programming Gurus - by Andre Lamothe, John Ratcliff and Denise Tyler](https://www.amazon.com/Tricks-Game-Programming-Gurus-Andre-Lamothe/dp/0672305070/)

## Videos

- [CGA Graphics - Not as bad as you thought! - by 8-bit Guy](https://www.youtube.com/watch?v=niKblgZupOc)
- [How Oldschool Sound/Music worked - by 8-bit Guy](https://www.youtube.com/watch?v=q_3d1x2VPxk)
  - Contains section about the Yamaha OPL chip found in AdLib and Sound Blaster sound cards at [4:32](https://www.youtube.com/watch?v=q_3d1x2VPxk&feature=youtu.be&t=272)
- [LGR - Evolution of PC Audio - As Told by Secret of Monkey Island](https://www.youtube.com/watch?v=a324ykKV-7Y)
- [Porting Retro City Rampage to MS-DOS: From PS4 to 1.44MB Floppy](https://www.youtube.com/watch?v=kSKeWH4TY9Y) - GDC talk.

## Open source DOS libraries

- [Allegro 4.2](https://www.allegro.cc/files/?v=4.2)
- [LoveDOS](https://github.com/rxi/lovedos) - A framework for making DOS games in Lua.

## Open source DOS games

### Homebrew games with source code

List of all homebrew DOS games: http://www.doshaven.eu

- [DOS Defender](https://github.com/skeeto/dosdefender-ld31)
- [Dungeons of Noudar](https://github.com/TheFakeMontyOnTheRun/dungeons-of-noudar)
- [Emeritus Pong](https://sourceforge.net/projects/empong/)
- [Floppy Bird](https://github.com/icebreaker/floppybird) - 16 bit assembly.
- [Gridfighter 3D](https://github.com/porta2note/gridfighter3d) - Quickbasic.
- [Hangman](https://sourceforge.net/projects/hangman-dos/) - Basic.
- [Magenta's Maze](http://www.doshaven.eu/downloads/537) - [site](https://archive.org/details/MAGSMAZE)
- [NetHack](https://github.com/NetHack/NetHack)
- [Piskworks](https://github.com/berk76/piskworks)
- [Plutonium Caverns](https://github.com/jani-nykanen/plutonium-caverns)
- [Ptakovina](https://github.com/berk76/tetris)
- [sudoku86](https://sourceforge.net/projects/sudoku86/)
- [Tetris](http://www.doshaven.eu/downloads/373) - [site](http://www.doshaven.eu/game/tetris/), assembly.
- [Towers of Hanoi](https://github.com/sblendorio/hanoi-dos) - Turbo Pascal, originally released in 1996.
- [x86 pong](https://github.com/spacerace/x86-pong) - PC-Booter game.
- [zmiy](https://sourceforge.net/projects/zmiy/)

### Freeware games with source code

- [Cyberdogs](https://web.archive.org/web/20180120123425/https://www.classicdosgames.com/files/source/dogs_src.zip) - Turbo Pascal.

### Commercial games with published source code

- [Abuse](https://web.archive.org/web/20160402141350/http://www.classicdosgames.com/files/source/abuse_pd.tgz)
- [Beneath a Steel Sky](https://web.archive.org/web/20200721083621/https://www.classicdosgames.com/files/source/sky-source.zip) - Assembly.
- [Catacomb](https://github.com/CatacombGames/Catacomb) - Turbo Pascal.
- [Catacomb 3D](https://github.com/CatacombGames/Catacomb3D)
- [Commander Keen in Keen Dreams](https://github.com/keendreams/keen)
- [Descent](https://github.com/videogamepreservation/descent)
- [Descent II](https://github.com/videogamepreservation/descent2)
- [Doom](https://github.com/id-Software/DOOM)
  - The DOS-specific code for Doom could not be published because of a
    dependency to the licensed DMX sound library, hence why it's cleaned up and
    only the Linux source is there. However, the Heretic and Hexen projects contain
    the original DOS code in a way where DMX-related code is removed.
- [Duke Nukem 3D](https://web.archive.org/web/20160403223736/http://www.classicdosgames.com/files/source/duke3dsource.zip)
- [Heretic](https://github.com/OpenSourcedGames/Heretic)
- [Hexen](https://github.com/OpenSourcedGames/Hexen)
  - Original [SourceForge link](https://sourceforge.net/projects/heretic/files/) for Heretic/Hexen.
- [Hovertank 3D](https://github.com/FlatRockSoft/Hovertank3D)
- [Quake](https://github.com/id-Software/Quake)
- [Rise of the Triad](https://github.com/videogamepreservation/rott)
- [Sopwith](https://web.archive.org/web/20200131222432/http://davidlclark.com/page/sopwith)
  - [MaiZure's Projects - Decoded: Sopwith](https://web.archive.org/web/20201211175311/https://www.maizure.org/projects/decoded-sopwith/)
- [Wolfenstein 3D](https://github.com/id-Software/wolf3d)
