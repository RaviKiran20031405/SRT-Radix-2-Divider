This project focuses on the design and implementation of an SRT radix-2 divider for unsigned integers using 
Verilog HDL on an FPGA. The division algorithm, based on the digit recurrence method, iteratively generates 
quotient bits by employing a lookup table for quotient digit selection. The design was implemented and 
verified using Verilog HDL and synthesized onto an FPGA platform. Performance metrics, including area 
utilization and maximum operating frequency, were analyzed. The implemented divider demonstrates the 
feasibility of high-performance division using the SRT algorithm on FPGAs, offering a balance between speed 
and hardware resources.

Design and implementation of an (Sweeney, Robertson, Tocher) SRT (Unsigned Radix-2) divider is a critical 
component in the field of digital arithmetic, particularly in high-performance computing and embedded 
systems. The SRT algorithm, which is a modification of the long division method, leverages the use of digit 
selection and recurrence relations to minimize the number of required operations, making it faster and more 
efficient than traditional division methods. We explore the various stages of the design, including digit 
generation, quotient prediction, and correction mechanisms. The divider is implemented using a SRT 
Algorithm of Digit recurrence method to achieve a balance between speed and area efficiency. Simulation 
results show that the proposed SRT divider offers significant improvements in terms of throughput and 
resource utilization compared to conventional dividers. The design is suitable for integration into processors 
and systems that require high-speed division operations, with applications in fields such as digital signal 
processing, cryptography, and high-performance computing.  

The flexibility of field programmable gate arrays (FPGAs) allows the rapid development of high performance 
custom hardware. By selecting arithmetic algorithms suited to the FPGA technology and subsequently 
applying optimal mapping strategies, high performance FPGA implementations can be developed. In 
microcontrollers, mathematical operations such as addition, subtraction, multiplication and division are 
performed using the Arithmetical Logical Unit (ALU) thought FPGAs does not offer such a unit. In FPGAs, 
arithmetic operations are performed using the shift registers, lookup tables, hardware multipliers, and logic 
gates. Among the basic arithmetic operations (addition, subtractions, multiplications and divisions) divisions 
is the most complex and expensive among the four arithmetic operations in hardware. 
