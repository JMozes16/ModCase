## EPD 4.2 inch 3 color hardware:

### Arduino Nano
![IMG_5786](https://github.com/JMozes16/ModCase/assets/85561037/70c8da3e-7211-4619-9a42-e0f6db115bc7)

### 4.2 EPD Front
![IMG_5787](https://github.com/JMozes16/ModCase/assets/85561037/5b546c97-cfa4-4a3e-af61-ca5c6eeafd98)

### 4.2 EPD Back
![IMG_5788](https://github.com/JMozes16/ModCase/assets/85561037/4bc9e0af-2da2-4dbe-9a1b-626d0efb11be)

### Important note
The Arduino nano only has a memory of 32Kb. And to cover the entire 4.01 inch EPD, there are 256Kb required, so an ESP32 or Raspberry Pi need to be looked into to get full display images.

### Connection (4.2 inch ePaper Module rev2.1 V2 to Arduino NANO)

BUSY : D7  
RST : D8  
DC : D9  
CS : D10  
CLK : D13  
DIN : D11  
GND : GND  
VCC : 3V3  
