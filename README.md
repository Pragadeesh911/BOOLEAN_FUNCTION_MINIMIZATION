# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-28 at 14 26 30_d4cfed38](https://github.com/user-attachments/assets/de33d253-14be-4c26-acd3-e3a52710f5cf)





**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Registration link** : 24002839
**Program:**
module expl1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
![WhatsApp Image 2024-10-28 at 14 36 15_4101f7ab](https://github.com/user-attachments/assets/43e4d102-0e7d-4e98-be9e-bebb9f41de28)
![WhatsApp Image 2024-10-28 at 14 36 16_799a6523](https://github.com/user-attachments/assets/38651389-31dd-4d00-b483-cb21ec872979)



**Timing Diagram**
![WhatsApp Image 2024-10-28 at 14 45 14_5617ed75](https://github.com/user-attachments/assets/a8809128-a305-4912-99ff-7ef588f4f767)
![WhatsApp Image 2024-10-28 at 14 45 30_0fcf590c](https://github.com/user-attachments/assets/72cab684-1a5d-41d4-b330-dac44a8135ff)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

