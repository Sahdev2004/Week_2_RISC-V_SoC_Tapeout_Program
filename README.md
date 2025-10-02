## Week 2 Task: BabySoC Fundamentals & Functional Modelling 🧠💻

This repository documents the tasks completed for Week 2, focusing on building a foundational understanding of **System-on-Chip (SoC) design** and performing **functional modelling** of the **BabySoC** project using industry-standard simulation tools. 

---

## 🎯 Objective

The primary goal for this week was to achieve a solid conceptual understanding of SoC fundamentals and gain hands-on practice in functional modelling of the BabySoC using simulation tools, specifically Icarus Verilog and GTKWave. 

---

## 📚 Part 1: Theory - Conceptual Understanding

This part involved a study of SoC design fundamentals to provide the theoretical basis for the project.

### Key Concepts Studied:

* **What is a System-on-Chip (SoC)?** 
* **Components of a typical SoC:** CPU, memory, peripherals, and interconnect.
* **Why BabySoC is a simplified model for learning SoC concepts.**
* **The role of functional modelling** before the RTL and physical design stages. 

---

## 🧪 Part 2: Labs - Hands-on Functional Modelling

This hands-on section involved working with the **VSDBabySoC Project** to compile, simulate, and analyze the module's behavior at the functional level.

### Tools Used:

| Tool | Purpose |
| :--- | :--- |
| **Icarus Verilog (`iverilog`)** | Used for compiling the BabySoC Verilog code. |
| **GTKWave** | Used for viewing and analyzing the generated simulation waveforms (`.vcd` files). |

### Functional Modelling Steps:

1.  Clone the BabySoC project repository (referencing the Lab Reference). 
2.  Compile the BabySoC Verilog modules using `iverilog`. 
3.  Simulate the design to generate `.vcd` waveform files. 
4.  Open the `.vcd` files in GTKWave for analysis. 

### Waveform Analysis Focus:
The analysis in GTKWave focused on key operations and data flow: 

* **Reset operation** 
* **Clocking** 
* **Dataflow**
