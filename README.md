# USB C cable tester - C2C caberQU
Can my cable support USB 2.0/3.0/3.1/3.2, power delivery? Is a wire broken?

<img src='https://github.com/petl/USB-C-cable-tester-C2C-caberQU/blob/main/photos/v3/CaberQ_003.jpg' width='100%'>

Website: https://caberqu.com

#### What is it?

The C2C caberQU board applies a voltage to all pins of a cable and measures which ones are connected to the other end. It features LEDs for each of the 24 pins and even shield. So in total 25 LEDs offer all possible combinations for USB-C receptacle pin usage in different modes:

- USB 2.0/1.1
- USB Power Delivery
- USB 3.0/3.1/3.2
- Alternate Mode
- Debug Accessory Mode
- Audio Adapter Accessory Mode

See [the manual](https://github.com/petl/USB-C-cable-tester-C2C-caberQU/blob/main/documentation/v3/caberQU_manual_v3.2_compressed.pdf) to check which pin should be connected to where and get more infos about the USB-C connector. 

<img src='https://github.com/petl/USB-C-cable-tester-C2C-caberQU/blob/main/photos/v3/IMG_20220911_165540-min.jpg' width='100%'>


#### Why did you make it?

The amount of possible USB C cable combinations is endless. If you use the wrong cable, data transmission may be slower than possible or certain devices may not work at all. In the USB C standard, the cable plays an important role and has to advertise itself as such. All of them need to have certain pins connected, some need to be grounded, some need to have resistors attached. 

#### What makes it special?

Unfortunately there is no easy way to extract whether a certain cable can support a certain use case. If a cable has a broken pin, that makes it even worse, due to their unpredictable behavior. The C2C caberQU cable tester solves this once and for all. By flipping the USB connectors, the opposing LEDs for some pins light up due to them not being mirrored. That's on purpose and defined in the USB C standard. The product is sold with one CR2032, the PCB and some basic instructions. The USB C cable is not included. You have to extract the needed pins for your desired usage on your own, unfortunately that can not be done universally for all possible combinations.

<img src='https://github.com/petl/USB-C-cable-tester-C2C-caberQU/blob/main/photos/v3/CaberQ_032.jpg' width='100%'>


No dedicated power supply is needed, all necessary power is supplied via the CR2032 battery.

Please note that if you have a cheaper shipping option I'm gladly using it and refunding you the difference. The item still is a prototype. It is working as intended, but funny quirks and other things are possible. It is not certified and only suited for prototyping. 

If you have any questions, just shoot me a message!
