<h1 align="center">Hi, I'm Ezra 👋</h1>

<p align="center">
  Building real-time embedded projects where code meets hardware, from ESP32 firmware to DMX stage lighting.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino" />
  <img src="https://img.shields.io/badge/FreeRTOS-5D9B3A?style=for-the-badge" alt="FreeRTOS" />
</p>

---

## About Me

- 🔧 I build embedded systems that run in real time and react to the physical world.
- 🎛️ My focus is lighting control, audio input and signal processing on microcontrollers.
- 🧵 I care about clean architecture: fixed-rate tasks, no shared-state surprises, and code other people can read.
<!-- Add your own lines here, for example: where you're based, what you're studying or working on, what you're learning, or what you want to collaborate on. -->

---

## Featured Project

### [ESP32 DMX Sound Reactive Lighting](https://github.com/itzRealEzra/Esp32-DMX-Sound-Reactive-Lighting)

A real-time DMX512 lighting controller. An ESP32 listens through a MAX9814 microphone, measures the room level against its own background noise, and drives a PAR light and a moving head to match.

| | |
| --- | --- |
| **Output** | DMX512 over RS485 at 50 Hz |
| **Input** | MAX9814 microphone on the ESP32 ADC |
| **Behavior** | Level zones from white through red, green and blue to a rainbow cycle with strobe |
| **Design** | Fixed-rate FreeRTOS DMX task, with the microphone loop kept separate so slow reads never stall the lights |

---

## Tech Stack

| Area | Tools |
| --- | --- |
| **Languages** | C, C++ |
| **Platforms** | ESP32, Arduino framework |
| **Protocols** | DMX512, RS485, UART |
| **Concepts** | FreeRTOS tasks, ADC sampling, RMS and dB level detection, real-time scheduling |

---

## Get in Touch

<p>
  <a href="https://github.com/itzRealEzra"><img src="https://img.shields.io/badge/GitHub-itzRealEzra-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <!-- Add more links if you want them, for example:
  <a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-you@example.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/your-handle"><img src="https://img.shields.io/badge/LinkedIn-your--handle-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  -->
</p>

Feel free to open an issue on any of my repositories if you have questions or ideas.

---

<p align="center">
  <sub>Thanks for stopping by ✨</sub>
</p>
