This is a PCB for my APRS BLE TNC, which is based on the ESP32APRS_Audio Firmware from nakhonthai - see https://github.com/nakhonthai/ESP32APRS_Audio.
This PCB implements the basic components to work with an esp32s3 and an external handheld Radio, like filters and DC Offsets. The Radio is connected via the Kenwood Plug. This is not intended for an RF Module on the Board!
It's oriented around Nakhonthai's layouts with some small changes.
I designed it for my esp32s3-N16R8 (the one already on a PCB, not the chip itself). Please check your Pin configuration before using this.

This PCB has:

-NPN transistor for PTT control

-GPIO PWM Filters

-ADC Input Bias

-UART Connectors for external GPS PCBs and other stuff (Supposed to be under the Board)

-Connectors for simple three-pin Sensors

-Every other Pin of the esp32 is led out to some connectors for future extensions, including four power pins

If you don't want to order this for yourself, get in touch; maybe I still have some lying around. (See qrz.com for email address)

73 de
DC4TA


<img width="459" height="795" alt="image" src="https://github.com/user-attachments/assets/3486ca39-0cbb-4de2-9ccd-748cd9503912" />

<img width="1171" height="763" alt="image" src="https://github.com/user-attachments/assets/5d73cc74-09fb-4c5b-aa09-6057e4a2b17d" />
