# Dental Attachment Unit

A comprehensive hardware design project for a temperature-controlled dental attachment unit with electronic controls and cooling systems.

## 🔧 Project Overview

This project contains 3D CAD models, electronic component designs, and hardware specifications for a dental attachment unit that features temperature control, cooling systems, and electronic monitoring capabilities.

## 📦 Components

### Electronic Components

#### 1. **Arduino Nano (arduino nano290313/)**
- Microcontroller: ATmega328
- USB Interface: FTDI FT232RL
- Crystal oscillator: 16MHz
- Complete 3D CAD model with all components
- Mini USB connectivity
- Reset button assembly
- LED indicators
- Voltage regulator

#### 2. **DS18B20 Temperature Sensor Module**
- Digital temperature sensor
- 1-Wire interface
- Location: `DS18B20 Module/`
- Includes KY-001 module design
- Custom holder design (see thermometer-holder-ds18b20)

#### 3. **Relay Module (SRD-05VDC-SL-C)**
- 5V DC coil voltage
- Songle relay
- PCB module design
- Location: `songle-relay-srd-05vcd-sl-c-1.snapshot.3/`

#### 4. **Solenoid Valve**
- Multi-voltage support: 6V / 12V / 24V
- Location: `solenoid 6V 12V 24V/`
- Complete 3D assembly model

### Cooling & Temperature Control

#### 5. **TEC1-12706 Peltier Module with Cooling Block**
- Thermoelectric cooler
- 40mm cooling block
- Liquid cooling capable
- Location: `tec1-12706-and-40mm-cooling-block-1.snapshot.3/`
- Includes thermal management design

#### 6. **Fan 40x40x10mm**
- 5V Sunon fan cooler
- 40mm x 40mm x 10mm dimensions
- Complete assembly with blade design
- Location: `Fan 40x40x10/`

#### 7. **Fan 80x80x25mm**
- Larger cooling fan assembly
- Chrome plated wire cover
- 80mm x 80mm x 25mm dimensions
- Location: `Fan 80x80x25/`

#### 8. **Heat Cartridge**
- Heating element
- Industrial-grade design
- Location: `Heat Cartrige/`

### Custom Parts & Holders

#### 9. **DS18B20 Thermometer Holder**
- Custom-designed holder for DS18B20 sensor
- STL file available for 3D printing
- Location: `thermometer-holder-ds18b20-1.snapshot.6/`
- Files: `objímka.stl`, `Objímka v4.step`

## 📁 File Formats

This project includes multiple CAD file formats:

- **SLDPRT** - SolidWorks Part files
- **SLDASM** - SolidWorks Assembly files
- **STEP** (.step, .stp) - Standard for the Exchange of Product Data (universal CAD format)
- **IGES** (.igs) - Initial Graphics Exchange Specification
- **STL** - STereoLithography (for 3D printing)
- **PNG/JPG** - Preview images and renderings

## 🎯 System Features

- **Temperature Monitoring**: DS18B20 digital temperature sensor with custom holder
- **Temperature Control**: Peltier module (TEC1-12706) for heating/cooling
- **Dual Cooling System**: 
  - 40mm fan for compact cooling
  - 80mm fan for enhanced cooling capacity
- **Heating Element**: Industrial heat cartridge
- **Fluid Control**: Multi-voltage solenoid valve
- **Electronic Control**: Arduino Nano-based control system
- **Relay Switching**: 5V relay module for load control

## 🛠️ Technical Specifications

### Control System
- **Microcontroller**: ATmega328 (Arduino Nano)
- **Interface**: USB (FTDI FT232RL)
- **Temperature Sensor**: DS18B20 (1-Wire digital)
- **Relay**: SRD-05VDC-SL-C (5V coil)

### Thermal Management
- **Cooling**: TEC1-12706 Peltier + dual fan system
- **Heating**: Industrial heat cartridge
- **Fans**: 40mm (5V) + 80mm cooling fans
- **Temperature Range**: Configurable via DS18B20 sensor

### Fluid Control
- **Solenoid**: 6V/12V/24V multi-voltage
- **Control**: Relay-switched

## 🚀 Getting Started

### Prerequisites
- SolidWorks (for viewing/editing SLDPRT/SLDASM files)
- Any CAD software supporting STEP/IGES formats
- 3D printer (for custom holder parts)
- Arduino IDE (for microcontroller programming)

### Viewing the Models
1. Open STEP files (.step, .stp) - universal format compatible with most CAD software
2. For SolidWorks users: Open SLDASM assembly files
3. For 3D printing: Use STL files in the thermometer-holder directory

### Hardware Assembly
1. Print custom parts from STL files
2. Assemble electronic components according to Arduino Nano design
3. Mount cooling fans and heat management components
4. Install DS18B20 sensor in custom holder
5. Connect solenoid valve and relay module
6. Wire Arduino Nano control system

## 📐 3D Printing

The following parts are ready for 3D printing:
- **DS18B20 Thermometer Holder**: `thermometer-holder-ds18b20-1.snapshot.6/objímka.stl`

## 🔌 Wiring & Electronics

### Arduino Nano Connections
- DS18B20 sensor → Digital pin (1-Wire)
- Relay module → Digital pin (output)
- Solenoid valve → Through relay
- Fan control → PWM capable pins
- Temperature feedback → DS18B20 data line

## 📷 Preview Images

Preview images and renderings are available in each component directory:
- Fan designs: `Preview sunon fan.jpg`, `Preview sunon fan2.jpg`
- Peltier module: `peltier internal.PNG`, `peltier isometric view.PNG`
- DS18B20 holder: `DS18B20-holder.png`, `DS18B20-holder-2.png`
- Component photos: Available in respective directories

## 🤝 Contributing

This is a hardware design project. Contributions for improvements, optimizations, or additional features are welcome.

## 📄 License

Please specify your license here.

## 👤 Author

**Mehrshad Lesani**
- GitHub: [@mehrshadlesani](https://github.com/mehrshadlesani)
- Email: mehrshad.lesani@gmail.com

## 🏷️ Project Status

Active development - Hardware design phase complete, ready for prototyping.

## 📌 Notes

- All measurements are based on standard electronic components
- CAD models include full assembly details
- Materials and rendering properties are embedded in SolidWorks files
- STEP files provided for cross-platform compatibility

---

**Last Updated**: November 2026
