# pi-zero-adsb-tracker

![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20Zero%20WH-red?style=for-the-badge&logo=raspberry-pi)
![Frequency](https://img.shields.io/badge/Frequency-1090%20MHz-blue?style=for-the-badge)

A compact, low-power ADS-B aircraft tracking station built around a Raspberry Pi Zero WH and RTL-SDR receiver.

The system receives 1090 MHz ADS-B transmissions directly from aircraft, decodes flight information, and displays real-time aircraft positions on a local tracking interface.

Designed as a personal embedded systems project combining:
* Linux
* Software Defined Radio (SDR)
* RF communication
* Data processing
* Hardware prototyping

Currently deployed in Greece.

---

## 📡 Project Overview

Commercial aircraft broadcast ADS-B messages containing information such as:
* Aircraft identification
* Altitude
* Position
* Speed
* Heading
* Flight status

This project captures those signals using an RTL-SDR receiver and processes them using a Raspberry Pi Zero WH.

```text
Aircraft
   │
   │ 1090 MHz ADS-B broadcast
   ▼
ADS-B Antenna
   ▼
RTL-SDR Receiver
   ▼
Raspberry Pi Zero WH
   ▼
readsb (Decoder)
   ▼
tar1090 (Tracking Interface)
🛠 Hardware SetupBill of Materials (BOM)ComponentModelPurposeSBCRaspberry Pi Zero WHMain processing unitSDR ReceiverRTL-SDR (RTL2832U + R860)1090 MHz signal receptionStorageGoodRAM M1AA 32GB U1 Class 10Operating system and data storageUSB AdapterCablexpert Micro USB OTG splitterSDR connectivitySD Card ReaderEsperanza USB 2.0OS flashingEnclosureCustom homemade caseProtection and portabilityHardware DesignThe receiver was built with a focus on:Low power consumptionSmall footprintStandalone operationEasy maintenanceThe enclosure was manually designed and built to protect the electronics while keeping access to USB connections, power input, and the microSD card.(Add pictures here later)💻 Software StackLayerTechnologyOperating SystemRaspberry Pi OS (Debian-based Linux)ADS-B ProcessingreadsbVisualizationtar1090🚀 Development RoadmapPhase 1 — Hardware Validation ✅Acquire Raspberry Pi Zero WHSetup RTL-SDR receiverVerify 1090 MHz receptionAssemble physical hardwarePhase 2 — Software Setup ✅Install operating systemConfigure ADS-B decoderValidate decoded aircraft dataPhase 3 — Tracking Interface ✅Local aircraft mapReal-time aircraft informationWeb-based dashboardPhase 4 — Optimization 🔄Improve antenna performanceTune SDR settingsReduce power consumptionImprove enclosure designPhase 5 — Advanced Features ⏳Aircraft logging databaseHistorical flight trackingRemote monitoringNetwork data sharing📸 Gallery(Images coming soon)📚 Skills & TechnologiesHardware: Raspberry Pi, Software Defined Radio, RF communication, USB peripherals, electronics prototypingSoftware: Linux, Python, networking, data processing, embedded systems🎯 Project GoalsThis project was created to explore the intersection between Computer Science, Embedded Hardware, and Radio Communication.The goal is to develop practical experience designing, building, and documenting complete hardware/software systems.
