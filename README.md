# midibrain
all info about our midi brain


The midi brain is based on an arduino pro micro. 
This shield will provide supercolider with io trough midi for our projects 


![alt text](https://www.bitsandparts.nl/partpics/0001FUNDUINOMINILEONARDO%5E3_hi.jpg)

## remote control

this module contains a 4 ch 433 mhz reciever. 

![alt text](https://hobbycomponents.com/2346-large_default/4-channel-433mhz-wireless-receiver-with-remote-fob.jpg)

The 4 gpio used for this module are: <br>

channel 1: gpio 10 <br>
channel 2: gpio 16 <br>
channel 3 gpio 14 <br>
channel 4 gpio 15 <br>
<br>

## External connections 
This module contains 3 external gpio connectors each connector has 4 pins 
![alt text](https://ae01.alicdn.com/kf/S81bbad23b49a4bfc8301678cb47c2a1dB/5-Paar-15edg-Kf2edg-3-5Mm-3-81Mm-3-96Mm-5-08Mm-Pcb-Schroef-Klemmenblok-2.jpg_80x80.jpg_.webp)

<br>
From left to right<br>
<br>
connector 1 <br>
1: gnd <br>
2: 5v <br>
3: io1/rx (serial tx/digital in/interupt) <br>
4: io0/tx (serial rx/digital in/interupt) <br>
<br>
connector 2 <br>
1: gnd <br>
2: 5v <br>
3: A1(analog in/digital in) <br>
4: A0(analog in/digital in) <br>
<br>
connector 3 <br>
:1 gnd <br>
2: 5v <br>
3: io3(i2c SCL/digital in/pwm out/interupt)<br>
4: io2(i2c SDA/digital in/interupt)<br>

Interupt is needed for encoder
