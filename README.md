This repository contains the source code fragments,
relayr has released for the firmware of the <a href="https://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF51822">nRF51822</a> MCUs
on their Wunderbar bricks (a product which has been discontinued a while ago and apparently not even shows up on relayr's website anymore).
Although the fragments are not sufficient
to be compiled into a working firmware,
they do include driver code for
the sensors present on the bricks.

This repository will not receive any more commits from our side.
It serves ony as a "bridge" for the integration of possible future upstream commits.
All sensor driver code will be merged
into the interoberlin-mynewt-extensions repository,
where it will henceforth be maintained:

https://github.com/interoberlin/interoberlin-mynewt-extensions

The latter allows for usage of said sensors
by fully open-source, <a href="https://mynewt.apache.org/">Apache MyNewt</a>-based nRF51 firmware, e.g. ours:

https://github.com/interoberlin/Baumhaus-Firmware-MyNewt
