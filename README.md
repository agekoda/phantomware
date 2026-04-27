<div align="center">

  <img src="https://raw.githubusercontent.com/agekoda/phantomware/60c2e698cb4bf4e830aad41c31de2faca51849b3/phantomware%20logo.bmp" alt="logo" width="120" />
  
  <h1> phantomware </h1>
  <p> Compact, powerful ESP32-S3 platform for IR, NFC, sensors, WiFi & more. </p>


<!-- Badges -->
<a href="https://github.com/agekoda/phantomware" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=agekoda&message=phantomware&color=purple&logo=github" alt="agekoda - phantomware"></a>
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/agekoda/phantomware/total)
<a href="https://github.com/agekoda/phantomware"><img src="https://img.shields.io/github/stars/agekoda/phantomware?style=social" alt="stars - phantomware"></a>
<a href="https://github.com/agekoda/phantomware"><img src="https://img.shields.io/github/forks/agekoda/phantomware?style=social" alt="forks - phantomware"></a>

   
<h4>
  <a href="https://www.tiktok.com/@designedbykoda">
    <img src="https://cdn.simpleicons.org/tiktok/FFFFFF" width="22" style="margin: 0 8px;" />
  </a>

  <a href="https://www.youtube.com/@zdhd">
    <img src="https://cdn.simpleicons.org/youtube/FF0000" width="22" style="margin: 0 8px;" />
  </a>

  <a href="https://designedbykoda.com">
    <img src="https://github.com/agekoda/phantomware/blob/main/kodalogo.png?raw=true" width="70" style="margin: 0 8px;" />
  </a>
</h4>
</div>


## 🔥 Overview

Phantomware is a fully custom-built multi-tool device based on the ESP32-S3, designed for wireless analysis, signal interaction, and hardware experimentation.

It combines RF, GPIO, IR, and NFC capabilities into a portable platform featuring a 240×320 TFT display, SD card storage, and a 3000mAh battery system with a full charging circuit, MAX17055 fuel gauge, and built-in overcharge and overcurrent protection.

With 6 navigation buttons and a modular software framework, Phantomware is built for advanced IoT development, prototyping, and hardware exploration.

<div align="center"> 
  <img src="https://github.com/agekoda/phantomware/blob/main/images/all together.jpeg?raw=true" alt="screenshot" width="Auto" height="Auto" />
</div>

<div>&nbsp;</div>

## Phantomware vs. Flipper Zero

| Feature | Phantomware | Flipper Zero |
|--------|------------|----------------|
| Microcontroller | ESP32-S3 Dual-core Xtensa LX7 | STM32WB55RG |
| Bluetooth and WiFi? | Bluetooth 5 & WiFi 4 | Bluetooth 5.4 |
| Display | 2" 240x320 TFT LCD | 1.4" 128x64 Monochrome |
| IR Transceiver | 3x VSMY14940 LEDs + TSOP75348WTR | 3x VSMY14940 + TSOP75338TR |
| NFC Support | PN532 via SPI | ST25R3916 |
| Battery & Power Mgmt | 3000mAh LiPo + TP4056 + MAX17055 | 2100mAh + BQ25896 + BQ27220 |
| Expansion Options | Micro SD + 16 GPIOs | Micro SD + 18 GPIOs |
| Target Use Case | Signal analysis, RFID/NFC, IR, tinkering | Sub-GHz, RFID/NFC, IR, utility |
| Open Source? | Open Source & fully customisable | Open Source with limitations |
| Typical Price Point | ~$50 USD | ~$200 USD |

> [!NOTE]
> Information for Flipper Zero is based on publicly available specifications and may vary.

## 🚀 Features

### 🔌 GPIO Toolkit

* PWM signal generator
* Oscilloscope
* Frequency analyser
* Voltmeter
* Resistor calculator
* USB to UART bridge

### 📡 WiFi Tools *(educational use only)*

* Network scan
* Packet monitor
* Spectrum waterfall
* Deauthentication Attack
* Beacon spam
* Evil portal / Captive portal
* Access point hosting
* Connect to AP and host HTML

### 📶 Bluetooth Tools

* BLE scanning
* Device advertisement spam (Apple / Samsung / Windows)

### ⌨️ HID Tools

* BadUSB
* BadBT (Bluetooth HID attacks)

### 💬 Communication

* ESP-NOW messaging
* NRF24-based chat system

### 🧩 Expansion Support

* GPS modules
* PN532 NFC module
* Future GPIO-based add-ons

<!-- nRFBOX V2 -->
## 📸 Versions

<table>
  <tr>
    <td style="text-align: center;">
      <img src="https://github.com/agekoda/phantomware/blob/main/images/v1.jpeg?raw=true" alt="phantomware v1" style="width: 400px; border: 1px solid #ccc; border-radius: 5px;">
      <p style="font-style: italic; font-size: 14px; margin-top: 5px;">v1 prototype based on ESP32</p>
    </td>    
    <td style="text-align: center;">
      <img src="https://github.com/agekoda/phantomware/blob/main/images/v2.jpeg?raw=true" alt="phantomware v2" style="width: 400px; border: 1px solid #ccc; border-radius: 5px;">
      <p style="font-style: italic; font-size: 14px; margin-top: 5px;">v2 based on ESP32-S3</p>
    </td>
    </td>    
    <td style="text-align: center;">
      <img src="https://github.com/agekoda/phantomware/blob/main/images/v3.jpeg?raw=true" alt="phantomware v3" style="width: 400px; border: 1px solid #ccc; border-radius: 5px;">
      <p style="font-style: italic; font-size: 14px; margin-top: 5px;">v3 based on ESP32-S3 with PCBA and battery</p>
    </td>
  </tr>
</table>

## 🚨 Disclaimer

This project is intended for **educational and research purposes only**.

Do not use this device to interfere with networks, devices, or signals that you do not own or have explicit permission to test. Misuse may violate local laws and regulations.

<!-- License -->
## ⚠️ License

Distributed under the MIT License. See LICENSE.txt for more information.


<!-- Contact -->
## 🤝 Contact

Email - enquiries@designedbykoda.com

Project Link: [https://github.com/agekoda/phantomware](https://github.com/agekoda/phantomware)

<div>&nbsp;</div>
