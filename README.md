# STM32 UART Communication Project 🎵💡
![imageBreadboard](https://github.com/user-attachments/assets/d712668e-eccf-4565-b22a-25f33acc7566)

This project demonstrates **UART communication** between an **STM32F103C8T6 Blue Pill** board and an **STM32F746 Discovery** board.  
 **This Code is Related to STM32F103C8T6 BluePill Board**
---

- The **STM32F7 Discovery** board hosts a **GUI (HMI)** that sends commands via UART.  
- The **STM32F1 Blue Pill** board receives the commands and:  
  - Plays sound through a buzzer 🎶  
  - Controls an LED that "dances" with the sound 💡  
---
### Features
- 4 distinct sounds at different frequencies  
- Ability to stop the sound  
- LED animation synchronized with the buzzer  
---
### Pin Configuration (STM32F103C8T6)
- **PC13** → LED  
- **PC14** → Buzzer  
---
### UART Settings
- **USART1** is enabled for communication  
---
### Demo
📺 Full project demo is available on the [Sly Fox Electronics YouTube Channel](https://www.youtube.com/@slyfoxelectronics).
