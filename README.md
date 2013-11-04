LinuxADS
========

LinuxADS - An implementation of Beckhoff's ADS protocol for Linux based systems

LibADS enables Linux applications to communicate with Beckhoff-PLC's using the 
ADS (Automation Device Specification) protocol. 
It provides a C-Api together with the necessary routing mechanism.
To facilitate the migration of applications written for Windows,
using the DLL provided by Beckhoff, it tries to be as close to the DLL interface as possible.

While it is still under development, it has been used in an industrial environment
for about 2 years and is quit stable.

Building is straigt forward:

./configue
make
make install.

There are no dependencies, except a reasonably sane build environment.

Please read the documentation in the "doc" subfolder.

Gerhard Schiller
