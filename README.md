# ESP8266-WIFI-Humidity-Monitor
Wireless humidity Monitor for my 3D printer filament. Samples DHT 11 every X hours/days, sends it to IFTTT and goes back in to deep sleep.
See the FULL Assembly and project video here: 
See this video for detailled IFTT Config (motion sensor) https://www.youtube.com/watch?v=y9XC5yHR5Bk
### Wiring For ESP12E LOLIN 
| Pin On DHT11| Pin On ESP8266|
| ------------- |----------------|
| GND     | G |
| VCC     | 3V3 |
| SIG    | GPIO0 (D3 on LOLIN) |
### Special Wiring
RST> D0 for wakeup (GPIO16/WAKE on NodeMCU)
NOTE: RST line wakeup Jumper must be removed to program!
### Support my projects by picking up the display/board here:
ESP8266: https://amzn.to/2vkxOP2
DHT11: https://amzn.to/2OP0RSD
### More Projects and Videos!
My Youtube Channel  : http://www.youtube.com/mkmeorg
My website   : http://www.mkme.org

### Other Random noes:
Some code borrowed from: https://github.com/beamzer/Wemos-IFTTT-Button/blob/master/Wemos-IFTTT-Button/Wemos-IFTTT-Button.ino

Another cool version: https://nobugsjustfeatures.wordpress.com/2017/12/11/pir-sensor-alarm-with-esp8266-and-ifttt-webhooks-maker/

Yes some variables are no longer used and should be removed. That is a future person problem- deal with it.

Yes credentials are hard coded- I did this to expressly annoy the internutz. Life is about joy in little wins....

ESP Deep sleep tutorial from Rui here: https://randomnerdtutorials.com/esp8266-deep-sleep-with-arduino-ide/

GPIO16 must be tied to reset to wake!
Video explains: https://www.youtube.com/watch?v=Q8GT-GBH7ok
