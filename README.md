# Hardware Implementation of Real-Time Communication using UART with AES-128 Encryption/Decryption

**Course**: Digital System Design (CPE344)  
**Type**: Complex Engineering Problem (CEP)  
**Student**: Sumaira Safeer (FA22-BCE-019)  
**University**: COMSATS University Islamabad, Attock Campus

---

## Project Overview
This project implements **real-time secure communication** between two NEXYS4 DDR FPGA boards using:
- **AES-128** encryption/decryption in hardware (Verilog)
- **UART** protocol for serial communication (115200 baud)
- **Pipelined architecture** for better performance

The system can encrypt data on one FPGA, transmit it securely via UART, and decrypt it on the receiving FPGA in real time.

---

## Key Features
- Full AES-128 encryption and decryption in hardware
- UART transmitter and receiver modules
- 3-stage pipelined AES architecture
- Real-time communication between FPGAs
- Verified through simulation and hardware testing

---

## Folder Structure

CEP_AES_UART_Implementation/

├── Report/

│   └── CEP_AES_UART_Report.pdf

└── Verilog/

├── uart_aes_top.v

├── uart_tx.v 

├── uart_rx.v

├── aes_top.v

├── aes_dec_top.v

└── tb_uart_aes_top.v


---

## Technologies Used
- **Hardware Description Language**: Verilog HDL
- **Target FPGA**: NEXYS4 DDR (Xilinx Artix-7)
- **Tools**: Xilinx ISE / Vivado
- **Communication Protocol**: UART (115200 baud, 8-N-1)

---

## Implementation Highlights
- AES-128 with SubBytes, ShiftRows, MixColumns, AddRoundKey
- Key Expansion module
- Pipelined encryption/decryption (3 stages)
- UART TX/RX with proper handshaking
- End-to-end encryption-decryption flow verified

---

## Results
- Successfully implemented and tested encryption + UART communication
- Correct round-trip encryption and decryption verified in simulation
- Functional on FPGA hardware

---

## 👩‍🎓 Author

**Sumaira Safeer**  
Computer Engineer 
COMSATS University Islamabad, Attock Campus  
[LinkedIn](https://www.linkedin.com/in/sumaira-safeer-948804418/)

