# esp32_arduino_reference
Reference hello_world esp32 application that links to various arduino libraries for testing

submodules:

git submodule add https://github.com/jfm0/arduino-esp32.git components/arduino
git submodule add https://github.com/joltwallet/esp_littlefs.git components/esp_littlefs

inside components/arduino:
git submodule add https://github.com/jfm0/m5stack libraries/m5stack

# Hello World Example

Starts a FreeRTOS task to print "Hello World"

See the README.md file in the upper level 'examples' directory for more information about examples.
