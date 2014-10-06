bluez
=====

Official Linux Bluetooth protocol stack

About
=====


bluetooth
=========

The Bluetooth wireless technology is a worldwide specification for a small-form factor, low-cost radio solution that provides links between mobile computers, mobile phones, other portable handheld devices, and connectivity to the Internet. The specification is developed, published and promoted by the Bluetooth Special Interest Group (SIG).

features
========

BlueZ provides support for the core Bluetooth layers and protocols. It is flexible, efficient and uses a modular implementation. It has many interesting features:

Complete modular implementation
Symmetric multi processing safe
Multithreaded data processing
Support for multiple Bluetooth devices
Real hardware abstraction
Standard socket interface to all layers
Device and service level security support
Currently BlueZ consists of many separate modules:

Bluetooth kernel subsystem core
L2CAP and SCO audio kernel layers
RFCOMM, BNEP, CMTP and HIDP kernel implementations
HCI UART, USB, PCMCIA and virtual device drivers
General Bluetooth and SDP libraries and daemons
Configuration and testing utilities
Protocol decoding and analysis tools
The current set of supported profiles is available here.

platforms
=========

The BlueZ kernel modules, libraries and utilities are known to be working prefect on many architectures supported by Linux. This also includes single and multi processor platforms as well as hyper threading systems:

Intel and AMD x86
AMD64 and EM64T (x86-64)
SUN SPARC 32/64bit
PowerPC 32/64bit
Intel StrongARM and XScale
Hitachi/Renesas SH processors
Motorola DragonBall

distributions
=============

Support for BlueZ can be found in many Linux distributions and in general it is compatible with any Linux system on the market:

Debian GNU/Linux
Ubuntu Linux
Fedora Core / Red Hat Linux
OpenSuSE / SuSE Linux
Mandrake Linux
Gentoo Linux

history
=======

The history page give more background on how BlueZ was created and what else happened in the early days of the Bluetooth technology.

awards
TuxMobil GNU/Linux Award 2005
