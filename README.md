# UART Controller Implementation in Verilog

## Overview

This project focuses on the RTL implementation of selected functional blocks of a UART controller using Verilog HDL. The design is developed and simulated using Xilinx Vivado.

The implemented modules focus on UART data transmission, reception, buffering, and associated control logic.

---

## Implemented Modules

The following UART functional blocks are implemented:

- Transmitter (TX) logic
- Receiver (RX) logic
- TX FIFO
- RX FIFO
- FIFO control logic
- Baud rate generation logic
- UART register interface

---

## Features

- Serial data transmission and reception
- Separate buffering for transmit and receive data
- FIFO-based data storage
- FIFO read and write control
- Configurable baud rate generation
- RTL-level functional simulation
- Verilog testbench-based verification

---

## Design Flow

1. Design the UART modules using Verilog HDL.
2. Develop individual modules for TX, RX, FIFO, and control logic.
3. Integrate the implemented modules.
4. Develop a testbench for functional verification.
5. Perform RTL simulation using Xilinx Vivado.
6. Verify TX and RX functionality.

---

## Tools Used

- **HDL:** Verilog
- **Simulation:** Xilinx Vivado
- **Design Level:** RTL

---

## Project Structure

```text
UART/
│
├── rtl/
│   ├── uart_tx.v
│   ├── uart_rx.v
│   ├── tx_fifo.v
│   ├── rx_fifo.v
│   ├── fifo_control.v
│   └── uart_top.v
│
├── tb/
│   └── uart_tb.v
│
├── docs/
│   └── UART_Block_Diagram.png
│
└── README.md
