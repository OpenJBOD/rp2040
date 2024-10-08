# OpenJBOD RP2040 Baseboard

This repository contains the hardware design files OpenJBOD RP2040 Baseboard.

For the accompanying software, please refer to:
- [micropython/micropython](https://github.com/micropython/micropython)
- [OpenJBOD/software](https://github.com/OpenJBOD/software)

## Requirements

- The design was created on KiCad 8.0.2, it uses the default symbol and footprint libraries from it. If you have installed KiCad without the default libraries, you may experience missing symbols.
- Non-standard symbols, footprints and models are bundled in the repository and should load with the project.

## Compatibility

The board is compatible with any standards-compliant ATX power supply.

For SAS expanders, any SAS expander that can operate with only power (i.e. no PCI-e communication) should be functional on the board.

The board has successfully been tested with:

- Adaptec AEC-82885T
