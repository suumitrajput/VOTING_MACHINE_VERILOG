# Voting-Machine-Using-verilog

## Overview
This project implements a secure and reliable electronic voting machine using Verilog HDL (Hardware Description Language). The voting machine design includes robust features such as button debouncing, vote counting, mode selection, and result display to ensure accurate and secure voting processes. This project serves as a practical application of digital design principles in a critical domain.

## Features
- **Button Debouncing:** Ensures reliable detection of button presses by filtering out noise and ensuring stable input signals.
  
- **Vote Counting:** Accurately counts and records votes for multiple candidates, providing a dependable tallying mechanism.
  
- **Mode Selection:** Allows users to switch between voting mode and result display mode, enhancing flexibility and usability.
  
- **Result Display:** Displays voting results via LEDs or other output methods based on the selected mode, enabling transparent election monitoring.

## Project Structure
The project is structured into modular Verilog components:
- **`buttonControl.v`:** Implements button debouncing logic to ensure accurate detection of button presses.
  
- **`modeControl.v`:** Manages mode selection and controls LED displays to reflect voting results based on the current mode.
  
- **`voteLogger.v`:** Logs and counts valid votes for each candidate, ensuring accurate tallying and recording of votes.
  
- **`votingMachine.v`:** Integrates all modules to form the complete voting system, orchestrating the voting process and result display.

- **`testbench.v`:** Provides a simulation environment to validate and verify the functionality of the voting machine design.

## How to Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Rachit5981/secure-voting-machine-verilog.git
   cd secure-voting-machine-verilog
   ```
   
2. **Open in Verilog Simulation Tool:**
   - Open your preferred Verilog simulation environment (e.g., ModelSim, Vivado).
   
3. **Compile and Simulate:**
   - Compile each Verilog module (`buttonControl.v`, `modeControl.v`, `voteLogger.v`, `votingMachine.v`, `testbench.v`) in your simulation tool.
   - Run the simulation using `testbench.v` to observe and verify the functionality of the voting machine design.

## Files
- **`buttonControl.v`:** Handles button debouncing for reliable input detection.
  
- **`modeControl.v`:** Manages mode selection and controls LED outputs for result display.
  
- **`voteLogger.v`:** Logs and counts votes for each candidate during the voting process.
  
- **`votingMachine.v`:** Top-level module integrating all sub-modules to create the complete voting system.
  
- **`testbench.v`:** Simulation environment to test and verify the functionality of the voting machine design.

## Requirements
- Verilog HDL simulation tool (e.g., ModelSim, Vivado) for compiling and simulating the design.

## Future Enhancements
- Implementing a graphical user interface (GUI) for intuitive interaction and monitoring.
  
- Adding support for additional features such as voter authentication and audit logging.
  
- Integrating with physical hardware components for real-world deployment of the voting machine.
