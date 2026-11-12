# PID Line Follower Bot

A two-wheel line follower built around an ATmega32A microcontroller, optical line sensors, and dual L298N motor drivers. The KiCad design includes the controller, sensor and motor-control circuits, and a compact robot PCB.

![Isometric CAD view of the line follower robot](Media/Cad%20isometric.png)

## Hardware overview

- ATmega32A-P microcontroller with crystal, buzzer, pushbuttons, and LCD connector
- Six photodetector inputs with LED emitters for line sensing
- Two L298N H-bridge drivers for the left and right DC motors
- 12 V input with an LM7809 regulator for the logic supply

## PCB and schematic

![PCB layout](Media/Pcb%20layout.png)

![Line follower schematic](Media/Screenshot%202026-11-12%20142647.png)

## KiCad source files

- [KiCad project](PID%20Line%20Follower.kicad_pro)
- [Schematic](PID%20Line%20Follower.kicad_sch)
- [PCB layout](PID%20Line%20Follower.kicad_pcb)

## Exports

- [PCB STEP model](exports/3d/PID%20Line%20Follower.step)
- [IDF board file](exports/idf/PID%20Line%20Follower.emn)
- [IDF library file](exports/idf/PID%20Line%20Follower.emp)

PDF drawing exports: [BOT](exports/pdf/BOT.pdf), [BOT NO MIRROR](exports/pdf/BOT%20NO%20MIRROR.pdf), [BOT 3](exports/pdf/BOT%203.pdf), [bot 4](exports/pdf/bot%204.pdf), [bot 5](exports/pdf/bot%205.pdf), [bot 6](exports/pdf/bot%206.pdf), and [bot5](exports/pdf/bot5.pdf).
