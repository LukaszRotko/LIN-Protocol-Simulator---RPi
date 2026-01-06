# Implementation of the LIN Communication Protocol in a Microcontroller-Based Device

This repository contains the **presentation of an engineering thesis** focused on the implementation of the **LIN (Local Interconnect Network) communication protocol** in a device based on a **Raspberry Pi Pico (RP2040) microcontroller**.

## 📌 General Information

- **Author:** Łukasz Rotko  
- **Supervisor:** Dr. Eng. Jerzy Białas  
- **University:** Cracow University of Technology  
- **Faculty:** Faculty of Computer Science and Telecommunications  
- **Degree Program:** Computer Science  
- **Year:** 2024  

## 🎯 Thesis Objective

The main objective of the thesis was to design and implement software enabling communication using the **LIN protocol** on a microcontroller-based device.  
The solution was created as a **flexible testing and diagnostic tool**, primarily intended for applications in the automotive domain.

## 🛠️ Scope of Work

The thesis covers:

- Analysis of the LIN communication protocol based on ISO standards  
- Comparison and selection of a suitable microcontroller platform  
- Implementation of the LIN protocol using **programmable I/O (PIO)**  
- Development of a LIN master device capable of:
  - Sending commands and diagnostic requests  
  - Receiving and decoding responses  
  - Verifying checksums and frame structure  
- Use of **multithreading** to enable simultaneous transmission and reception  
- Presentation and validation of the solution through practical tests  

## 💻 Technologies and Tools

- **Hardware:** Raspberry Pi Pico (RP2040)  
- **Programming Language:** MicroPython  
- **Key Libraries and Modules:**
  - `rp2` (PIO state machines)
  - `machine`
  - `_thread`
  - `gc`, `time`, `sys`
- **Development Tools:**
  - Thonny IDE (prototyping)
  - PyCharm + rshell (final development and automation)

## 📊 Presentation Content

The presentation included in this repository covers:

- Motivation and problem statement  
- LIN protocol structure and timing requirements  
- Hardware and platform selection rationale  
- Software architecture and PIO-based implementation  
- Multithreaded data reception approach  
- Test results, limitations, and potential improvements  
- Final conclusions  

## 🔒 Source Code Availability

The **source code is not included in this repository**.

The implementation code is maintained in a **separate private repository** and can be made available **upon request from the author**.

## 📄 License

This repository is intended for **educational and presentation purposes** only.
