# Marlin 3D Printer Firmware

<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

Marlin is the world's most popular open source firmware for Replicating Rapid Prototyper (RepRap) machines, commonly referred to as "3D printers." Marlin Firmware is highly efficient, running even on modest 16MHz embedded AVR processors. While Marlin 1.1 only supports ATmega AVR (Arduino, etc.) and AT90USB (Teensy++ 2.0), [Marlin 2.0](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x) also adds support for several ARM processors, including the SAM3X8E (Arduino Due), NXP LPC1768/LPC1769 ARM Cortex-M3 (Re-Arm, MKS SBASE, Smoothieboard), and ARM Cortex-M4 (Teensy 3.5/3.6, STM32F1/4/7).

A monumental amount of talent and effort goes into Marlin production, and thanks are due to many volunteers around the world. We work closely with the community, contributors, vendors, host and library developers, etc. to improve the quality, configurability, and compatibility of Marlin Firmware with a [huge variety](http://marlinfw.org/docs/configuration/configuration.html#motherboard) of boards. For the final 1.1 release we focused on code quality, performance, stability, and overall user experience. Several new features were added, many of which require no extra hardware.

## Documentation

- Visit [marlinfw.org](http://marlinfw.org/) for complete documentation on [configuration](http://marlinfw.org/docs/configuration/configuration.html), [installation](http://marlinfw.org/docs/basics/install.html), [features](http://marlinfw.org/meta/features/), and the many [G-codes](http://marlinfw.org/meta/gcode/) that Marlin supports. We will continue to expand the site to include in-depth articles, tutorials, and how-to videos on all of Marlin's features.
- See the [Releases](https://github.com/MarlinFirmware/Marlin/releases) page for Release Notes on all current and previous versions of Marlin.
- Check out the [RepRap.org Marlin Page](http://reprap.org/wiki/Marlin) for an overview of Marlin and its role in the RepRap project.

## Marlin 1.1.x

The 1.1.x branch is home to all tagged releases of Marlin 1.1.

Marlin 1.1.9 is the final release of the AVR-only flat version of Marlin Firmware, so there will be no further 1.1.x releases. However [`bugfix-1.1.x`](https://github.com/MarlinFirmware/Marlin/tree/bugfix-1.1.x) will continue to receive patches for critical bugs, so be sure to test it (or [`bugfix-2.0.x`](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)) before reporting any bugs you find in 1.1.9.


## License

Marlin is published under the [GPL license](https://github.com/COPYING.md) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

---

<!-- [![Coverity Scan Build Status](https://scan.coverity.com/projects/2224/badge.svg)](https://scan.coverity.com/projects/2224) -->

- [![Travis Build Status](https://travis-ci.org/MarlinFirmware/Marlin.svg)](https://travis-ci.org/MarlinFirmware/Marlin)
- [![Flattr Scott Lahteine](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=thinkyhead&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software) - Flattr Scott Lahteine
- [![Flattr Erik van der Zalm](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software) - Flattr Erik van der Zalm
