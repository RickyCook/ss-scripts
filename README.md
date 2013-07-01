ss-scripts
==========

Simple command line interface for screenshot shortcuts

Example config
--------------

Print screen to capture, shift key captures partial and meta key uploads to Gyazo

* PrScr - `xmessage $(/usr/local/bin/ss-capture.sh full)`
* Shift + PrScr - `xmessage $(/usr/local/bin/ss-capture.sh partial)`
* Mod + PrScr - `/usr/local/bin/ss-gyazo-browser.sh full`
* Mod + Shift + PrScr - `/usr/local/bin/ss-gyazo-browser.sh partial`
