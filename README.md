# 8-bit ALU in Verilog

A simple 8-bit Arithmetic Logic Unit (ALU) implemented in Verilog.
This project performs basic arithmetic and logical operations and includes a testbench for simulation.

## 🔧 Features

* **Addition**
* **Subtraction**
* **Bitwise AND, OR, XOR, NOT**
* **Shift Left (SHL)**
* **Shift Right (SHR)**

## 📁 Files

* `alu.v` — Main ALU module
* `alu_tb.v` — Testbench for verifying ALU functionality

## 🚀 Simulation

Tested and simulated using **EDA Playground** and **Icarus Verilog**.
The testbench prints results for each ALU operation.

## 🛠 Tools Used

* Verilog
* Icarus Verilog (iverilog)
* EDA Playground
* Git / GitHub

## 📌 How to Run

1. Clone the repo or download the files.
2. Use any Verilog simulator (e.g., Icarus Verilog) to compile and run:

   ```bash
   iverilog alu.v alu_tb.v -o alu
   vvp alu                   i have this on my file 8bit-ALU-Verilog saved in notebook as README.md 
   ```
