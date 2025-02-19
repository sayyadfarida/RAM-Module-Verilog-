COMPANY: CODTECH IT SOLUTIONS

NAME: Farida Sayyad

INTERN ID: :CT6WJJR

*DOMAIN*: VLSI

DURATION: 6 WEEEKS

MENTOR: NEELA SANTOSH



The design supports both read and write operations on the rising edge of a clock signal, making it ideal as a fundamental memory component in digital systems. Whether you are a student learning digital design, a hobbyist prototyping on an FPGA, or a professional building a larger system, this module offers a clear and flexible solution for integrating synchronous memory into your projects. The RAM module is parameterized to allow for easy modification of key attributes such as data width, address width, and overall memory depth. For example, by changing the parameter for the address width, you can adjust the number of memory locations available (with 2^N locations for an N-bit address). Similarly, the data width parameter defines the size of each data word stored in memory. TIn this design, all operations are synchronized to the clock’s rising edge. When the write enable (we) signal is high, the module writes the input data (data_in) into the memory at the specified address. Simultaneously, the module reads the content of that address and presents it on the data output (data_out). This synchronous behavior ensures that all memory operations are predictable and time-coordinated, which is critical for high-speed digital designs. The chosen read-during-write behavior is such that the new data being written is immediately available on the output—a design choice that aligns with industry best practices and is commonly referenced in Verilog tutorials and synthesis guidelines ASIC-WORLD.COM​INTEL.COM .

Accompanying the RAM module is a detailed testbench that demonstrates its functionality. The testbench is designed to simulate both write and subsequent read operations. Initially, it writes known values to specific memory addresses and later disables the write enable signal to allow the stored values to be read back. Through this process, the testbench verifies that the module correctly stores and outputs data. The simulation results can be observed using standard tools such as ModelSim, Icarus Verilog, or Vivado, which further helps users understand the timing and control of synchronous memory operations.

The repository is organized into well-defined sections to make it easy to navigate and integrate into your projects. The source code folder contains the Verilog module with extensive inline comments explaining every aspect of the design—from parameter definitions to clocked read/write operations. The testbench folder includes the simulation scripts and sample waveforms, offering a hands-on demonstration of how the module operates under different conditions. Detailed documentation in the README file provides step-by-step instructions for compiling, simulating, and integrating the RAM module into larger systems.his parameterization enables the module to be readily adapted for a variety of applications without needing to overhaul the entire design.


Output:
