# EVB-USB32240 USB to SD Card Adapter

An open-source hardware design for a USB to SD card adapter board based on the USB32240 controller.

## Features

- USB Type-A interface
- Micro SD card slot support
- 3.3V voltage regulation using LM3480-3.3
- Crystal oscillator for clock generation
- Status LED indicator
- SMD components for compact design

## Hardware Specifications

- **USB Interface**: USB Type-A connector
- **SD Card**: Micro SD card slot
- **Voltage Regulator**: LM3480-3.3 for 3.3V power supply
- **Crystal**: External crystal for clock generation
- **Form Factor**: Compact SMD design
- **PCB Layers**: 2-layer board (F.Cu and B.Cu)

## Key Components

- USB32240 controller in QFN-36 package
- LM3480-3.3 voltage regulator in SOT-23 package
- Various 0201, 0402 resistors and capacitors
- Status LED for operation indication
- Crystal oscillator for stable timing

## Project Structure

```
EVB-USB32240/
├── EVB-USB32240.kicad_pcb   # PCB layout file
├── EVB-USB32240.kicad_sch   # Schematic file
├── EVB-USB32240.kicad_pro   # Project file
└── EVB-USB32240-backups/    # Backup files
```

## Manufacturing

The board is designed to be manufactured using standard PCB fabrication processes:
- 2-layer PCB
- Standard FR4 material
- Components are primarily SMD for automated assembly
- Minimal via count for cost optimization

## License

This hardware design is released under MIT License

## Contributing

Contributions to improve the design are welcome. Please feel free to:
- Submit bug reports
- Propose design improvements
- Create pull requests


## Acknowledgments

- KiCad EDA for the design tools
- Contributors and reviewers
