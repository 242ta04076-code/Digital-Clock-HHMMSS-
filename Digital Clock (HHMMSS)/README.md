# Digital Clock (HH:MM:SS) using Verilog

## 📌 Project Overview

This project implements a **24-hour Digital Clock (HH:MM:SS)** using Verilog HDL.

The clock counts:
- Hours (00–23)
- Minutes (00–59)
- Seconds (00–59)

Every clock pulse represents one second in simulation.

---

## Features

- 24-hour format
- Automatic second counting
- Minute rollover after 59 seconds
- Hour rollover after 23:59:59
- Synchronous reset
- Easy to simulate on ModelSim, Vivado and Icarus Verilog

---

## Files

- digital_clock.v
- digital_clock_tb.v
- simulation.png
- waveform.vcd

---

## Software

- Verilog HDL
- ModelSim
- Vivado
- Icarus Verilog
- GTKWave

---

## Expected Output

Time counts as:

00:00:00

00:00:01

00:00:02

...

00:00:59

00:01:00

...

23:59:59

00:00:00

---

## Author

Harshitha Gangireddy