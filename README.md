# AXI_demo
A simple Xilinx AXI interface based architecture to showcase its flexibilty and immense utility while designing comprehensive designs. For the sake of simplicity, only Memory Mapped AXI interfaces have been used with the following components :

AXI Master:
  -MicroBlaze CPU

AXI Slaves:
  -AXI Interrupt Controller
  -AXI Timer
  -AXI UART
  -AXI DRAM controller
  -AXI BRAM controller
  
The design is targetted at Artix-7-AC701 FPGA platform. However, the design can be modified by changing the board configuration while instantiating the project as well as by  reconfiguring the Memory Interface Generator (MIG) to the required board.
