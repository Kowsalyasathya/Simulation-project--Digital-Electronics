# DESIGN AND SIMULATE THE LOGIC DIAGRAM USING VERILOG

## AIM
To Design and simulate the logic diagram using Verilog.

## EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher.

Software – Quartus prime.

## PROCEDURE
Step 1: Create module encoder and decoder.

Step 2: Get inputs and outputs for encoders and decoders.

Step 3: perform or operation for encoder and and logic for decoders.

Step 4: perform RTL LOGIC and get waveform.

Step 5: End the module.

## LOGIC DIAGRAM
![283742533-a6fb8c2d-ce4f-4ffc-a189-609ab0a05350](https://github.com/Kowsalyasathya/Simulation-project--Digital-Electronics/assets/118671457/f0ef6024-f19e-41a2-ad3c-2879ac475d7e)

## NETLIST DIAGRAM
![283742559-47202004-8d40-4967-a9b8-1bc8782f49f7](https://github.com/Kowsalyasathya/Simulation-project--Digital-Electronics/assets/118671457/b6420536-5b5d-4f30-95d0-22d00d2e23c8)

## TIMING DIAGRAM
![283742587-31f4de35-3e4d-4701-9228-f31a92183e30](https://github.com/Kowsalyasathya/Simulation-project--Digital-Electronics/assets/118671457/ccf80159-4d07-4f3f-8efd-f5c562708b79)
## TRUTH TABLE
![283742683-f1b5d97a-1b6a-4c5f-8a09-fa3b3fab29da](https://github.com/Kowsalyasathya/Simulation-project--Digital-Electronics/assets/118671457/13ae21c4-fb44-42e6-bc13-10bd9c52a4a2)

## PROGRAM
```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: KOWSALYA M
RegisterNumber: 212222230069
module e13(x,y1,y2,z1,z2):
Input x,y1,y2;
Output z1,z2;
Assign z1=(x&y) | ((~x) & y2);
Assign z2=((~x)&y2) | (x&(~y1));
endmodule
```
## RESULT
Thus the program to design and simulate the logic diagram using Verilog.
