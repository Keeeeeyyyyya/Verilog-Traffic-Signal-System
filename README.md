<img width="1674" height="794" alt="download1" src="https://github.com/user-attachments/assets/ccd5d389-2a6d-494f-9d11-57df97faca6d" />
<img width="1723" height="777" alt="1" src="https://github.com/user-attachments/assets/6d0a4f0d-a066-48d8-b54c-899a1f8d7013" />


**Overview**

This project is a Verilog-based **Traffic Light Controller** designed using **Finite State Machine (FSM)** principles to manage traffic flow at a two-way intersection. The system controls signal transitions (Red, Yellow, Green) for the main and side roads based on predefined timing cycles. The design is simulated and verified using **EDA Playground**.

**Key Features**

* **FSM-based design** for structured and predictable traffic signal control.
* Supports **Main Road** and **Side Road** light cycles.
* **Clock-driven** state transitions.
* **Reset functionality** to restart the signal cycle.
* **Customizable timing parameters** for signal changes.
* Includes a **testbench** for verification in simulation.

**Visualization**

The traffic light states are represented using **3-bit signals**:

* `3'b100` → **Red**
* `3'b010` → **Yellow**
* `3'b001` → **Green**

**Main Road Light (light\_M1)** and **Side Road Light (light\_S)** change according to the FSM logic.

**Project Features**

* **Verilog Implementation**: Modular and clean HDL code for easy understanding.
* **Testbench Included**: Simulates realistic traffic light behavior.
* **EDA Playground Simulation**: No hardware needed for testing.
* **Scalable Design**: Can be expanded for more complex intersections.

**How to Use the Project**

1. **Open EDA Playground**: [https://www.edaplayground.com/](https://www.edaplayground.com/)
2. Create a new Verilog project.
3. Copy the **Traffic Light Controller** and **Testbench** code from this repository into the editor.
4. Select **Verilog** as the language.
5. Choose a Verilog simulator (e.g., **Icarus Verilog**).
6. Run the simulation and view the waveform to verify functionality.

**Requirements**

* EDA Playground account (optional, but useful for saving work)
* Basic knowledge of Verilog HDL
* Understanding of Finite State Machines (FSM)
* Internet browser to access EDA Playground

**Objective**

The main objective of this project is to design and simulate a **Traffic Light Controller** that ensures efficient and safe traffic flow by controlling signal lights using **FSM-based logic** in Verilog. It also aims to provide hands-on experience in hardware description language programming and digital design simulation.
