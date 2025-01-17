# 2-Bit-ALU-and-4-Bit-ALU
The 4-bit and 2-bit ALU project showcases the design and implementation of compact Arithmetic Logic Units, capable of performing fundamental operations like addition, subtraction, and logic functions. This project demonstrates the foundation of digital computation, highlighting efficiency and scalability in circuit design.
# Explain:
- 2-bit ALU on the hardware level
  A 2-bit ALU (Arithmetic Logic Unit) is a digital circuit that performs basic arithmetic and 
logic operations on 2-bit binary numbers at the hardware level. It is a fundamental component 
of most central processing units (CPUs) and microcontrollers. The 2-bit ALU takes two 2-bit 
binary inputs, performs a specified operation, and produces a 2-bit binary output along with 
some status flags.
- ![image](https://github.com/user-attachments/assets/6ed09b3d-5c67-4e44-a355-220b2eff8a2b)
- ![image](https://github.com/user-attachments/assets/c773fedd-369b-49ed-b308-cd308b3d81cf)
- Circuit connection results
- ![image](https://github.com/user-attachments/assets/e2d8a4c4-952d-450b-b374-61436120add9)
The procedure for connecting a 2-bit ALU circuit by connecting 3 logic gates AND OR XOR in 
connecting the ALU full adder The XOR is connected in front of the full adder circuit to change 
the input before it is calculated in the circuit so that our circuit can do both addition and 
subtraction. Next, Cin with 0 and 1 indicates whether to be addition or subtraction, Therefore 1 
is subtraction, 0 is addition.
- ![image](https://github.com/user-attachments/assets/00b79b68-3c0f-4eaf-a775-15c1cc422619)
Enter binary : 11 + 10  
Results : 101 
CarryOut is 1  
,S1 is 0  
, S0 is 1

- 4 bit ALU
  A 4-bit Arithmetic Logic Unit (ALU) is a digital circuit that performs various arithmetic and 
logical operations on 4-bit binary numbers. One of the fundamental operations an ALU can 
perform is addition. The work description of a 4-bit ALU addition involves designing and 
implementing the circuit to carry out this operation. Here's a step-by-step breakdown of the 
process
- ![Uploading image.png…]()
# Result
![4-Bit-Full adder](https://github.com/user-attachments/assets/af6c13b6-3a29-43c9-b3bd-d5d0865510d7)
![4-Bit-Full adder ALU](https://github.com/user-attachments/assets/681aaf30-f72d-454d-974b-929fedc8cb05)
