# Coma Patient Monitor

[![View Site](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/a-conspiracy-theory/rts-coma-monitor)

Accurate & fast monitoring service for unconsious patients

## Project Description
This project aims to implement a coma patient monitoring system. Its main job is patient stability sensing. It is able to track a patients heart rate, blood oxygen level, and temperature. If detected values exceed a given range, the system will enter a critical state. This critical state will alert the acting nurse who will then call a hospital code depending on severity. This project also implements a monitoring web portal which displays extra data, such as heart rate history and exact critical state information. The emergency state can be toggled from this webpage or from a button on the device if it is required.

{% include youtube.html id="2YpgbN0muC4" %}

---

## Key Features
* **Web Portal:** A simple, concise web portal tracks all important patient info.
* **Broad Sensing:** Three separate patient vitals are tracked, ensuring absolute knowledge of state.
* **Intense Signaling:** Bright LED state monitors and large webpage changes ensure acting personel are immediately informed of patient state changes.

## Tech Stack
* **Core:** An ESP32 microcontroller effortlessly keeps the system running with 50-ms deadlines
* **Kernel:** The FreeRTOS kernel ensures strict timing requirements are kept, so you always know how your patient is doing
* **Software:** Lightweight software means efficient, fast execution. Never worry about sensor lag or notification delay.
