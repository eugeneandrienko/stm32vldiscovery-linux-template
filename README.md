# STM32VLDiscovery for Linux

There is a template STM32VLDiscovery project for Linux.

Unlike other similar project, there are:
* You don't need Keil
* You don't need IAR
* You don't need Eclipse or Eclipse-based IDE
* You don't need any another IDE!

All what you need - is a blank black console, emacs or vim for source code 
editing and other dependencies:
* Cross-compiler (arm-none-eabi-gcc, the same gdb and etc.). I suggest 
cross-compiler from Linaro company (https://launchpad.net/gcc-arm-embedded).
* stlink utility - to load binary to the STM32VLDiscovery board.
* make
* sudo
* Development files for SG utils (install ``libsgutils2-dev`` for Debian-based distributives or ``sg3-utils`` for Gentoo-based).

To compile project - execute ``make`` in console. To flash project to the
STM32 board - execute ``./flashing_stm32vldiscovery.sh`` and follow orders
on the screen.
