**NAME: S ABISHEK**

**REG NO : 24900833**

**EXP NO 6 : SERIAL-IN-SERIAL-OUT-SHIFTREGISTER**

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

Type the program in Quartus software.

1.Compile and run the program.

2.Generate the RTL schematic and save the logic diagram.

3.Create nodes for inputs and outputs to generate the timing diagram.

4.For different input combinations generate the timing diagram.

**PROGRAM**


![image](https://github.com/user-attachments/assets/8e789ead-ea46-4acb-810d-3034eec7067b)


**RTL LOGIC FOR SISO**

![image](https://github.com/user-attachments/assets/587c9c2a-4c24-4458-a851-21d2db195b00)


**TIMING DIGRAM FOR SISO**

![WhatsApp Image 2024-12-24 at 21 41 25_097aeef4](https://github.com/user-attachments/assets/515c2416-ea44-46f0-add4-d59563b87f62)



**RESULTS**

Thus to implement SISO Shift Register using verilog and validating their functionality using their functional tables done successfully.
