# Hab Bridge

Starting with the Zephyr environmental sensing bluetooth sample, built for the
Nordic nRF7002-DK development board.

The goal is to use this board as a physical user interface as well as a bridge
between mobile and IoT devices in the Hab.

TODO:

 - add rust lib via cbindgen
 - remove dep on external bluetooth sample code
 - add bme environment sensor
 - add gatt support for general gpio/data acquisition
 - pairing/connection support for privacy
 - demonstrate lcd touchscreen support
 - implement over-the-air updates
 - install the board in service
