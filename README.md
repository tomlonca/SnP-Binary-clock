# SnP-Binary-Clock

This project is about designing and implementing a **binary clock** using an AtMega48 microcontroller and a custom PCB.

## Overview
The clock supports:
- **Normal mode**
- **Sleep mode**
- **Low power mode**

Mode switching is done via three buttons on the top of the board.

## Available Files
- `BinaryClock_pcb.sch` – Schematic
- `BinaryClock_pcb.prl` – PCB layout
- `BinaryClock_pcb.pcb` – Compiled firmware

## Status
Work in progress.

## Komplexaufgabe

- Bauen Sie eine Binäruhr mit dem ATmega48, benutzen Sie hierfür mindestens die ausgegebenen Bauteile
- Pflicht Features:

1. Binäre Ausgabe auf 11 LED’s mit hardware PWM Helligkeitssteuerung (OC1x-Pin).
2. Steuerung über Taster (INT0, INT1, x).
3. Sleepmode mit Beweis der Reduzierten Leistungsaufnahme nach Datenblatt.
4. Zeitbasis über Timer und Uhrenquarz, mit Genauigkeitsmessung, Programmierung über ISP.
5. Programmierung direkt über AVR-gcc kein Arduino!

- Sinnvoll wäre es, die Uhr auf der Platine aus HWP II aufzubauen!
