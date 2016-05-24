# DNS TXT Record description

* `md` - Model Name (e.g. "Chromecast");
* `id` - UUID without hyphens of the particular device (e.g. xx12x3x456xx789xx01xx234x56789x0);
* `fn` - Friendly Name of the device (e.g. "Living Room"); 
* `rs` - Unknown (recent share???) (e.g. "Youtube TV");
* `bs` - Uknonwn (e.g. "XX1XXX2X3456");
* `st` - Unknown (e.g. "1");
* `ca` - Unknown (e.g. "1234");
* `ic` - Icon path (e.g. "/setup/icon.png");
* `ve` - Version (e.g. "04").


# Model names

* `Chromecast` - Regular chromecast, supports video/audio;
* `Chromecast Audio` - Chromecast Audio device, supports only audio.


# Useful links

* [DIAL Protocol](http://www.dial-multiscreen.org/);
* [An implementation of the Chromecast CASTV2 protocol in JS](https://github.com/thibauts/node-castv2);
* [Chromecast - steps closer to a python native api](http://www.clift.org/fred/chromecast-steps-closer-to-a-python-native-api.html);