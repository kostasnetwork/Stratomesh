# pi-zero-adsb-tracker

![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20Zero%20WH-red?style=for-the-badge&logo=raspberry-pi)
![Frequency](https://img.shields.io/badge/Frequency-1090%20MHz-blue?style=for-the-badge)

A lightweight, low-power ADS-B aircraft tracking station built using a Raspberry Pi Zero WH and an RTL-SDR receiver.

The system receives real-time aircraft broadcasts on 1090 MHz, decodes ADS-B data, and displays aircraft information through a local tracking interface.

This project focuses on combining:
- Embedded hardware
- Software Defined Radio (SDR)
- Linux systems
- Networking
- Data processing

Built and tested in Greece.

---

## 📡 How It Works

Aircraft continuously broadcast ADS-B messages containing information such as:

- Aircraft identification
- Altitude
- Position
- Speed
- Heading

The receiver captures these transmissions using an RTL-SDR device and processes them using the Raspberry Pi Zero WH.

---

## 🛠️ Hardware Setup

The hardware used for this build:

- Raspberry Pi Zero WH (Pre-soldered headers)
- RTL-SDR USB Dongle (RTL2832U + R860 tuner)
- GoodRAM M1AA 32GB microSD (U1 Class 10)
- Cablexpert Micro USB to USB-A OTG splitter
- Esperanza USB 2.0 Card Reader
- Homemade custom enclosure

---

## 💻 Software Roadmap

### Phase 1: Hardware Setup ✅

- [x] Raspberry Pi Zero WH acquired
- [x] RTL-SDR receiver acquired
- [x] Hardware assembled
- [x] Custom enclosure created

---

### Phase 2: Software Installation

- [ ] Install operating system
- [ ] Configure RTL-SDR drivers
- [ ] Install ADS-B decoding software
- [ ] Test aircraft reception

---

### Phase 3: Tracking System

- [ ] Create local aircraft map
- [ ] Display real-time aircraft data
- [ ] Improve user interface

---

### Phase 4: Optimization

- [ ] Improve antenna setup
- [ ] Optimize SDR settings
- [ ] Reduce power consumption
- [ ] Improve enclosure design

---

### Phase 5: Advanced Features

- [ ] Aircraft data logging
- [ ] Historical flight database
- [ ] Remote monitoring
- [ ] Network data sharing

---

## 📸 Gallery

Images coming soon.

---

## 🎯 Project Goals

The goal of this project is to gain practical experience in:

- Embedded systems
- Radio communication
- Linux administration
- Hardware prototyping
- Software development

This project explores the connection between computer science and physical hardware systems.

---

## 📚 Technologies Used

Hardware:
- Raspberry Pi Zero WH
- RTL-SDR
- ADS-B 1090 MHz

Software:
- Linux
- ADS-B decoding software
- Networking tools
- Data visualization tools
