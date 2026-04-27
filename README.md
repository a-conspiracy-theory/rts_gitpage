# Coma Patient Monitor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![View Site](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/a-conspiracy-theory/rts-coma-monitor)

A concise, one-sentence description of what this project does and who it is for.

## Project Description
This project aims to implement a coma patient monitoring system. Its main job is patient stability sensing. It is able to track a patients heart rate, their blood oxygen level, and their temperature. If detected values exceed a given range, the system will enter a critical state. This critical state will alert the acting nurse who will then call a hospital code depending on severity. This project also implements a monitoring web portal which displays extra data, such as heart rate history and exact critical state information. The emergency state can be toggled from this webpage or from a button on the device if it is required.

## ✨ Key Features
* **Web Portal:** A simple, concise web portal tracks all important patient info.
* **Broad Sensing:** Three separate patient vitals are tracked, ensuring absolute knowledge of state.
* **Intense Signaling:** Bright LED state monitors and large webpage changes ensure acting personel are informed of patient state changes.

## 🛠️ Tech Stack
* **Core:** An ESP32 microcontroller effortlessly keeps the system running with 50-ms deadlines
* **Kernel:** The FreeRTOS kernel ensures strict timing requirements are kept, so you always know how your patient is doing
* **Software:** Lightweight software means efficient, fast execution. Never worry about sensor lag or notification delay.
