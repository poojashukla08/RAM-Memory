# RAM-Memory

COMPANY: CODTECH IT SOLUTIONS

NAME:POOJA SHUKLA

INTERN ID: CT06DH677

DOMAIN: VLSI

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

A SIMPLE SYNCHRONOUS  RAM MODULE WITH READ AND  WRITE OPERATIONS.

###Description

## Task Description: RAM Memory Module with Read and Write Operations

This project demonstrates the implementation and simulation of a simple **RAM (Random Access Memory)** module using **Verilog HDL**, focusing on **basic read and write operations**. The design is created, simulated, and tested using the **EDA Playground** online simulation platform, making it accessible for students, hobbyists, and engineers learning digital design and hardware description languages.

---

###  Objective

The goal of this project is to:

* Develop a behavioral model of a **synchronous RAM memory block**
* Implement **write and read functionality** based on input control signals
* Simulate memory behavior using **testbench stimulus**
* Observe memory contents and verify functional correctness using waveform outputs on EDA Playground

---

###  Design Description

The RAM module is parameterized for flexibility and consists of the following key components:

* **Memory Array**: A 2D register array to store data.
* **Address Bus**: Specifies the memory location to access.
* **Data Bus**: Transfers data in and out of memory.
* **Control Signals**:

  * `write_enable`: When high, writes data to the specified address.
  * `read_enable`: When high, outputs data from the specified address.
  * `clk`: A clock signal to synchronize read/write operations.
  * `rst`: An active-high reset signal that clears the memory or pointers.

All read and write operations are synchronous, meaning they occur on the **rising edge of the clock**.

---

###  Module Features

* **Parameterizable Memory Size**: You can adjust the memory depth and word width.
* **Synchronous Operations**: Ensures that read and write occur only on valid clock edges.
* **Reset Behavior**: Clears all memory contents on reset (optional, depending on design).
* **Non-blocking Assignments**: Proper use of Verilog coding style to prevent race conditions.

---

### Testbench Details

A dedicated **testbench module** is included in the project to simulate and verify RAM operations:

* Initializes input signals
* Writes values to specific addresses
* Reads values back and checks correctness
* Includes timing delays to simulate real-time hardware behavior
* Displays outputs using `$display` and waveform view

The testbench helps demonstrate that:

* Written data is correctly stored at the specified address
* Read operations return the expected data
* Memory does not change unintentionally during inactive cycles

---

###  Tools Used

* **EDA Playground**: A cloud-based Verilog/VHDL simulator and waveform viewer

  * [https://www.edaplayground.com/](https://www.edaplayground.com/)
  * Enables simulation without installing local tools
  * Supports multiple simulators (e.g., Icarus, ModelSim)

---

###  Files Included

* `ram_memory.v` – Main RAM module (design file)
* `tb_ram_memory.v` – Testbench for simulation
* `README.md` – Project documentation

---

###  Learning Outcomes

By working through this project, I:

* Understood the internal structure of RAM
* Learnt to design, simulate, and debug memory in Verilog
* Practiced writing testbenches for functional verification
* Gained hands-on experience using EDA Playground

-----------------------------------------------------------------------------------

###OUTPUT WAVEFORM:

<img width="1864" height="481" alt="Image" src="https://github.com/user-attachments/assets/7d182c9b-d5ee-4bec-b682-d643bfb012e3" />

-------------------------------------------------------------------------------------
end.

