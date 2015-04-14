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

To install, simply use dpkg to install the resulting .deb package.
