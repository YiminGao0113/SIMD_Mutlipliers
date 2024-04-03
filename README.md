
# SIMD Versatile Dot Product Unit
The SIMD Versatile Dot Product Unit is a high-performance computing solution designed for generating dot product outputs in various precisions, leveraging SIMD (Single Instruction, Multiple Data) architecture to enhance computational efficiency and performance.

## Getting Started

### Prerequisites

- **Icarus Verilog**: For Verilog simulation
- **GTKWave**: For waveform analysis

#### Installing Icarus Verilog and GTKWave

- **Icarus Verilog**:
  
  ```bash
  apt install -y autoconf gperf make gcc g++ bison flex
  git clone https://github.com/steveicarus/iverilog.git
  cd iverilog
  # Follow the installation instructions
  sh autoconf.sh
  ./configure
  make
  ```
  
- **GTKWave**:
  ```bash
  sudo apt-get update
  sudo apt-get install gtkwave
  ```

#### Run the Testbench and observe the waveform
To run the testbench for the SIMD Versatile Dot Product Unit, you can use the provided Makefile. 
Run the make command with your design name. For example, to run the testbench for the dp32 design: 
  ```bash
  make dp32
  ```

### Notes:

- Ensure you provide the actual installation instructions for Icarus Verilog within the `iverilog` directory or link to the official documentation if it's more detailed.
- Adjust the contribution guidelines based on how you prefer to receive contributions.
- Specify the license under which your project is released. Common choices include MIT, GPL, and Apache 2.0, among others.

This README is generated by ChatGPT4.0 :)
