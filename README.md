
# JLCPCB-KiCad-DRC

JLCPCB Design Rules for KiCad 7.0, implemented as Custom Rules in PCB Editor `File > Board_Setup... > Design Rules > Custom Rules`), and stored in the `.kicad_dru` file.

These rules use some features only available in KiCad 7.0.

Each design rule is validated for PASS/FAIL the associated PCB (`.kicad_pcb`).

## Use in your KiCad 7 project

Simply copy the [`JLCPCB.kicad_dru`](JLCPCB/JLCPCB.kicad_dru) file into your KiCad 7 project folder, and rename it to match your project name `your-project.kicad_dru`.

The JLCPCB Design Rules will automatically be included in the KiCad PCB Editor (`File`>`Board Setup...`>`Design Rules`>`Custom Rules`), and be included when performing a [Design Rules Check (DRC)](https://docs.kicad.org/7.0/en/pcbnew/pcbnew.html#design_rule_checking) (`Ìnspect`>`Design Rules Checker`).

## JLCPCB documentation

- [PCB Manufacturing & Assembly Capabilities](https://jlcpcb.com/capabilities/pcb-capabilities)
- [Capabilities](https://jlcpcb.com/capabilities/Eagle%20PCB%20to%20gerber%20files)

## KiCAD documentation

- [Custom Design Rules (KiCad 7.0)](https://docs.kicad.org/7.0/en/pcbnew/pcbnew.html#custom_design_rules)

# KiCad Templates for new projects

Provides a number of additional Board and production house templates for KiCad EDA.

The templates here serve two purposes:

1. They provide the outline, standard position and shared components for common adapters
2. They setup basic board parameters such as DRC limits and preferred track widths
