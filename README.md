# mocicon

Mocicon is a Music On Console tray icon for quick access.
By Calvin Morrison 2009

This is a modified version implementing:

* Left double click for next song
* Right double click for previuos song

[The original source is here](https://mocicon.sourceforge.net/)

---

The source is fairly simple, and there are plenty of options to go around.
I don't do much source commenting, but it is all fairly self explanitory.

compiling without make:

    gcc -Wall -g -O2 mocicon.c -o mocicon `pkg-config --cflags --libs gtk+-2.0`

with make it is the regular as root:

    make clean install

it's simple enough. you'll need the gtk+ 2.0 libs and that's it.

run

    sudo ./install

it just installs mocicon in /usr/local/bin/
