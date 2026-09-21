# 🔦 Morse Code via Laser – ASK Modulation

A MATLAB-based simulation of Morse code transmission using
Amplitude Shift Keying (ASK) through laser ON/OFF modulation.

## 📌 Project Overview

This project demonstrates digital optical communication using
Morse code and Amplitude Shift Keying (ASK).

The system converts text messages into Morse code and represents
the coded information using laser ON/OFF pulses.

It also supports decoding Morse code back into readable text.

## 🎯 Objectives

- Implement Morse code encoding and decoding.
- Demonstrate ASK-based digital optical communication.
- Generate laser ON/OFF waveforms representing binary data.
- Visualize the transmitted signal in the time domain.
- Understand the basic concept of optical digital communication.

## ⚙️ Working Principle

The system uses two amplitude levels:

- Logic 1 → Laser ON
- Logic 0 → Laser OFF

Morse code is represented using different durations of laser
ON and OFF states.

### Morse Representation

- Dot (.) → Short laser ON pulse
- Dash (-) → Long laser ON pulse
- Space → Laser OFF period

The text is first converted into Morse code and then converted
into an ASK waveform representing the optical transmission.

## 🔄 System Flow

Text Input
    ↓
Morse Code Encoding
    ↓
ASK / ON-OFF Modulation
    ↓
Laser ON/OFF Waveform
    ↓
Transmission Visualization

For decoding:

Morse Code Input
    ↓
Morse Code Decoder
    ↓
Decoded Text

## 🖥️ Features

- Letters → Morse Code conversion
- Morse Code → Letters conversion
- ASK waveform generation
- Time-domain waveform visualization
- GUI-based MATLAB interface
- Support for alphabetic characters

## 🛠️ Software Requirements

- MATLAB R2021 or later
- Signal Processing Toolbox
- MATLAB plotting functions

## 📊 ASK Waveform

The generated waveform represents the optical transmission
using ON and OFF signal levels.

A dot produces a short-duration ON pulse, while a dash produces
a longer ON pulse. Gaps are represented by OFF periods.

## 💻 How to Run

1. Install MATLAB R2021 or later.
2. Open the project folder in MATLAB.
3. Open `morse_gui.m`.
4. Run the MATLAB script.
5. Select one of the available modes:
   - Letters → Morse
   - Morse → Letters
6. Enter the required text or Morse code.
7. Click the Convert button.
8. View the converted output and ASK waveform.

## 📈 Results

The simulation successfully demonstrates:

- Text to Morse code conversion.
- Morse code to text decoding.
- ASK waveform generation.
- ON/OFF transitions representing optical data transmission.
- Visualization of the transmitted signal in the time domain.

## 🧠 Concepts Demonstrated

- Amplitude Shift Keying (ASK)
- On-Off Keying
- Morse Code
- Digital Communication
- Optical Communication
- Signal Encoding and Decoding
- Time-Domain Signal Representation
- MATLAB GUI Development

## 🚀 Future Scope

The simulation can be extended into a hardware-based optical
communication system using:

- Laser diode transmitter
- Photodiode receiver
- Microcontroller or embedded processor
- Real-time optical data transmission

## 📚 References

- Simon Haykin, *Communication Systems*, 5th Edition
- J. G. Proakis, *Digital Communications*, 4th Edition
- MATLAB Documentation
