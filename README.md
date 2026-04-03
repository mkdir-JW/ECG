#  Multimodal ECG & Heart Sound Acquisition System

An engineering project focused on designing and implementing a system for multimodal acquisition and analysis of biomedical signals — electrocardiographic (ECG) and acoustic heart sounds (PCG).

---

## Project Description

The goal of this project was to develop a complete measurement system capable of simultaneously acquiring:

* electrical signals (ECG)
* acoustic signals (heart sounds)

and performing correlation analysis between them.

The system enables a deeper understanding of the relationship between the electrical and mechanical activity of the heart .

---

##  System Architecture

###  Hardware

* ECG front-end (AD8232)
* Microphone + amplifier (MAX4466)
* Microcontroller (STM32F429ZIT6)
* Data acquisition system (ADC + DMA)

###  Software

* Embedded firmware (C, STM32CubeIDE)
* Digital signal filtering (FIR)
* Data transmission (UART)
* Desktop application for visualization

---

##  Features

* 📡 simultaneous ECG and PCG acquisition
* 🧹 digital signal filtering
* 📈 time and frequency domain analysis (FFT)
* 🌊 time-frequency analysis (CWT)
* 🔗 correlation analysis between signals
* 📊 real-time signal visualization

---

##  Technologies

* Embedded C (STM32)
* Digital Signal Processing (DSP)
* FIR filters
* FFT / CWT
* UART communication
* Biomedical signal acquisition systems

---

##  Applications

* cardiac signal analysis
* biomedical research
* diagnostic support systems
* biomedical engineering education

---

##  Project Objectives

* design and build a complete measurement system
* analyze correlations between ECG and heart sounds
* demonstrate signal processing techniques in biomedical applications 

---

##  Disclaimer

This project is intended for educational and research purposes only and is not suitable for clinical use.

---

##  Author

Jakub Wołosz
Biomedical Engineering
Silesian University of Technology
