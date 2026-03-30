# PCB BADGE
This project was mainly build for blueprint Build Guild Meetup this is a 85.6 x 54 mm sized board (proply a size of credit card) this has few leds, oled display and esp32.. 
![image1](https://raw.githubusercontent.com/thagreatjoel/Build-Guild-PCB/refs/heads/main/img/Screenshot%20From%202026-03-30%2019-30-12.png)
![image2](https://raw.githubusercontent.com/thagreatjoel/Build-Guild-PCB/refs/heads/main/img/Screenshot%20From%202026-03-30%2019-30-40.png)

# Describe PCB
So like it is used as an id card. where they can add there names or whatever in the oled. Also they can many parterns of animation for the leds. the animation pattern can be change with the mode butoon given there. I used the pads instead of the button for BOOT and RESET.. it give more space and less componets.(basically i wanted to be less crowded) 

# Key Elements
We have main controller as ESP32C3, CH340 for programing, AMS1118 3.3v voltage regulator. TP4056 for charger (exactly i used the whole module - i was bit lazy ik), USB Type-C for programing and power ofc.., and a lipo battery. i recommend to use around 3.7-4.5v..

# Specs
- MCU: ESP32C3
- 0.91'inch Oled Display
- 8 LEDS
- Arduino IDE
- C-Type Power
- Charging Module: TP4056
- Can Be Programmed through Arduino IDE
