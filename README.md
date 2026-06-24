# Gizmo 2.0
## Description
Gizmo 2.0 is generally a small desk robot that acts as an AI companion whose only mission is to interact with you, dance with you, and even brainstorm with you. Gizmo 2.0 can help you organize your thoughts, and he gives incredible answers for any questions you ask him. Also, he is provided with a mic for voice and music recognition. So, you can have a little party with him, and it has 2 servo motors that act as joints for his arms, which are mainly used for dancing and interaction with his owner.

Gizmo was made after a lot of research and thinking i had like a really long time seeing totorial and example on the internet to see how to make a moving AI companian and which MCU to get and what could be its abailities so i used ESP32-S3 as the main MCU, inmp441 as a microphone, a speaker, 2 servo motors and a customed PCB to hold every thing together.

## Why it was biult
I had a really good time designing Gizmo as I made a unique 3D design with inspiration from EVE in the Wall-E robot film. As a kid I loved this character so much, and since it was really quiet and charming, it was like a new technology on earth to clean the planet, but I made it a little different. I made it to be like a moving thing on my desk to dance with me and interact with me when having long programming or designing sessions. Gizmo will be there for you. I wanted to make it with a moving wheels but i couldn't get a good design as well as that my desk is not that big for a moving robot So i ended up by making a static one with moving arms and a big processer which is the ESP32-S3.

There is another good reaseon for building Gizmo which is the amount of memories and thoughsts i gave into biulding it. Since this is my last project before attendign fallout which is a hackathon organized by Hack Club in shenzhen and i can't wait to go.

## How to use it / Build it
The first step of constructing Gizmo 2.0 is fabricating the PCB since it will be one of the main parts of the prototype. Also, you need it since the prototype doesn't have any additional space to maintain the electronics without the PCB. So, after fabricating the PCB, you should buy the components as well as jumpers and long wires for the LCD, speaker, and servo motors. After that you should 3D print the parts I provided in the repo, and for each part there is a compatible part in the main body, which will hold everything from servo motors to the connector and the head, which is part 5 or head connector; this connects to the neck of the head part.

Now we start the assembly. First of all, get your LCD and glue it to the front head part, then glue the speaker to the back head part, and assemble the 2 parts using the neck I provided, which has a place to hold all these parts together. After this, get the base and add the PCB after assembling everything and uploading the firmware. and close the base with the top part of the base and then assemble the main body and the servo motor holder and glue the servo motors to the part, then glue the arm to the servo motor after it to the main body after assembling the arms to the body. Now you have a full working prototype.

## CAD
I made this 3D design using onshape software, it was like a new experience for me to design a small prototype like a robot with this components so i had a new experience and i made every thing with smth like joints to hold it together. Also i added my name and HC for Hack Club.
And this is the design link:
https://cad.onshape.com/documents/7c9149f39106583a98e32532/w/5ca8de735c404b6ef83d1411/e/55ea2a7bab61e22144a448e0?renderMode=0&uiState=6a34a954f7594a7258307f8a
<br>
<img width="627" height="706" alt="image" src="https://github.com/user-attachments/assets/58306a0e-3791-4f22-a9d6-c4937bf7ce00" />
<img width="577" height="761" alt="Screenshot 2026-06-19 024403" src="https://github.com/user-attachments/assets/225fd1ff-2a44-4003-81b5-088edb300545" />


## Schematic
This is a simple diagram for my circiut it havethenamea small introduction a digra for whot will the system work and 2 systems the power and the ESP32-S3 connections
<img width="1170" height="838" alt="image" src="https://github.com/user-attachments/assets/0edfb5d5-1c9d-44a0-92c0-0cc3946cfa63" />

## PCB design
A polished PCB design with a copper filled zone to my GND net also i assimblied it many times until i got this one with no problems.
<img width="655" height="472" alt="image" src="https://github.com/user-attachments/assets/66cdaca6-1bef-4d31-ac1c-3c29388567cf" />

## Magazine
<img width="545" height="835" alt="Gizmo 2 0 Zine" src="https://github.com/user-attachments/assets/45531ff8-8ec6-4704-b33c-3bad3f668d88" />

## BOM

| Item | Price | Quan. | Place | Link |
| :--- | :---: | :---: | :--- | :--- |
| ESP32-s3 | 10.55 | 1 | future electronics | [View Item](https://store.fut-electronics.com/products/esp32-s3-devkitc-1?srsltid=AfmBOoo5ok_RH336v4kgNkFmU0aAF1dDe45BG5KH02IJx1Rra65h0LNp) |
| ESP32 Camera OV5640 | 7.58 | 1 | makers | [View Item](https://makerselectronics.com/product/banana-pi-camera-ov5640-160-degree-5mp/?srsltid=AfmBOoqwwII_0DwU1h8Btitem8w31jUf-n4unO7NtXqaaZ5AVWlHgDsY) |
| 18650 Lithium Ion Rechargeable | 4.62 | 2 | future electronics | [View Item](https://fut-electronics.com) |
| AMS1117 3.3V Step-Down | 1 | 1 | micro ohm | [View Item](https://microohm-eg.com/ams1117-3-3-ldo-800ma-dc-5v-to-3-3v-step-down-power-supply-module/) |
| Step Down 5A XL4015 | 1.63 | 1 | micro ohm | [View Item](https://microohm-eg.com/dc-dc-step-down-converter-variable-5a-xl4015/) |
| BMS 2S 13A Lithium Battery Protection Board | 1.5 | 1 | micro ohm | [View Item](https://microohm-eg.com/2s-13a-18650-7-4v-8-4v-lithium-battery-protection-board/?utm_source=chatgpt.com) |
| 2S 8.4V 2A 18650 Lithium Battery Charger Module USB Type C | | 1 | ram electronics | [View Item](https://www.ram-e-shop.com/ar/shop/kit-li-2s-charger-2s-8-4v-2a-18650-lithium-battery-charger-module-usb-type-c-9295?srsltid=AfmBOoqNP3OFFPA_uS9me429NkSkgtTsNjoG1qEyEM67Y3l1D3-WlItv) |
| inm441 | 5.25 | 1 | Ali express | [View Item](https://ar.aliexpress.com/item/32934187800.html?gatewayAdapt=glo2ara) |
| i2s amplifier (max 98357) | 2.6 | 1 | future electronics | [View Item](https://store.fut-electronics.com/products/max98357-i2s-3w-class-d-amplifier-audio-decoder-module?srsltid=AfmBOoqAc6RcUHtToGTEkW9skKCJ9fX_xuc7YFtfUabfdsT7n0q2HLyD) |
| Speaker - 3W 4 Ohm | 1.54 | 1 | future electronics | [View Item](https://store.fut-electronics.com/products/speaker-3w-4-ohm?srsltid=AfmBOopv4otZbRL29DhJ3REfWfF-85G6EDgruAXGc6kVUNDOp2_l61lA) |
| LCD Module 1.28 inch Round Display | 9 | 1 | micro ohm | [View Item](https://microohm-eg.com/round-lcd-module-1-28-inch-240x240-ips-color-with-gc9a01-controller/) |
| TTP223 Capacitive Touch Sensor | 0.29 | 2 | makers | [View Item](https://makerselectronics.com/product/ttp223-capacitive-touch-sensor-module/?srsltid=AfmBOop7F_AzNeOoilzYLkXKq8DPKwVegbdnGAW85MecGYuK8TcNj0Ez) |
| 1.3 kg.cm servo | 2 | 2 | Circuits electronics | [View Item](https://circuits-elec.com/products/servo-motor-1-3-kg-cm-standard?srsltid=AfmBOoorhdeY6_q4NXN0ngcBwieEeBY9QWrYb_PrgZwciAxm65uJPD-Y) |
| PCB fabrication | 5 | 1 | JLCPCB | |
| 3D design | 20 | | | |
| **Total** | **75** | | | |
