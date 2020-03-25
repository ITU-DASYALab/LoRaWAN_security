# HFSV Small Smart City – Water meters
## Security assessment

### Introduction

Security analysis of IoT Networks is a challenging task, for various reasons:

IoT systems, rather than just consisting of their most visible and new component (sensors, gadgets, “things”) are comprised of elements spanning from device to backend, from physical unit to cloud, from edge to server.
IoT systems are often described as consisting of multiple tiers or stages, with typical numbers ranging from three (Device-Gateway-Backend), four (Device-Gateway-Edge-Backend) to five (Device-Gateway-Edge-NetworkBackend-App/DataBackend).
One such description is the “Four Stage IoT Architecture” [1]

Each of the stages on an IoT system then exists in several layers, which one might attempt to describe along the widely accepted ISO/OSI [2] or TCP/IP model, respectively in four or seven layers.

In what follows, we describe the potential vulnerabilities and attack vectors of the HFSV Small Smart City Water Meter project, in a matrix organized by stage – Device – Gateway – Network Server – App/Data Server
and
a modified OSI model (with People & Organisation added as a top layer).

![LoRaWAN overview](https://github.com/ITU-PITLab/LoRaWAN_security/blob/master/LoRaWAN-Overview.png "LoRaWAN overview")


|                       |   Device     |   Gateway    |  Netw Server | App/data Server    |
|:--------------------- |:-------------|:-------------|:-------------|:-------------|
| People & organization |              |              |              |              |
| Application           |              |              |              |              |
| OS/FW                 |              |              |              |              |
| LPWAN protocol        |              |              |              |              |
| physical              |              |              |              |              |
