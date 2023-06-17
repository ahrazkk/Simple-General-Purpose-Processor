# Simple-General-Purpose-Processor
 design and construct an Arithmetic and Logic Unit (ALU) in VHDL environment and implement it on an FPGA board



In this lab, the objective was to design and construct an Arithmetic and Logic Unit (ALU) using VHDL and implement it on an FPGA board. The lab consisted of several parts that needed to be completed.

In Part I, we procured the input data for the ALU, which involved using the last four digits of our student ID as the input values. These values were utilized in the simulation phase of the design.

Part II focused on the storage unit, specifically the registers used to temporarily store the input values. We wrote VHDL code for a register unit and created a symbol for it to be used in the final circuit design.

Part III involved the control unit, which consisted of a finite state machine (FSM) and a 4 to 16 decoder. The FSM was responsible for determining the controller sequence, and the decoder decoded the FSM output to the operation-selector microcode. We implemented the FSM and decoder designs and created symbols for both components.

In Part IV, we described the ALU core, which was the heart of the GPU unit. The ALU core performed arithmetic and logical operations on the inputs A and B based on the microcode received from the control unit. We implemented the ALU core using VHDL code and created a symbol for it.

Part V focused on displaying the output of the ALU core. In the simulation phase, the output result was displayed in bit-value format, while in the implementation phase on the FPGA board, it was displayed on two 7-segment displays in hexadecimal format.

In Part VI, we combined all the designed components, including the registers, ALU core, FSM, decoder, and 7-segment displays, into one final circuit design. We connected the components using data buses and named the buses appropriately. We synthesized and simulated the design to verify the functionality of the ALU.

Finally, in Part VIII, we addressed various problem sets related to the ALU and control unit. We implemented the initial design of the GPU, modified the ALU core to perform different operations, and modified the control unit to display specific outputs based on the FSM output.

Overall, this lab allowed us to gain hands-on experience in designing and implementing a simple general-purpose processor using VHDL and an FPGA board. We learned about the different components of the ALU and control unit and their roles in processing and controlling operations.
