# Idea

So far, we have mainly focused on key/crypto attacks.
However, the total landscape of attacks is a lot wider, and the most likely attacks are probably of different types.

Therefore,

Group all vulnerabilities / attacks by

```
horizontal: 4-tier view   
device  |   gateway  |   netwserver  |   app/data servers  (terms might differ, but quite universal)

vertical: 
type/class of attack  - physical, user/governance, crypto .... (not a stringent system, but good enough)
```



We could keep the separation into "traditional" and "new IoT-specific" attack vectors.

For each attack, we could discuss possible outcomes, risk

# Overview

![LoRaWAN overview](https://github.com/ITU-PITLab/LoRaWAN_security/blob/master/LoRaWAN-Overview.png "LoRaWAN overview")


|               |   Device     |   Gateway    |  Netw Server | App/data Server    |
|:------------- |:-------------|:-------------|:-------------|:-------------|
| physical               | theft    | theft     |    |   | 
| physical               | jamming    | jamming     |    |   | 
| protocol               | energy depletion     |      |    |   | 
| user/governance | Default or Weak Credentials     | default password   |    |  |
| user/governance | key provision    |   |   | key provision |
| protocol                | weak crypto     |     | weak crypto    |   | 
| OS/FW              |    | FW old     |    |   |
| protocol               | Reverse Engineering Devices     |      |    |   |
| protocol               | Replay     |      |    |   |
| protocol               | Device spoofing     |      |    |   |
| protocol               | stupid keys     |      |    |   |
| protocol               | Reverse Engineering Devices     |      |    |   |
| protocol               | Offline Key Cracking     |      |    |   |




