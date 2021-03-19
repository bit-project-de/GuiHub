# GuiHub
ESP32 Multitasking example for Arduino combining Touch GUI (lv_arduino) and 433MHz Ask Receiver (RadioHead) running in seperate threads. Basic OTA is included to allow remote Flashing of the ESP32 Board.

The basic idea is to use a Wemos D1 Mini ESP32 as a Home Automation Room Hub / RF-Bridge with Touch UI. Each room can have radio controlled sensors and actors which can be controlled directly by the ESP32 Touch Ui.

This Arduino Sketch is a simple approach to combine required libraries and handlers in a single Arduino Sketch by seperating the Gui Loop and the RF Receiver Loop in 2 different threads to keep Gui responsible while listening for new Radio Messages.
