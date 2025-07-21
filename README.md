# ESP32 Based 2-Layer PCB - KiCad

**A professionally redesigned 2-layer remote sensing PCB, converted from a 4-layer design with advanced thermal management and power distribution optimization.**

## 📋 Project Overview

This repository contains the complete **KiCad project files** for a **2-layer ESP32-based remote sensing and data logging PCB**. The design has been optimized from a previous 4-layer implementation, featuring improved thermal management, power distribution, and cost-effective manufacturing.

### Key Components
- **ESP32-C3 SoC** - WiFi/Bluetooth enabled microcontroller
- **BME280 Environmental Sensor** - Temperature, Humidity, Pressure monitoring
- **MicroSD Card Interface** - Data storage and logging capability
- **Onboard 3.3V Regulator** - Clean power supply with star topology distribution
- **USB-C Connector** - Modern charging and programming interface

## 🎯 Design Evolution & Improvements

| **Feature** | **Previous Design** | **Current Design** | **Improvement** |
|-------------|--------------------|--------------------|-----------------|
| **PCB Layers** | 4-layer stackup | 2-layer design | **60% cost reduction** |
| **Storage Interface** | Large SD card slot | Compact microSD | **Space optimization** |
| **Sensor Placement** | Near ESP32 (heat affected) | Top-left isolation | **Higher accuracy** |
| **Power Distribution** | Standard routing | Star topology (VR1 hub) | **Noise reduction** |
| **Form Factor** | Larger footprint | Compact rectangular | **Better integration** |

## 🔧 Technical Specifications

### **Hardware Features**
- **Microcontroller**: ESP32-C3 RISC-V single-core processor
- **Connectivity**: WiFi 802.11 b/g/n, Bluetooth 5.0 LE
- **Environmental Sensing**: BME280 with I2C interface
- **Data Storage**: MicroSD card (up to 32GB)
- **Power Supply**: 3.3V regulated, star topology distribution
- **PCB Design**: 2-layer, optimized for manufacturing

### **Physical Specifications**
- **Board Layers**: 2 (Top: 3.3V + Signals, Bottom: GND + Routing)
- **PCB Thickness**: 1.6mm standard
- **Component Count**: ~50 components
- **Mounting**: 4x mounting holes for mechanical stability
- **Connectors**: Edge-mounted for enclosure compatibility

## 🎨 Design Philosophy

### **Thermal Management**
- **BME280 Repositioning**: Moved to top-left corner to minimize thermal interference from ESP32
- **Component Isolation**: Heat-generating components separated from sensitive analog circuits
- **Thermal Relief**: Proper via placement for heat dissipation

### **Power Distribution Excellence**
- **Star Topology**: Centralized power distribution from voltage regulator (VR1)
- **Wide Power Traces**: Minimized voltage drop and improved current handling
- **Clean Decoupling**: Strategic decoupling capacitor placement around ESP32
- **Ground Plane**: Solid bottom-layer ground for excellent signal integrity

### **Manufacturing Optimization**
- **2-Layer Design**: Standard manufacturing process compatibility
- **Standard Components**: Industry-standard footprints and packages
- **DRC Compliant**: All design rules verified for manufacturability
- **Professional Documentation**: Complete silkscreen labeling

## 📁 Repository Structure

ESP32_BASED_2LAYERSPCB_-KiCAD/
├── 2.kicad_pro # Main KiCad project file
├── 2.kicad_sch # Schematic design
├── 2.kicad_pcb # PCB layout file
├── 2.kicad_prl # Project local settings
├── .gitignore # KiCad-specific ignore rules
├── README.md # Project documentation
└── [supporting files] # Additional KiCad assets

text

## 🚀 Getting Started

### **Prerequisites**
- **KiCad 6.0+** - Latest version recommended
- **Basic PCB Knowledge** - Understanding of schematic and layout principles

### **Usage Instructions**

1. **Clone Repository**
git clone https://github.com/BitwiseAjeet/ESP32_BASED_2LAYERSPCB_-KiCAD.git
cd ESP32_BASED_2LAYERSPCB_-KiCAD

text

2. **Open in KiCad**
- Launch KiCad
- Open `2.kicad_pro`
- Review schematic (`2.kicad_sch`)
- Examine PCB layout (`2.kicad_pcb`)

3. **Generate Manufacturing Files**
- Plot Gerber files
- Generate drill files
- Export pick & place files

## 🏭 Manufacturing Ready

### **Fabrication Specifications**
- **Layer Count**: 2-layer PCB
- **Material**: FR4 standard
- **Thickness**: 1.6mm ± 0.1mm
- **Surface Finish**: HASL or ENIG
- **Minimum Trace**: 0.1mm (4 mil)
- **Minimum Via**: 0.2mm (8 mil)

### **Assembly Information**
- **Component Placement**: Top side only
- **SMD Technology**: 0603 and larger components
- **Hand Assembly**: Friendly for prototyping
- **Production Ready**: Compatible with pick & place machines

## 📊 Performance Highlights

### **Electrical Performance**
- **Power Consumption**: Optimized for battery operation
- **Signal Integrity**: Clean power delivery and proper grounding
- **EMI Compliance**: Good layout practices for electromagnetic compatibility
- **Thermal Performance**: Improved sensor accuracy through thermal isolation

### **Mechanical Design**
- **Mounting**: 4x M3 mounting holes
- **Connector Accessibility**: Edge-mounted for easy enclosure integration
- **Component Height**: Low-profile design for compact applications
- **Robustness**: Industrial-grade component selection

## 🔄 Version History

- **v2.0** (Current) - 2-layer optimization with thermal and power improvements
- **v1.0** - Original 4-layer reference design

## 🤝 Applications

This PCB design is suitable for:
- **IoT Environmental Monitoring**
- **Remote Data Logging Systems**
- **Industrial Sensor Networks**
- **Research and Development Projects**
- **Educational PCB Design Reference**

## 📈 Future Enhancements

- [ ] Battery management integration
- [ ] Additional sensor interfaces
- [ ] RF performance optimization
- [ ] Protection circuit additions
- [ ] Expansion connector options

## 📄 License

This project is **open-source** and available for educational, research, and commercial use.

---

**Author**: [BitwiseAjeet](https://github.com/BitwiseAjeet)  
**Created**: July 2025  
**Status**: 🟢 Production Ready  
**Design Tool**: KiCad EDA Suite  
**Version**: 2.0

[![KiCad](https://img.shields.io/badge/KiCad-6.0+-blue)](https://www.kicad.org/)
[![License](https://img.shields.io/badge/License-Open%20Source-green)](https://github.com/BitwiseAjeet/ESP32_BASED_2LAYERSPCB_-KiCAD)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-success)](https://github.com/BitwiseAjeet/ESP32_BASED_2LAYERSPCB_-KiCAD)
