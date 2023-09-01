# Design and Simulation of a 32-bit RISC V Core and APB
Microprocessors can be of different architectures: Single-cycle, multi-cycle and pipelined. Multi-cycle architecture defines its input and output datapath and controls. In this project, SystemVerilog is used to design multi-cycle architecture.  <br>

RISC-V is an open standard instruction set architecture based on RISC principles. It is free-for-all, and can be implemented easily by using SystemVerilog. RISC-V has its own way of defining instructions in assembly and machine languages. Codes are compiled in SystemVerilog according to RISC-V standards.  <br>

In this project, instructions have been compiled in RISC-V architecture using SystemVerilog.
 <br>

<img
  src="APB.png"
  title="EVM"
  style="display: inline-block; margin: 0 auto; max-width: 400px; height: 400px">
  
APB: an industry standard protocol that is used to communicate with peripheral components. <br>
<ul>
  <li> APB bridge is the master </li> 
  <li> Peripherals are the slave </li> <br>
  </ul>
<br>

The data path for complete multicycle is shown below: <br>

<img
  src="datapath.png"
  title="EVM"
  style="display: inline-block; margin: 0 auto; max-width: 400px; height: 400px">

  The data path for complete multicycle is shown below: <br>

  <img
  src="fsm.png"
  title="EVM"
  style="display: inline-block; margin: 0 auto; max-width: 400px; height: 400px">

  

