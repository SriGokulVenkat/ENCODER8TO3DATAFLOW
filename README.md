### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime



**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**
![Screenshot 2024-12-08 094229](https://github.com/user-attachments/assets/6eca9d73-593a-4009-9f0a-2de69bfb13f3)




**PROGRAM**
![Screenshot 2024-12-08 094126](https://github.com/user-attachments/assets/e05579a1-9fe1-4a08-b148-c6a2021a0b21)
![Screenshot 2024-12-08 094135](https://github.com/user-attachments/assets/cd842e0c-cc2a-4d45-9b88-b860ff7aaabb)




Developed by: SRI GOKUL VENKAT M
 RegisterNumber: 24901059

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-08 092339](https://github.com/user-attachments/assets/993d094c-0e12-4503-b01e-943c47b0fa64)

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-08 092350](https://github.com/user-attachments/assets/4bc7fd11-7c13-4f85-9f75-b5ed4f2552b4)

**RESULTS**

![Screenshot 2024-12-08 094237](https://github.com/user-attachments/assets/bec26db8-fe0f-4d55-ae00-244f159d32b5)




