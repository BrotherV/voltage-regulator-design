# Voltage Regulator Design

### From Linear to Switching

**Author:** Mohsen Hatami  
**Edition:** First Edition (2026)  
**Format:** PDF · 489 pages

[**Read or download the book (PDF)**](./Voltage_Regulator_Design.pdf)

## About the book

*Voltage Regulator Design: From Linear to Switching* is a technical textbook and reference for power-electronics and hardware design engineers and graduate students. It covers the design of voltage regulators from the Zener shunt regulator and the LDO to multiphase, resonant, and phase-shifted converters, and the protection and current-sensing circuits that surround them. It brings together explanations, design equations, step-by-step procedures, worked designs with real controller ICs, design rules, and checklists.

The book has 40 chapters in seven parts, eight appendices, more than 220 figures, and more than 120 tables. Each worked design starts from a table of requirements, develops every equation in numbered steps with the numbers shown, and ends with a results table or bill of materials. Each chapter opens with an overview and learning objectives and closes with key takeaways and review problems; the answers are collected at the back of the book. Device values taken from manufacturers' datasheets are cited, and every figure states what kind of evidence it is: analytical, simulation, schematic, conceptual, or illustrative.

## Topics covered

- **Part I — Foundations:**
  - What a regulator must do and how its performance is specified.
  - Real inductors, capacitors, MOSFETs, and diodes.
  - Feedback and stability.
- **Part II — Linear Regulators:**
  - Shunt regulators: Zener and TL431.
  - Series regulators: standard, quasi-LDO, and LDO.
  - LDO dynamics: stability, PSRR, noise, and transients.
  - Thermal design and protection, and linear regulator designs with real ICs.
- **Part III — Non-Isolated Switching Converters:**
  - Switching converter fundamentals.
  - The buck converter: operation, power-stage design, small-signal model, and Type II and Type III compensation.
  - The boost converter and the buck-boost family: inverting, four-switch, SEPIC, and Ćuk.
  - Step-by-step designs with real ICs, including the TPS54331, LM5190, LTC7890, LM5125, and LM51772.
  - Multiphase buck converters for processor VRMs, with a complete TPS53679 design.
- **Part IV — Isolated Converters:**
  - Inductor and transformer design: cores, bobbins, wire, turns, gaps, and winding construction.
  - Flyback converters, with designs using the UCC28C43, UCC28782, and XDPS2221E.
  - Forward converters, with designs using the UC3845, UCC2897A, and MAX17599.
  - Push-pull, bridge, and LLC resonant converters, with UCC25661 and UCC28951 designs and digital control with the XDPP1188.
- **Part V — Control:** small-signal modeling of switching converters, control methods (voltage mode, peak and average current mode, constant on-time), compensator design, and loop measurement.
- **Part VI — Practical Design:** PCB layout for switching regulators, EMI and input filters, and protection, efficiency, thermal design, and testing.
- **Part VII — High-Current Outputs, Protection and Current Sensing:**
  - Scaling the secondary side of soft-switched converters to 100 A and above: rectifier arrangements, synchronous rectification, paralleling, and current sharing.
  - Rectifiers and output stages for welding machines, including a 200 A inverter welder.
  - MOSFET fundamentals for protection circuits.
  - Reverse-polarity and reverse-current protection, and power routing.
  - Overcurrent and short-circuit protection, eFuses, and hot swap.
  - Undervoltage and overvoltage lockout, inrush, inductive-load, thermal, and surge protection.
  - Shunt current sensing, and ground bounce and shared return impedance.
  - Selection tables, troubleshooting cases, and a register of the worked designs.

The appendices include:
- a formula reference sheet and component property tables;
- design checklists, and unit conversions with rules of thumb;
- topology quick-reference sheets and a glossary;
- study paths and design templates.

## Intended readers

Practicing power-electronics and hardware engineers, and graduate students with a background in circuit theory and some exposure to control theory. The book develops the converter models and compensation methods it uses from first principles.

## A note on the worked designs

The worked designs are calculated examples for study and a starting point for engineering work. They have not been built or measured, and the plots are evaluations of the equations and models stated in their captions. Values marked "verify" in the text must be confirmed against the current datasheet or standard before a design is built. Power converters and welding power sources operate at hazardous voltages and energies; see the notice on the copyright page.

## Copyright and permitted use

Copyright © 2026 **Mohsen Hatami**. All rights reserved.

The PDF may be downloaded and read for personal use. **Do not modify or redistribute the PDF.** To share it, link to the author's official GitHub or LinkedIn page rather than uploading another copy. This PDF should be hosted here only with the author's permission.

**This repository is not published under an open-source license.** See the copyright page of the PDF for full terms and disclaimer.

## Feedback

Corrections and technical feedback are welcome. Please contact the author through his professional profile or an author-approved contact channel.
