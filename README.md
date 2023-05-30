Wifi proxy for NMEA frames received on a virtual serial port connected to USB.

Tested en ESP32-S2 and should work on ESP32-S3 (not tested).

This application receives NMEA frames from a USB device using a VCP (Virtual Comm Port) and relay them
to an UDP socket frame by frame.

Based on idf example: [cdc_acm_vcp](https://github.com/espressif/esp-idf/tree/903af13e847cd301e476d8b16b4ee1c21b30b5c6/examples/peripherals/usb/host/cdc/cdc_acm_vcp) and [libnmea-esp32](https://github.com/igrr/libnmea-esp32/blob/5e80d96e0e9d6ecdf8401abd90c243a720147814/example/main/nmea_example_uart.c).
