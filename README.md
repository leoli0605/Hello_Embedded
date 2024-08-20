# Embedded Introduction Project

## Basic

- [ ] STM32F723 + [SEGGER RTT](https://github.com/adfernandes/segger-rtt)
- [ ] STM32F723 + [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS-Kernel) + [LibOpenCM3](https://github.com/libopencm3/libopencm3) + [littlefs](https://github.com/littlefs-project/littlefs) + [cJSON](https://github.com/DaveGamble/cJSON)
- [ ] STM32F723 + [FreeRTOS+POSIX](https://github.com/FreeRTOS/Lab-Project-FreeRTOS-POSIX)
- [ ] STM32F723 + [FreeRTOS+FAT](https://github.com/FreeRTOS/Lab-Project-FreeRTOS-FAT)
- [ ] STM32F723 + [NuttX](https://github.com/apache/nuttx)
- [ ] STM32F723 + [TinyUSB](https://github.com/hathach/tinyusb)
- [ ] STM32F723 + [CherryUSB](https://github.com/cherry-embedded/CherryUSB)
- [ ] STM32F723 + [FreeRTOS+FAT](https://github.com/FreeRTOS/Lab-Project-FreeRTOS-FAT) + [CherryUSB](https://github.com/cherry-embedded/CherryUSB)
- [ ] STM32F723 + [NuttX](https://github.com/apache/nuttx) + [CherryUSB](https://github.com/cherry-embedded/CherryUSB)
- [ ] Build a STM32F723 application to integrate all into one demo project.
  - In-Application-Programming with Secure Boot (COM, HID, MSC, DFU)
  - Camera Demo (UVC)

## IoT

- [ ] ESP32 + [LVGL](https://github.com/lvgl/lvgl)
- [ ] ESP32 + [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS-Kernel) + [LVGL](https://github.com/lvgl/lvgl)
- [ ] ESP32 + [NuttX](https://github.com/apache/nuttx) + [LVGL](https://github.com/lvgl/lvgl)
- [ ] ESP32 + [lwIP](https://github.com/lwip-tcpip/lwip)
- [ ] ESP32 + [FreeRTOS-Plus-TCP](https://github.com/FreeRTOS/FreeRTOS-Plus-TCP)
- [ ] ESP32 + [NuttX](https://github.com/apache/nuttx)
- [ ] ESP32 + [lwIP](https://github.com/lwip-tcpip/lwip) + [MQTT-C](https://github.com/LiamBindle/MQTT-C)
- [ ] ESP32 + [FreeRTOS-Plus-TCP](https://github.com/FreeRTOS/FreeRTOS-Plus-TCP) + [MQTT-C](https://github.com/LiamBindle/MQTT-C)
- [ ] ESP32 + [NuttX](https://github.com/apache/nuttx) + [MQTT-C](https://github.com/LiamBindle/MQTT-C) + [HTTP Server](#)
- [ ] ESP32 + [Matter](https://github.com/project-chip/connectedhomeip)
- [ ] ESP32 + [Thread](https://github.com/openthread/openthread)
- [ ] Build an ESP32 application to integrate all into one demo project.
  - display information on the panel (LVGL)
  - display/control status in both wired and wireless modes (HID, MQTT, Matter, OpenThread)
  - streaming/controlling live video/audio in both wired and wireless modes (lwIP, TCP/UDP, RTSP/Socket, HTTP Server/cJSON and UVC)
  - recording live video/audio onto an SD card and playing it back from the SD card via both wired and wireless modes (MJEP/AVI, PCM/WAV, MP3, littlefs/FSFAT, MSC)
  - OTA/In-Application-Programming (bootloader, wear leveling, ...)
- [ ] ESP32 + [YOLO](#)

## Embedded Linux

- [ ] Raspberry Pi + [buildroot](https://github.com/buildroot/buildroot) + [HTTP Server](#) + [RTSP](#) + [WebSocket](#) + [WebRTC](#)
- [ ] Raspberry Pi Zero W + [BME280](https://shop.playrobot.com/products/raspberry-pi-ved0063) + [MQTT](#)
