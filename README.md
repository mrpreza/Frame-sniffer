# Frame-sniffer

### Contributors

This project was made possible by the following contributors:

- [Reza Paktinat](https://github.com/mrpreza)
- [Saeed Razavi](https://github.com/Spitamo)
- [Soroosh Dadashi](https://github.com/sorooshdp)

### Project Description


An FPGA-based Ethernet frame sniffer designed to capture, analyze, and validate network frames at the hardware level.  
This project includes VHDL source code, a Python frame generator for testing, and a testbench for simulation.  

---

## 🚀 Features
- **VHDL Implementation**  
  Core logic for sniffing and processing Ethernet frames on FPGA hardware.  

- **Testbench (VHDL)**  
  Simulation environment for verifying the FPGA logic.  

- **Python Frame Generator**  
  (`framegen.py`) Used to generate test frames for validation and debugging.  

- **Wireshark Integration**  
  Example captured outputs (screenshots included) for validating functionality.  

---


## 🛠️ Requirements

- **Hardware**:  
  - Xilinx FPGA board (or compatible)  
  - Ethernet PHY interface  

- **Software**:  
  - [Xilinx ISE / Vivado](https://www.xilinx.com/) (for synthesis and simulation)  
  - Python 3.x (for frame generation)  
  - [Wireshark](https://www.wireshark.org/) (for packet validation)  

---

## ⚡ Usage

1. **Synthesize and Deploy**  
   - Load `vhdl.vhdl` and `UCF.txt` into your FPGA project (ISE/Vivado).  
   - Compile and program the FPGA.  

2. **Run Simulation (Optional)**  
   - Open `testbench.vhdl` in your simulator.  
   - Verify output waveforms and frame detection.  

3. **Generate Test Frames**  
   ```bash
   python framegen.py
📖 Documentation

Full report: Report.pdf

Additional docs: report.docx, report.pdf, LES.pdf

Example outputs: wireshark output (1).jpg, wireshark output (2).jpg

🔧 Future Improvements

Support for advanced protocols (IPv6, ARP, etc.)

Real-time packet filtering on FPGA

Integration with host PC via UART/Ethernet

## 📜 License


This project is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. You are free to share the work, but you cannot modify it or create derivatives. Proper attribution must be given to the original author.
You can view the full license text here: [CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY%20ND%204.0-lightgrey)
