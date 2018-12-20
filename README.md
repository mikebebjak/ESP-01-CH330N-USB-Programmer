# ESP-01-CH330N-USB-Programmer

This is a very simple but effective USB programmer for the ESP8266-01 Wifi microcontroller.
It uses a new CH330N SOIC-8 chip which is very easy to implement in ESP projects at a very low cost with few additional components.
The repository includes datasheet, drivers, schematics, Eagle board files and gerbers as well as an Eagle library file for the CH330N.
The drivers used for the CH330N are the same as the CH341.
You can purchase the CH330N at: https://lcsc.com/product-detail/USB_CH330N_C108996.html 
You will need:
1x CH330N USB transceiver
1x AMS1117 TO-223 3.3V regulator
1x Molex USB-A through-hole connector
1x 8-pin 2mm socket for the ESP
4x 10K 1206 resistors (for pullups and pulldowns)
2x 0.1uF 1206 capacitors
1x 6mm through-hole momentary push button for the reset button
1x large electrolytic capacitor (220uF or higher at 6.3V min.)
GPIO 0 is tied to GND permanently so this programmer cannot be used to boot the ESP (though it may sometimes work anyway).
