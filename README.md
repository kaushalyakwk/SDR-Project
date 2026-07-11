# Communication System Design using GNU Radio

A complete digital communication system designed and implemented using **GNU Radio**, featuring secure file transmission with **BPSK modulation**, **Forward Error Correction (FEC)**, and **AES/RSA encryption**. The project demonstrates both simulation and real-world transmission using Software Defined Radio (SDR).

## Overview

This project was developed as part of the **EN2130 - Communication Design Project** at the **University of Moratuwa**.

The communication system was designed to achieve:

- Reliable digital data transmission
- Secure communication
- Error detection and correction
- Resistance to channel impairments
- Real-world wireless transmission using SDR

## Features

- Digital communication system using GNU Radio
- Secure file transmission
- BPSK Digital Modulation
- Differential Encoding
- Forward Error Correction (Convolutional Coding)
- AES File Encryption
- RSA Key Exchange
- Software Defined Radio (SDR) implementation
- Simulation and over-the-air transmission
  
## System Architecture

```
File
 │
 ▼
AES Encryption
 │
 ▼
FEC Encoder
 │
 ▼
Differential Encoder
 │
 ▼
BPSK Modulator
 │
 ▼
SDR Transmission Channel
 │
 ▼
Receiver
 │
 ▼
Carrier & Clock Recovery
 │
 ▼
Demodulator
 │
 ▼
FEC Decoder
 │
 ▼
AES Decryption
 │
 ▼
Recovered File
```
<img width="632" height="253" alt="image" src="https://github.com/user-attachments/assets/50fe9db5-634e-49f6-b36e-946071f53ccd" />
<img width="706" height="390" alt="image" src="https://github.com/user-attachments/assets/aa9f826c-aff7-4d3c-a454-5cd891e27ac6" />
<img width="697" height="383" alt="image" src="https://github.com/user-attachments/assets/7d732d96-87ff-462d-89b0-7e2850de99a2" />


## Team

- H.M.C.N.K Bandara
- K.W.K Kaushalya
- G.W.C.M Luckshan
- A.C. Pasqual

Department of Electronic and Telecommunication Engineering

University of Moratuwa
