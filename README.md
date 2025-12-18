[14:15, 16/12/2025] Dubz: # Non-Contact Temperature-Based Sanitization System

## Project Status
Working hardware prototype (proof-of-concept)

## Description
This project is a non-contact automatic sanitization system that measures
body temperature using an infrared temperature sensor and dispenses sanitizer
when a valid temperature is detected. The system was built and tested on a
breadboard to validate functionality.

## Features
- Non-contact temperature sensing
- Automatic sanitizer dispensing
- Relay-controlled pump
- External power isolation for motor safety

## Hardware Used
- Arduino Uno
- MLX90614 IR Temperature Sensor
- Relay Module
- DC Pump

## System Operation
1. IR sensor reads object temperature
2. Microcontroller evaluates temperature threshold
3. Relay activates pump if conditions are met
4. Sanitizer is dispensed automatically

## Limitations
- Breadboard-based prototype
- No enclosure
- Basic firmware logic

## Future Improvements
- PCB design
- LCD/OLED display
- IoT monitoring
- Enclosure and safety improvements

## Demo
See working prototype video in /media/demo_video_link.txt
[14:40, 16/12/2025] Dubz: # AI Tutor for the Visually Impaired

## Project Status
Working hardware and software prototype (proof-of-concept)

## Description
This project is an AI-based assistive learning system designed to help visually
impaired users interact with educational content using voice-based input and
audio feedback. The system processes spoken commands and responds with
audio output, enabling hands-free and screen-free learning.

The project focuses on accessibility, simplicity, and real-time interaction
using embedded hardware and basic AI concepts.

## Features
- Voice-based user interaction
- Audio feedback for responses
- Assistive learning support
- Hands-free operation
- Designed for visually impaired users

## Hardware Used
- Microcontroller / Single Board Computer (specify if Arduino, ESP32, Raspberry Pi)
- Microphone module
- Speaker or audio output module
- Power supply
- Breadboard and jumper wires

## Software / Technologies
- Embedded C / Python (depending on implementation)
- Basic AI / logic-based response system
- Audio input and output handling

## System Operation
1. The user speaks a command or question.
2. The microphone captures the audio input.
3. The system processes the input using predefined logic or AI-based processing.
4. An appropriate response is generated.
5. The response is played back as audio through a speaker.

## Limitations
- Prototype-level implementation
- Limited vocabulary or predefined responses
- No enclosure or optimized hardware design

## Future Improvements
- Integration of advanced AI/NLP models
- Cloud-based knowledge access
- Improved speech recognition accuracy
- Portable enclosure design
- Multi-language support

## Demo
A working demonstration video is available in the media/demo_video_link.txt file.