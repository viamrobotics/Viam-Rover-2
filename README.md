# Viam Rover 2.0 CAD files and BOM

This repo contains the CAD files (in Solidworks format), bill-of-materials (BOM) and PCB data relating to Viam Rover 2.0. 

The [CAD folder](https://github.com/viamrobotics/Viam-Rover-2/tree/main/CAD) contains SLDPRT files, DXF files of 2D sheet metal components and a full STEP assembly. You can also find the STL assembly of the Viam Rover [here](https://drive.google.com/file/d/1JtyBRx6tN-1W6WaxFIfYrkQEeCwIIvxX/view?usp=drive_link).

## PCB files

`BH-Viam-PCB1 230718.pcb` and `BH-Viam-PCB2 230718.pcb` are legacy Protel/Altium PCB 4.0 binary board files. Open them in the desktop version of [Altium Designer](https://www.altium.com/documentation/altium-designer/design-tools-interfacing/altium-design-software-import-export) with the Protel importer enabled. When an older PCB file is opened, Altium Designer launches its PCB Import Wizard and converts the board to the current format.

These files contain the board layouts rather than the circuit schematics. After conversion, use Altium Designer's PCB editor to inspect component pads, nets, and connector pin mappings.

For documentation on the Viam Rover unboxing and setup visit [here](https://docs.viam.com/get-started/try-viam/rover-resources/rover-tutorial/).

The Viam Rover 1.0 repo can be found [here](https://github.com/viamrobotics/Rover-VR1).


## License 
Copyright 2022-2023 Viam Inc.

Apache 2.0 - See [LICENSE](./LICENSE) file
