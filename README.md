## **NanoHat OLED**

Example code of correct use and start for the NanoHat OLED.  

Designed specifically to work with the NanoHat OLED:
http://wiki.friendlyarm.com/wiki/index.php/NanoHat_OLED

Currently supported boards (Plug & Play):
* NanoPi NEO
* NanoPi NEO Air
* NanoPi NEO2
* NanoPi NEO Plus2.

Also support other development board with the i2c interface (Need to manually connect).  


Installation
------------
Execute the following command in the Ubuntu core system:    

```
# git clone https://github.com/friendlyarm/NanoHatOLED.git
# cd NanoHatOLED
# sudo -H ./install.sh
```
The demo will automatically start at the next reboot.  

Troubleshoot
------------
Check that the path in /usr/local/bin/oled-start is correct. You can just run it, you would get an error if it's wrong.
Reboot once corrected, boom!

## License

The MIT License (MIT)
Copyright (C) 2017 FriendlyELEC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
