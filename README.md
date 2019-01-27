# ESP8266-Programmer-Button-Extension

A very simple RESET and GPIO0 button extension board for a ESP8266 USB programmer

Nowadays you can buy handy little USB programmer board for the ESP8266-01 and they are cheap (very very cheap in China).

- [aliexpress](https://www.aliexpress.com/af/ch340-usb-to-esp8266-esp-01.html?g=y&SearchText=ch340+usb+to+esp8266+esp+01&d=y&misspellText=ch340+usb+to+esp8266+esp+01&initiative_id=SC_20190127060118&origin=n&spm=2114.search0604.spellresult.1.5f7e6e9b2Ri52a&isViewCP=y&jump=afs)
- [amazon.com](https://www.amazon.com/s/ref=a9_asi_1?rh=i%3Aaps%2Ck%3Ach340+usb+to+esp8266+esp01&keywords=ch340+usb+to+esp8266+esp01&ie=UTF8&qid=1548597881)
- [amazon.de](https://www.amazon.de/s/ref=a9_asc_1?rh=i%3Aaps%2Ck%3Ach340+usb+to+esp8266+esp+01&keywords=ch340+usb+to+esp8266+esp+01&ie=UTF8&qid=1548597795)

The only anoying thing is they have no RESET or PROGRAMMING (GPIO0) buttons.
But this is easily to solve, because the pins of the yellow socket are quite long and you can solder your own button board under the programmer board.

![side view](./img_0242.jpg)

You have to solder the two buttons and three wires only and you are ready :-)

![bottom view](./img_0243.jpg)

The right button is the PROGRAMMING (GPIO0) button the left one is the RESET button. The best way to put your ESP in programming mode is to use one finger press down the PROGRAMMING button and with the same finger press down the RESET button. Release the buttons first RESET than PROGRAMMING and your ESP is in programming mode.

![bottom view](./img_0244.jpg)

If your serial monitor speed is set to 74880 you will see this message:

`ets Jan  8 2013,rst cause:2, boot mode:(1,6)`

boot mode (1,x) means programming mode

boot mode (3,x) is the running mode

---

Have fun with this very tiny hack.