
# Experiment--09-Implementation-of Shift-registers-using-verilog-
### AIM: To implement PISO , PIPO,PISO  using verilog and validating their functionality using their functional tables
### Developed by: Devadhaarini.D
### Register Number: 23006001
### HARDWARE REQUIRED:  – PC, Cyclone II , USB flasher
### SOFTWARE REQUIRED:   Quartus prime
### THEORY 
Shift registers are basically of 4 types. These are:

Serial In Serial Out shift register
Serial In parallel Out shift register
Parallel In Serial Out shift register
Parallel In parallel Out shift register
Serial-In Serial-Out Shift Register (SISO) –
The shift register, which allows serial input (one bit after the other through a single data line) and produces a serial output is known as Serial-In Serial-Out shift register. Since there is only one output, the data leaves the shift register one bit at a time in a serial pattern, thus the name Serial-In Serial-Out Shift Register.

The logic circuit given below shows a serial-in serial-out shift register. The circuit consists of four D flip-flops which are connected in a serial manner. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.

![image](https://user-images.githubusercontent.com/36288975/172337366-540cc45e-11fe-4cce-9503-560dc704bc7d.png)

FIGURE -01 
erial-In Parallel-Out shift Register (SIPO) –
The shift register, which allows serial input (one bit after the other through a single data line) and produces a parallel output is known as Serial-In Parallel-Out shift register.

The logic circuit given below shows a serial-in-parallel-out shift register. The circuit consists of four D flip-flops which are connected. The clear (CLR) signal is connected in addition to the clock signal to all the 4 flip flops in order to RESET them. The output of the first flip flop is connected to the input of the next flip flop and so on. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.

![image](https://user-images.githubusercontent.com/36288975/172337438-03416c7e-7c9d-4939-ba34-c355b9fc79c5.png)

FIGURE-02
The above circuit is an example of shift right register, taking the serial data input from the left side of the flip flop and producing a parallel output. They are used in communication lines where demultiplexing of a data line into several parallel lines is required because the main use of the SIPO register is to convert serial data into parallel data.
Parallel-In Serial-Out Shift Register (PISO) –
The shift register, which allows parallel input (data is given separately to each flip flop and in a simultaneous manner) and produces a serial output is known as Parallel-In Serial-Out shift register.

The logic circuit given below shows a parallel-in-serial-out shift register. The circuit consists of four D flip-flops which are connected. The clock input is directly connected to all the flip flops but the input data is connected individually to each flip flop through a multiplexer at the input of every flip flop. The output of the previous flip flop and parallel data input are connected to the input of the MUX and the output of MUX is connected to the next flip flop. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.

![image](https://user-images.githubusercontent.com/36288975/172337544-1632407f-1743-4b17-b480-00663d01e59f.png)

FIGURE-03
A Parallel in Serial out (PISO) shift register us used to convert parallel data to serial data.

Parallel-In Parallel-Out Shift Register (PIPO) –
The shift register, which allows parallel input (data is given separately to each flip flop and in a simultaneous manner) and also produces a parallel output is known as Parallel-In parallel-Out shift register.

The logic circuit given below shows a parallel-in-parallel-out shift register. The circuit consists of four D flip-flops which are connected. The clear (CLR) signal and clock signals are connected to all the 4 flip flops. In this type of register, there are no interconnections between the individual flip-flops since no serial shifting of the data is required. Data is given as input separately for each flip flop and in the same way, output also collected individually from each flip flop

![image](https://user-images.githubusercontent.com/36288975/172337661-babb1f90-6286-4d14-8cbd-26a380ee085e.png)

FIGURE-04
A Parallel in Parallel out (PIPO) shift register is used as a temporary storage device and like SISO Shift register it acts as a delay element.

### Procedure

1.Use quartus software and import required modules.

2.Assign inputs and outputs for shift registers.

3.Assign logic for input to give output at positive edge.

4.Perform opertaions and produce rtl circuit.

5.end module

### PROGRAM 
Program 1:

![Screenshot 2023-12-02 170420](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/17f1c4d9-497e-48d0-b533-a4b3f22375f0)

Program 2:

![Screenshot 2023-12-02 170429](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/c989a2eb-4601-470f-8eef-05f1764f9c0b)

Progran 3:

![Screenshot 2023-12-02 170440](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/2d59f464-4588-4039-bc4d-9b812652218b)

### RTL LOGIC  REGISTERS   
1.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/cc3ee6e6-9c91-42e9-a5ad-c1354b48fb19)

2.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/50f4a0c2-45ef-48a5-8636-77980ff9bf22)

3.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/ec54674f-6ea1-4237-803a-bd15ed39187c)

### TIMING DIGRAMS FOR SHIFT REGISTERS
1.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/38cd73bc-db94-4395-b41d-c81cb43b9ed7)

2.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/b0058539-829b-42ac-b12d-bb1dd3d2913f)

3.

![image](https://github.com/Devadhaarini/Exercise-09-Shift-registers-using-verilog-/assets/145796552/e3bf556a-90df-455e-a734-195f87c11a51)

### RESULTS 
Thus the program to implement shift registers is done successfully.
