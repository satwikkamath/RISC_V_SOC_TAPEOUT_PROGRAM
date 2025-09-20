# Week 0 - Installation & Setup

This week focused on setting up the development environment and verifying tool installations.

---

## ✅ Tasks Completed

### 1. Oracle Virtual Machine
- Installed [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- System Requirements Checked:
  - RAM: 6GB
  - HDD: 50GB
  - CPU: 4vCPU
  - OS: Ubuntu 20.04+

### 2. Tool Installation

#### Yosys
```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make   # if not installed
sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install
```
<img width="726" height="473" alt="yosys" src="https://github.com/user-attachments/assets/16c347aa-ef7c-4708-a5c8-4bd62a7208a5" />

#### Icarus Verilog 
```bash
sudo apt-get update
sudo apt-get install iverilog
```
<img width="727" height="473" alt="iverilog" src="https://github.com/user-attachments/assets/a0e3a179-df63-4c13-88bf-8d98e7649211" />

#### GTKWave
```bash
sudo apt-get update
sudo apt install gtkwave
```
<img width="1005" height="822" alt="gtkwave" src="https://github.com/user-attachments/assets/b8564789-c5cf-4956-b409-913c93f88dd6" />

#### OpenSTA
[OpenSTA Github](https://github.com/The-OpenROAD-Project/OpenSTA)

<img width="741" height="477" alt="opensta" src="https://github.com/user-attachments/assets/f43f38fc-c218-4ece-96b0-70d8f20a4c04" />
