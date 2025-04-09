# Reconfigurable Logic for IoT Devices

> This project explores the design of a low-power digital logic architecture capable of toggling between high-performance and energy-efficient modes using FSM and dynamic clock scaling in Verilog and Vivado.

---

### 📌 **Project Overview**
- **Objective:** Design and simulate a logic module with configurable performance modes controlled by an FSM and dynamic clock scaling.
- **Methodology:** A finite state machine (FSM) controls the power state and output logic based on input conditions. Simulations were carried out in Vivado using Verilog, and dynamic clock switching was implemented for mode transition.

---

### 💡 **Key Features**
- Dual-mode operation: Low-Power (50 MHz) and High-Performance (200 MHz)  
- Finite State Machine with asynchronous inputs  
- Clock control logic to optimize power  
- Tested for stable switching and timing violations  

---

### 🧰 **Skills Used**
FSM Design, Power Optimization, Timing Control, Verilog

---

### 🧪 **Technologies & Tools**
Vivado, Verilog/SystemVerilog

---

### 🔍 **Key Findings**
Successfully simulated a dual-mode logic system with ~30% power savings in low-power mode and seamless transition verified via waveform.

---

### 🎓 **What I Learned**
Dynamic clock control, FSM-based state transition, low-power design principles in digital systems.

---

### 🚀 **Future Work**
Deploy the design on a Xilinx FPGA board and test hardware performance; extend to include sleep/wake interrupts for ultra-low power IoT nodes.

---

### 📂 **Files Attached**
fsm_logic.v, vivado_project.xpr, waveform_switching_test.png
