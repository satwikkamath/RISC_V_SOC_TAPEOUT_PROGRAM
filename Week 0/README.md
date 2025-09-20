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

#### Icarus Verilog 
```bash
sudo apt-get update
sudo apt-get install iverilog

#### GTKWave
sudo apt-get update
sudo apt install gtkwave

#### OpenSTA
[OpenSTA Github](https://github.com/The-OpenROAD-Project/OpenSTA)
