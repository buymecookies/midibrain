# midibrain
all info about our midi brain

![final product](https://github.com/buymecookies/midibrain/assets/75701354/ffa3f018-6e46-451a-be11-b2918a3ee354)

The midi brain is based on an arduino pro micro. 
This shield will provide supercolider with io trough midi for our projects 


![alt text](https://www.bitsandparts.nl/partpics/0001FUNDUINOMINILEONARDO%5E3_hi.jpg)

## remote control

this module contains a 4 ch 433 mhz reciever. 

![alt text](https://hobbycomponents.com/2346-large_default/4-channel-433mhz-wireless-receiver-with-remote-fob.jpg)

The 4 gpio used for this module are: <br>

channel 1<br>
gpio: 14<br>
midinote:A1 <br>
<br>
channel 2<br>
gpio: 10<br>
midinote:A2 <br>
<br>
channel 3<br>
gpio: 15 <br>
midinote:A3 <br>
<br>
channel 4 <br>
gpio: 16<br>
midinote:A4 <br>
<br>


## External connections 
This module contains 3 external gpio connectors each connector has 4 pins <br>
![alt text](https://ae01.alicdn.com/kf/S81bbad23b49a4bfc8301678cb47c2a1dB/5-Paar-15edg-Kf2edg-3-5Mm-3-81Mm-3-96Mm-5-08Mm-Pcb-Schroef-Klemmenblok-2.jpg_80x80.jpg_.webp)<br>


From left to right<br>
<br>
connector 1 --standard 2 x button-- <br>
1: gnd <br>
2: 5v <br>
3: Gpio: io1/rx Midinote: B1 (serial tx/digital in/interupt) <br>
4: Gpio: io0/tx Midinote: B2 (serial rx/digital in/interupt) <br>
<br>
connector 2 --standard 2 x analog in-- <br>
1: gnd <br>
2: 5v <br>
3: gpio: A1 Midi: cc1 (analog in/digital in) <br>
4: Gpio: A0 Midi: c10 (analog in/digital in) <br>
<br>
connector 3 --standard 1x encoder in-- <br>
1: gnd <br>
2: 5v <br>
3: Gpio: io3 Midi: cc pan (i2c SCL/digital in/pwm out/interupt)<br>
4: Gpio: io2 Midi: cc pan (i2c SDA/digital in/interupt)<br>
Interupt is needed for encoder
