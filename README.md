# Awesome Structured Text [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of resources, tools, examples, and community content for IEC 61131-3 Structured Text (ST) programming.

Structured Text (ST) is a high-level, Pascal-like programming language defined in the [IEC 61131-3](https://webstore.iec.ch/en/publication/68533) standard for PLCs, HMIs, and industrial control systems. Its text-based, Pascal-like syntax makes it the most accessible IEC 61131-3 language for software engineers transitioning to industrial automation.

## Contents

- [Development](#development)
- [Resources](#resources)
- [Contribute](#contribute)

## Development
### Development Platforms

- [AnyAutomation Studio](https://anyautomation.ch/en/studio) - AI-assisted engineering IDE for Siemens TIA Portal (SCL) and CODESYS with SCL unit testing on PLCSIM Advanced, PLC online access and Git
- [B&R Automation Studio](https://www.br-automation.com/) - Development environment for B&R industrial controllers with full IEC 61131-3 support
- [Beremiz](https://beremiz.org/) - Open-source IEC 61131-3 IDE and runtime supporting all five PLC languages
- [CODESYS](https://store.codesys.com/en/codesys.html) - Manufacturer-independent IEC 61131-3 development platform
- [Danfoss PLUS+1 GUIDE](https://www.danfoss.com/en/products/dps/software/software-and-tools/plus1-software/plus1-guide/) - Development environment for Danfoss mobile machine controllers with graphical and IEC 61131-3 Structured Text programming
- [Omron Sysmac Studio](https://automation.omron.com/en/us/products/family/SYSSTDIO) - Integrated development environment for Omron NJ/NX/NY series machine controllers
- [OpenPLC](https://autonomylogic.com/) - Open-source PLC based on easy-to-use software
- [Phoenix Contact PLCnext Engineer](https://www.phoenixcontact.com/en-pc/products/software-plcnext-engineer-1046008) - Free IEC 61131-3 IDE for PLCnext Technology controllers
- [Rockwell Studio 5000 Logix Designer](https://www.rockwellautomation.com/en-us/products/software/factorytalk/designsuite/studio-5000.html) - Design environment for Allen-Bradley ControlLogix and CompactLogix controllers
- [Schneider Electric EcoStruxure Control Expert](https://www.se.com/us/en/product-range/548-ecostruxure-control-expert-software/) - Programming software for Schneider Electric Modicon controllers
- [Siemens TIA Portal](https://www.siemens.com/global/en/products/automation/industry-software/automation-software/tia-portal.html) - Integrated automation engineering platform for Siemens S7 PLCs using SCL (Structured Control Language)
- [TwinCAT by Beckhoff](https://www.beckhoff.com/en-us/products/automation/twincat/) - Realtime PLC, NC, CNC, and robots control on almost any PC
### Testing

- [co-unit](https://forge.codesys.com/lib/counit/) - Open-source unit testing framework for CODESYS
- [TcUnit](https://github.com/tcunit/TcUnit) - TwinCAT unit testing framework
- [UniTest](https://github.com/tkucic/UniTest) - Platform-agnostic unit testing library for any IEC 61131-3 environment
### Compilers & Parsers

- [blark](https://github.com/klauer/blark) - Beckhoff TwinCAT Structured Text parser written in Python
- [iec-checker](https://github.com/jubnzv/iec-checker) - Static analysis tool for IEC 61131-3 programs
- [matiec](https://github.com/beremiz/matiec) - Open-source IEC 61131-3 to C compiler used by Beremiz and OpenPLC
- [RuSTy](https://github.com/PLC-lang/rusty) - Structured Text compiler written in Rust with LLVM backend
### Libraries

- [OSCAT](https://store.codesys.com/en/oscat-basic.html) - Open-source function block library with building automation, network, and math blocks
- [structured-text-utilities](https://github.com/WengerAG/structured-text-utilities) - Utility functions for arrays, numbers, strings, and date/time operations
- [TcOpen](https://github.com/TcOpenGroup/TcOpen) - Application framework for TwinCAT 3 industrial automation
### Extensions

- [STweep](https://www.stweep.com/) - Source code formatter for Structured Text with IDE plugins
- [tree-sitter-structured-text](https://github.com/tmatijevich/tree-sitter-structured-text) - IEC 61131-3 Structured Text grammar for tree-sitter
- [vscode-st](https://github.com/Serhioromano/vscode-st) - Structured Text language support for Visual Studio Code
### DevOps

- [Twinpack](https://github.com/Zeugwerk/Twinpack) - Package manager for TwinCAT libraries with Visual Studio integration
- [zkbuild-action](https://github.com/Zeugwerk/zkbuild-action) - GitHub Action for building and unit testing TwinCAT PLC projects

## Resources

### Standards

- [IEC 61131-3](https://webstore.iec.ch/en/publication/68533) - Official international standard defining Structured Text and the other four PLC programming languages
- [PLCopen](https://plcopen.org/) - Vendor-independent organization maintaining technical standards and resources for IEC 61131-3

### Lists

- [awesome-industrial](https://github.com/HighFiveDetroit/awesome-industrial) - Curated list of Industry 4.0 resources including open-source industrial software
- [twincat-resources](https://github.com/benhar-dev/twincat-resources) - A curated list of TwinCAT resources

### Videos

- [Object Oriented Industrial Programming (OOIP) using CODESYS by Gary Pratt](https://www.youtube.com/watch?v=vRGaW4L762k) - How to apply object oriented programming concepts in CODESYS (March 2021 CODESYS Tech Talk)
- [Online PLC Support by Shane Welcher](https://www.youtube.com/c/ShaneWelcher) - YouTube channel with PLC programming tutorials including ST for Rockwell Automation
- [PLC programming using TwinCAT 3 by Jakob Sagatowski](https://www.youtube.com/playlist?list=PLimaF0nZKYHz3I3kFP4myaAYjmYk1SowO) - 18-part course covering various aspects of TwinCAT 3, geared toward software engineers

### Articles

- [Basics of Structured Text (ST) Programming by Realpars](https://www.realpars.com/blog/structured-text) - ST syntax and examples
- [Contact and Coil TwinCAT 3 Tutorial](https://www.contactandcoil.com/twincat-3-tutorial/structured-text/) - Comprehensive guide covering ST syntax, data types, loops, and string handling
- [Fernhill SCADA Structured Text Reference](https://www.fernhillsoftware.com/help/iec-61131/structured-text/) - Detailed ST language reference with syntax documentation and examples
- [Stefan Henneken's IEC 61131-3 Blog](https://stefanhenneken.net/) - In-depth articles on OOP, design patterns, and the IEC 61131-3 standard
- [Structured Text Programming: A Step by Step Guide by PLC Academy](https://www.plcacademy.com/structured-text-tutorial/) - Comprehensive tutorial covering ST syntax, data types, control structures, and practical examples

### Books

- [Mastering PLC Programming by M. T. White](https://www.packtpub.com/en-us/product/mastering-plc-programming-9781804612880) - Hands-on guide covering IEC 61131-3 languages with CODESYS examples
- [PLC Controls with Structured Text (ST), V3: IEC 61131-3 and best practice ST programming by Tom Mejer Antonsen](https://a.co/d/8kcnwez) - In-depth guide to IEC 61131-3 standard implementation with practical examples and industry best practices for ST programming

### Courses

- [ControlByte Academy](https://controlbyte.tech/) - Video courses on CODESYS Structured Text programming with exercises and community support
- [RealPars](https://www.realpars.com/) - Professional courses covering PLC programming across Siemens, CODESYS, and other platforms

### Community

- [CODESYS Forge](https://forge.codesys.com/) - Official CODESYS community with forums, libraries, and project sharing
- [PLC Talk Forum](https://www.plctalk.net/qanda/) - Q&A platform for automation professionals
- [r/PLC on Reddit](https://www.reddit.com/r/PLC/) - Active community with 100k+ members

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
