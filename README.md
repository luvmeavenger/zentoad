# zentoad
An os using c and assembly.
============================================================
              ZEN TOAD OS - VERSION 1.0
          The Lightweight x86 Hobbyist System
============================================================

Welcome to ZenToad OS, a custom 32-bit operating system 
built for simplicity and performance.

[ SYSTEM FEATURES ]
------------------------------------------------------------
* Kernel: Custom 32-bit x86 Monolithic
* UI: Integrated Window Manager (WM) Bar
* Storage: ATA PIO Disk Driver (read/write support)
* Editor: Full-screen text editor buffer

[ COMMANDS ]
------------------------------------------------------------
- help      : Display available commands
- edit      : Open the text editor (Press ESC to exit)
- save      : Save editor text to the virtual disk
- load      : Load last saved text from the disk
- clear     : Clear the terminal screen
- shutdown  : Power off the system (QEMU support)

[ HOW TO RUN ]
------------------------------------------------------------
If you are using QEMU on Windows/Linux/Android:
qemu-system-i386 -kernel zentoad.bin -drive file=disk.img,format=raw

[ NOTES ]
------------------------------------------------------------
ZenToad uses Sector 2 of the primary master disk for 
persistent storage. Ensure 'disk.img' is present in the 
root directory.

Developed by: Zexion
Date: February 2026
============================================================
