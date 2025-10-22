Repository for an example breakout board for the TPS61220 boost converter IC from Texas Instruments.

This repository contains the schematic and PCB layout files for a simple breakout board designed to make it easy to use the TPS61220 in your projects. The TPS61220 is a high-efficiency boost converter capable of stepping up low input voltages to higher output voltages, making it ideal for battery-powered applications.

This breakout board is modelled after the TPS61220EVM-319 evaluation module (link below).

## Example Images
![Top View](https://i.imgur.com/jgy9n4q.jpeg)

## Usage
If R1 is set to 1Mohms and R2 is set to 180kohms, the output voltage will be 3.28V when powered from a < 3.28V source.

## Contents
- Schematic files
- PCB layout files

## Bill of Materials (BOM)

This BOM lists the components used in the associated design.

| Line No. | Manufacturer Part No. | Description | Manufacturer | Quantity | Mouser Part Number |
|:---:|:---:|:---|:---|:---:|:---:|
| 1 | TPS61220DCKR | Tiny Low Inp Vltg Bo / Schakelende spanningsregelaars | Texas Instruments | 1 | 595-TPS61220DCKR |
| 2 | EPL3015-472MLC | 4.7uH Shld 20% 1.4A / Vermogensinductoren - SMD | Coilcraft | 1 | 994-EPL3015-472MLC |
| 3 | GRM188R60J106ME47J | 10 uF 6.3 VDC 20% 06 / Meerlaagse keramische condensatoren MLCC - SMD/SMT | Murata Electronics | 2 | 81-GRM188R60J106ME7J |

---

### Notes
* Quantity refers to the "Besteld Aantal Quantity Ordered" from the source document, which is the total count of components required for the order or project.
* The Manufacturer Part Number and Description are key identifiers for the component.
* The Mouser Part Number is included for easy reference and reordering.

## Relevant Links

- [TPS61220 Product Page](https://www.ti.com/product/TPS61220)
- [TPS61220EVM-319 Evaluation Module](https://www.ti.com/tool/TPS61220EVM-319)
- [EEVBlog post with debug help](https://www.eevblog.com/forum/beginners/kindly-requesting-help-with-debugging-a-tsp61220-(pcb)-voltage-boost-converter/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
User from the EEVBlog forum for assistance with debugging the design:
- tooki
- mdijkens
- Psi
- ahsrabrifat
- MariuszD
- Slh
- xvr
- MathWizard
