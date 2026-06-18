# Seven CAD

Seven is a rapid‑prototyping platform for low‑cost, low‑power connected
IoT devices with integrated LTE cellular connectivity.

Designed for teams moving from concept to deployment, Seven bridges the gap
between traditional development boards and finalized products—making it ideal
for pilot projects, field trials, and early production runs.

Specification:

* Nordic Semiconductor nRF9151 SiP with integrated LTE-M/NB-IoT modem and GPS
  * 64 MHz Arm Cortex-M33
  * 256 KiB RAM
  * 1 MiB flash
* 6-36 V input voltage
* 2 x mikroBUS™ sockets for easy expansion with Click Boards
* RGB LED
* Passive buzzer
* Programming interface (SWD) via TAG connector
* Industrial temperature range (-40 to 85 Celsius)

The software stack is built on the Zephyr Project, providing a robust, secure,
and scalable RTOS foundation. It includes ready‑to‑use modules for over‑the‑air
(OTA) updates and cloud connectivity, with primary support for AWS IoT.

By adopting the widely used mikroBUS™ add‑on standard, Seven offers access to
thousands of off‑the‑shelf Click Boards. This makes it easy to extend the
platform with sensors (motion, proximity, temperature, etc.) or interfaces such
as RS‑232, RS‑485, CAN, and more—without custom hardware design.

Seven is open source and open hardware, giving developers complete transparency
and control to customize, manufacture, and evolve their products without vendor
lock‑in.

---

This repository contains FreeCAD project and documentation for Seven reference enclosure.

## Prerequisites

* Install [FreeCAD](https://www.freecad.org/downloads.php)
* A 3D printer or use a 3D printing service like [JLCPCB](https://jlcpcb.com/3d-printing?from=Jesse)

## Getting started

Clone repository:

```bash
git clone git@github.com:id8-engineering/seven-cad.git
```

Cd into it:

```bash
cd seven-cad
```

1. Open FreeCAD
2. Select the file in repository under freecad ending with .FCStd.
3. On the left panel you will see your timeline, press the **eye** icon on the names **case**, **lid** & **jtag-box**.
4. Press the **eye** icon on all bodies on at a time, start with **case** and do the rest of the steps then go back to the next body.
5. Double press the 3D body so it gets green.
6. In the left top corner press **file** then **export** and pick your wanted 3D model file-type. There is often a recommended file-type for your printer.
7. Import these three files into your printer application and print your full enclosure case for Seven.

## License

Copyright 2026 ID8 Engineering AB

This source describes Open Hardware and is licensed under the CERN-OHL-P v2.

You may redistribute and modify this source and make products using it
under the terms of the CERN-OHL-P v2 (https://cern.ch/cern-ohl).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY
AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-P v2
for applicable conditions.

This source distribution includes the companion documents required by
the CERN-OHL-P v2 guide:

- [LICENSE](LICENSE)
- [CERN-OHL-P-v2-user-guide.md](CERN-OHL-P-v2-user-guide.md)
- [CHANGES.txt](CHANGES.txt)

---

## Report issues

If you run into problems, you can ask for help in our
[issue tracker](https://github.com/id8-engineering/seven-cad/issues) on
GitHub.

## Maintainers

Maintained by [ID8 Engineering AB](https://github.com/id8-engineering/).
