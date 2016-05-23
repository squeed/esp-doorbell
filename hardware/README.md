ESP8266 to Doorbell adapter
===========================

This is a simple PCB that connects an ESP-8266 with a Ritto 6630 door opener. This
sort of hardware is typically used in German apartment buildings. The circuit allows
the front door to be opened via an ESP8266.

This particular telephone has slots for multiple mo![](../img/pi-adapter-sch.png)
dules within the chassis. This board
is designed to fit in that slot.

The telephone opens the door by tying the Opener signal to Ground. So, this board
provides an optoisolator that simulates pressing the button.

Since the system provides 12v power, we use that.

This also exposes the SPI lines to connect an LED strip, because those are useful.

![](rendering.png)
![](schematic.png)
