# Idea

group all vulnerabilities / attacks by

```
horizontal: 4-tier view   
device  |   gateway  |   netwserver  |   app/data servers  (terms might differ, but quite universal)

vertical: 
type/class of attack  - physical, user/governance, crypto .... (not a stringent system, but good enough)
```

# Overview

![LoRaWAN overview](https://github.com/ITU-PITLab/LoRaWAN_security/blob/master/LoRaWAN-Overview.png "LoRaWAN overview")


|               |   Device     |   Gateway    |  Netw Server | App/data Server    |
|:------------- |:-------------|:-------------|:-------------|:-------------|
| physical               | theft    | theft     |    |   | 
| physical               | jamming    | jamming     |    |   | 
| LoRaWAN protocol               | energy depletion     |      |    |   | 
| user/governance | default password    | default password   |    |  |
| user/governance | key provision    |   |   | key provision |
| cryptography               | weak crypto     |     | weak crypto    |   | 
| OS/FW              |    | FW old     |    |   |

