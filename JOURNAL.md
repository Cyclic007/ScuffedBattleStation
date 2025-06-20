---
title: "ScuffedBattleStation"
author: "Cyclic"
description: "A colling stand and cool thing for my laptop"
created_at: "2025-6-05"
---

#### June 7 actualy starting

so the plan is to have a cooling pad that includes 2 usb-c ports(from a hub) and an ethernet port

The Specs

- https://en.wikipedia.org/wiki/IEEE_802.3
- https://en.wikipedia.org/wiki/USB-C

so I start on the scematic

I am goning to use LAN9513i

- http://ww1.microchip.com/downloads/en/DeviceDoc/00002305A.pdf

I also am going to be useing USB 2.0

spent about 1hr trying to find the right risitor

** Total Time spent 5hr ** 

#### June 7 part 2

I finished the scematic and PCB 

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/644f29519e95badf747718a1331e8e104f8c7d1c_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3f61ca0e62ecd940865626d81b3810b320c07354_image.png)

I am going to use normal fan connectors for my thing

I am also going to need to use PCBway's assembely thing because I can't hand solder a good handful of the components

** Total time spent 1hr 

#### June 9 fixing PCB 

My PCB has a problem where my drill holes are too small and need fixing

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/39d9717cea20de48c2353f18908326993ec17a9a_image.png)

Finished PCB.

** Total Time Spent 1hr **

#### June 11 making 3d models

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/5e81d29f6b0a5c9428853da5d7627ed5fdb7f7ee_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/ea9be0c1a7128b3404cefe927e0488eec02ef515_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/f7e5adcec03061fe27feb3d5e3523446423bf2d5_image.png)

** Total time spent 3 hr **

#### June 12 working more on 3d models

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d826565080f8e3d7618f18240a6986696e57bb7d_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1aa7b1a590809a847a9704768ae77a849fa3e970_image.png)

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/4ed4c2659cc7666ac6c0c2a0384ba3f3e5f181be_image.png)

in this rendition there are now slots in the frame to put the platforms and made it actually possible to put the feet on the frame

While I was trying to find price I found that JLPCB does not have the exact parts I need so I am going to have them find the right parts 

JLCPCB also has no USBC receptacles so I am going to get them separately and hand solder

I am also going to hand solder the fans directly to the PCB 

Also prepped to ship

** Total time spent 5 hr **

#### June 14 PCB fixing

I found out that I screwed up the pcb and had all of my USB-c connectors flipped in the wrong direction so I fixed that and rerouted

I also found that I forgot to attach a resistor and forgot to connect shield to gnd

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/dc98765bd9ac918f3bfee273648a23a9e3b9813a_image.png)

** Total time spent 1 hr ** 

#### June 16 adding crystals

I found that the controller I am useing needs an external crystal ossolator and needs all of the 3.3v pins connected so I fixed that and added KC2520Z1.84320C1KX00 to the PCB

I also fixed BOM

I also fixed the PCB and got an actual price for the PCBA

![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3ba1ef5c528257cfcc808a5a282add16cd73cd07_image.png)