**NAME: S ABISHEK**

**REG NO: 24900833**

**EXPERIMENT NO 10 : SERIAL-IN-SERIAL-OUT-SHIFTREGISTER**

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY:**

**SISO shift Register:**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**PROCEDURE:**

Type the program in Quartus software.

1.Compile and run the program.

2.Generate the RTL schematic and save the logic diagram.

3.Create nodes for inputs and outputs to generate the timing diagram.

4.For different input combinations generate the timing diagram.


**PROGRAM:**

![image](https://github.com/user-attachments/assets/4f9fb1fe-0f29-4acc-885e-ded8947b7171)


**RTL LOGIC FOR SISO:**

![image](https://github.com/user-attachments/assets/948105ba-e874-4a9e-8eb5-79e4b905a14c)



**TIMING DIGRAM:**

![WhatsApp Image 2024-12-24 at 21 41 25_03e483bf](https://github.com/user-attachments/assets/1e41b18a-5956-4ddf-a4c2-50eb2cfcfc23)




**RESULTS:**

Thus to implement SISO Shift Register using verilog and validating their functionality using their functional tables done successfully.
