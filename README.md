## 4-bit RPN Calculator Project

**Lab 8 - 4-bit RPN Calculator**

**By:** Lurjan Sela, Nakul Kochar, Filip Niemiec

**Lab Objective**
- The objective of Lab 8 was to design and create a 4-bit RPN calculator utilizing prior knowledge of components such as counters, multiplexers, RAM, ALU, and other integrated circuits used in previous labs.

**Learning from Unfinished Progress**
- Embracing the journey of designing and implementing the 4-bit RPN Calculator, we find value even in its unfinished state. This incomplete project serves as a reminder that not everything goes as planned, but the effort and commitment put into it are just as important. It's a testament to our determination and the learning that occurs when things don't go as expected.

**Block Diagram**
- The project employed a block diagram to illustrate the design. In this design, the counter was linked to the memory address, memory outputs connected to Register 1, which, in turn, was linked to the ALU with selectable options and connected LEDs. The control unit was connected to the MUX, serving as the input for the memory. Additionally, a second register was linked to the same MUX and the ALU, resulting in a total of two registers connected to the ALU.

**State Diagram**
- The team developed a state diagram to guide the project. The diagram began at an "IDLE" state and stayed there until the selection of "n" or "f." Upon pressing "n," it progressed to "State 1 (Push 1)" or "State 2 (Push 2)," and when "f" was pressed, it advanced to "State 3 (Pop 1)," "State 4 (Pop 2)," "State 5 (Pop 3)," or "State 6 (Pop 4)."

**Control Unit**
- The project included the design and testing of a control unit.

**Ram, Mux, ALU, Registers**
- The RAM, MUX, and ALU components were integrated, with the input of the RAM connected to the MUX. Red wires indicated these connections. The output of the RAM was connected to a register, which, in turn, was connected to the ALU on a separate board.

**Conclusion**
- While the project was not completed, the team successfully configured and tested the control unit. They also began the process of connecting the RAM, MUX, and registers to the control unit for testing different input signals, with further work required to fully wire and test the overall calculator.
