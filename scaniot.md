

# IoT scanning Ideas

-   can we scan the whole network efficiently?
-   can we detect some problems? e.g. key reuse?
-   can we dive deeper in the protocols?
-   MQTT

# Mapping all-things network gateways

10 gateways LoRa -> TCP/IP

-   can't learn which keys are being used?
-   real-life security threat: keys printed on paper on top of the devices

Application session key and network session key

OTAA -> join process where you advertise your application key, and
that's linked by the gateway to the right network and application.
This creates an application session key

ABP -> autonomous, session keys are preconfigured, no join process,
they just talk and claim they have pre-agreed keys

Device EUI -> unique identifier

# Links

-   [slides on IoT networking](https://learnit.itu.dk/pluginfile.php/239105/mod_resource/content/1/IoT2019_Networking_1.pdf)
-   [LoRa alliance security whitepaper](https://lora-alliance.org/sites/default/files/2019-05/lorawan_security_whitepaper.pdf)
-   [One-key<sub>MAC</sub>](https://en.wikipedia.org/wiki/One-key_MAC)
-   [AES CTR](https://en.wikipedia.org/wiki/Block_cipher_mode_of_operation#Counter_(CTR))
-   [LoRa wiki page](https://en.wikipedia.org/wiki/LoRa)
-   [LoRa vs LTE, vs Sigfox comparison](http://www.nickhunn.com/lora-vs-lte-m-vs-sigfox/)
-   [[<https://www.zdnet.com/article/lorawan-networks-are-spreading-but-security-researchers-say-beware/>][ZDnet article on lorawan network security]]

