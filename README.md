This project is a TRIL engineering file that can optimize the timing performance of FPGA.

1. Instructions for use:
    To compile VTR:
        cd vtr-verilog-to-routing-8.0.0
        make

    For more information, please refer to the VTR related documentation:https://docs.verilogtorouting.org/en/latest/

    To compile IR:
        mkdir build
        cmake ..
        make
        ./main ../benchmark/diffeq.blif

    To compile LBTB:
        For LBTB compilation, please refer to README in the LBTB file.

    To use IR-LBTB:
        chmod +x IR_LBTB.sh
        ./IR_LBTB.sh

2. File directory
    1.benchmark 
    2.src: source code for IR-LBTB
    3.vtr: Open source FPGA CAD tool
    4.LBTB: Code for Latch based timing analysis
    5.vtr-verilog-to-routing-8.0.0: Verilog-to-Routing, an open source FPGA CAD tool.
