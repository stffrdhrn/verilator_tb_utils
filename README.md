## Verilator Testbench Utils

This is a set of verilator testbench harness tools to use with testing verilog
CPU cores.

It provides helpers for:

  * Setting up a JTAG server for use with OpenOCD (therefore GDB debugging)
  * Initializing memory with a ELF binary
  * Dumping VCD files for use with getting signal traces for debugging
