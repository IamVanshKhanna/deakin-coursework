# SIT210 – Task 3.1P: Real-Time Temperature Monitor with Temperature Indicator

> Arduino IoT Cloud · Arduino Nano 33 IoT · DHT22 · C++ · Vansh Khanna

A real-time IoT project that monitors temperature and humidity using a **DHT22 sensor** on an **Arduino Nano 33 IoT**, streams data to the **Arduino IoT Cloud**, and displays live readings on a cloud dashboard with a temperature indicator widget.

---

## Project Overview

| Detail | Value |
|---|---|
| Unit | SIT210 – Embedded Systems |
| Task | 3.1P – Arduino IoT Cloud Integration |
| Board | Arduino Nano 33 IoT |
| Sensor | DHT22 (temperature & humidity) |
| Platform | Arduino IoT Cloud |

---

## Hardware List

| Component | Purpose |
|---|---|
| Arduino Nano 33 IoT | Wi-Fi-enabled microcontroller |
| DHT22 Sensor | Temperature & humidity readings |
| Jumper wires & breadboard | Circuit assembly |

---

## Circuit Layout

See [`Layout.jfif`](./Layout.jfif) for the wiring diagram.

- DHT22 **VCC** → 3.3V
- DHT22 **GND** → GND
- DHT22 **DATA** → Digital pin (as configured in `thingProperties.h`)

---

## Arduino IoT Cloud Setup

1. Create a **Thing** in [Arduino IoT Cloud](https://create.arduino.cc/iot)
2. Add two Cloud variables: `temperature` (float) and `humidity` (float)
3. Download the generated `thingProperties.h` (already included in this repo)
4. Open `sketch123.ino` in Arduino IDE or Arduino Cloud editor
5. Add your Wi-Fi credentials and device secret to `arduino_secrets.h`
6. Upload to your Nano 33 IoT
7. Open the Dashboard (see [`Dashboard.png`](./Dashboard.png)) to view live data

---

## Files

| File | Description |
|---|---|
| `sketch123.ino` | Main Arduino sketch |
| `thingProperties.h` | Auto-generated IoT Cloud variable bindings |
| `arduino_secrets.h` | Wi-Fi SSID/password & device secret (keep private) |
| `Dashboard.png` | Screenshot of the Arduino IoT Cloud dashboard |
| `Layout.jfif` | Circuit wiring diagram |

---

## What I Learned

- Connecting an Arduino board to the cloud using Arduino IoT Cloud
- Defining and syncing cloud variables that update in real time
- Building a live dashboard with indicator and gauge widgets
- Handling sensor data (DHT22) and transmitting it over Wi-Fi
- Managing secrets safely with `arduino_secrets.h`

---

*Vansh Khanna — VK7160 · SIT210 Embedded Systems*
