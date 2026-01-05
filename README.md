# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime
JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.
<img width="623" height="384" alt="image" src="https://github.com/user-attachments/assets/73f07f8f-4429-4ca1-b3a2-8627a6ea948c" />
<img width="654" height="580" alt="image" src="https://github.com/user-attachments/assets/9d2317d3-c69e-4a9a-9055-2045ada00140" />



**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

 


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

 

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**
step-1 Go to quartus software.

step-2 Set new environment.

step-3 Type the code to implement SR flipflop using verilog and validating their functionality using their functional tables.

step-4 Run the program.

step-5 Give inputs in the waveform table .

step-6 Run the program.



/* write all the steps invloved */

**PROGRAM**
<img width="498" height="297" alt="image" src="https://github.com/user-attachments/assets/60d57d52-f877-4b83-ae14-5288ae40cac1" />


/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL LOGIC FOR FLIPFLOPS**
<img width="786" height="293" alt="image" src="https://github.com/user-attachments/assets/25231870-b665-494a-a9cf-5595db81f726" />


**TIMING DIGRAMS FOR FLIP FLOPS**
<img width="853" height="144" alt="image" src="https://github.com/user-attachments/assets/d935959b-0d7d-4bdb-804a-ad248042210a" />


**RESULTS**
Studied and verified the truth table of JK flip-flop in Quartus II using verilog programming successfully.
