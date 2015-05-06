Senoko Firmware
=================

Operating system firmware for the Senoko battery/passthru board.  Source code
for the firmware may be obtained at https://github.com/xobs/senoko-chibios-3/

Building
------------

To build the package, run "git-buildpackage [tag]" where [tag] is a valid
upstream tag, such as v1.0.  You might also need to add -uc -us if building
an unsigned package.  E.g.:

    git-buildpackage -us -uc --git-upstream-tag=v1.0


Installation
------------

After the resulting .deb package has been installed the firmware still needs to be flashed to the Senoko board.

To prevent malicious alteration of the firmware during normal operation the physical "reflash" button on the Senoko must be held down during firmware updates.

Running `update-senoko` at the command line will guide you through the flashing process, including obtaining root access as necessary.
