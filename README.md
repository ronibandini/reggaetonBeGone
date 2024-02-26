# Reggaeton Be Gone
Detects reggaeton musical genre with Machine Learning and sends packets to disable BT speakers (hopefully)

# Parts 
Raspberry Pi 3 https://www.dfrobot.com/product-1703.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP
DFRobot Oled 128x32 screen https://www.dfrobot.com/product-2018.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP
Push button https://www.dfrobot.com/product-1098.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP
BT Audio Receiver 5.0 (to test with your own BT) https://www.dfrobot.com/product-2085.html?tracking=hOuIhw4fDaJRTdy4abz04npbQC78dqxBkqVt7XMFYxEXj2s0ukWgm71wbut0ewUP 
Jumper cables

# Machine Learning
Model trained using Edge Impulse platform https://edgeimpulse.com/ (free account for developers)
Clone the repository, Deploy to Linux, ARM. Upload to Rpi, Change permissions to 744

# Connections
Oled SDA ->  Rpi GPIO 2
Oled SCL -> Rpi GPIO 3
Oled VCC -> Rpi VCC
Oled GND -> Rpi GND

Button pin 1 -> GPIO26
Button pin 2 -> GND

Power supply: 5V 3A

# Contact
Roni Bandini, @RoniBandini
