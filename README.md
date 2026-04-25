# Reggaeton Be Gone

![RBG](https://github.com/user-attachments/assets/82ae1932-0db3-41b7-aafb-94ccb48f4141)

## 🧷 Updated Alternative: Pocket Gone

If you want something simpler:

**Pocket Gone**

* 💸 Cheaper ($15 in parts)
* 🎒 Portable 
* 🔧 Easier to build 

👉 https://pocketgone.com

# 🎧🚫 Reggaeton Be Gone

Detects **reggaeton music** using Machine Learning and sends packets to disrupt nearby Bluetooth speakers 

---

## 🧠 Overview

Reggaeton Be Gone is an experimental Raspberry Pi device that:

* 🎙️ Captures audio input
* 🤖 Classifies genre using an ML model
* 📡 Triggers a Bluetooth interference routine when reggaeton is detected

Focus areas: **edge ML**, **audio classification**, **RF experimentation**

---

## 🧰 Hardware

* 🖥️ Raspberry Pi 3
  https://www.dfrobot.com/product-1703.html

* 📟 DFRobot OLED 128x32 Display
  https://www.dfrobot.com/product-2018.html

* 🔘 Push Button
  https://www.dfrobot.com/product-1098.html

* 📶 Bluetooth Audio Receiver 5.0
  https://www.dfrobot.com/product-2085.html

* 🔌 Jumper cables

* ⚡ Power supply: **5V / 3A**

---

## 🤖 Machine Learning

* Trained with **Edge Impulse**
  https://edgeimpulse.com/

* 🎵 Audio classification model for reggaeton detection

* 📦 Planned: public `.eim` file or open project for cloning

---

## 🔌 Wiring

### 📟 OLED Display

```
SDA  → GPIO 2  
SCL  → GPIO 3  
VCC  → 3.3V / 5V  
GND  → GND  
```

### 🔘 Button

```
Pin 1 → GPIO 26  
Pin 2 → GND  
```

---

## ⚙️ How It Works

1. 🎙️ Capture audio
2. 🤖 Run inference locally
3. 🚫 If reggaeton detected:

   * 📡 Send Bluetooth packets
   * 🔇 Attempt to disrupt nearby speakers

---

## 🧪 Versions

### 🧩 v2.0 (Experimental)

* Built for Nerdearla Chile
* Incremental improvements

### 🧩 v3.0 (Experimental)

* Built for Ekoparty
* Includes:

  * 📡 On-device scan
  * 🎯 Strike system (reduce false positives)
  * 🤖 Improved ML model
  * 🧱 Enclosure + full package

👉 https://www.patreon.com/RoniBandini/shop/reggaeton-be-gone-version-experimental-3-860409

---

## 📚 Full Instructions

* 🇬🇧 https://www.hackster.io/roni-bandini/reggaeton-be-gone-e5b6e2
* 🇪🇸 https://www.youtube.com/watch?v=sPcHeiP9Xgg

---

## ⚠️ Disclaimer

* 🧪 Experimental project
* ⚖️ May be restricted by local regulations

Use responsibly.

---

## 📬 Contact

* 📸 https://www.instagram.com/ronibandini/
* 🐦 https://x.com/RoniBandini
* 💼 https://www.linkedin.com/in/ronibandini/

---
