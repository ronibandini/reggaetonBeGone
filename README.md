# Reggaeton Be Gone

![RBG](https://github.com/user-attachments/assets/82ae1932-0db3-41b7-aafb-94ccb48f4141)

Detects reggaeton musical genre with Machine Learning and sends packets to disable BT speakers (hopefully)

# Parts 
Raspberry Pi 3 https://www.dfrobot.com/product-1703.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP

DFRobot Oled 128x32 screen https://www.dfrobot.com/product-2018.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP

Push button https://www.dfrobot.com/product-1098.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP

BT Audio Receiver 5.0 (to test with your own BT) https://www.dfrobot.com/product-2085.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP 

Jumper cables

# Machine Learning
Model trained using Edge Impulse platform https://edgeimpulse.com/ (free account for developers)
I will soon post the eim file or make public my project for cloning

# Complete Instructions
English https://www.hackster.io/roni-bandini/reggaeton-be-gone-e5b6e2
Spanish workshop https://www.youtube.com/watch?v=sPcHeiP9Xgg

# Connections
Oled SDA ->  Rpi GPIO 2
Oled SCL -> Rpi GPIO 3
Oled VCC -> Rpi VCC
Oled GND -> Rpi GND

Button pin 1 -> GPIO26
Button pin 2 -> GND

Power supply: 5V 3A

# 2.0 Experimental version
This version was made for the Nerdearla Chile workshop. It includes several enhancements  

# 3.0 Experimental version
This version was made for Ekoparty workshop and it was given for free to the participants. It includes on device scan, strike to avoid false positives, better ML model and more. You can get this version (software, 3d enclosure and ML model) at https://www.patreon.com/RoniBandini/shop/reggaeton-be-gone-version-experimental-3-860409 

# Pocket Gone

Reggaeton Be Gone is not an easy device to make. Besides, most people just need a simple way to disable loud Bluetooth speakers. I have another device called Pocket Gone—cheaper, portable, and easy to make. You can sign up for the asynchronous workshop and build your own. https://www.patreon.com/RoniBandini/shop/taller-virtual-de-pocket-gone-945256 

# Contact
Customizations, prototyping, maker or AI talks? 

Roni Bandini
https://www.instagram.com/ronibandini/
https://x.com/RoniBandini
https://www.linkedin.com/in/ronibandini/
