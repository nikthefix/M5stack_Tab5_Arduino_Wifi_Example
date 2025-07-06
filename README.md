nikthefix 06.07.25

M5stack Tab5 Wifi example for Arduino

Depends on Arduino_ESP32 V3.2.1 and above

Select board ESP32P4 Dev Module - not M5tab5 board as M5 boards package has not been updated to 3.2.1 at the time of writing

Enable USB CDC On Boot if you wish to use the serial monitor

The extra method recently added to the core by @me-no-dev is called at line 52 - special thanks to him for this work

The mDNS URL is esp32.local or view the serial monitor for the dynamically assigned server IP address

