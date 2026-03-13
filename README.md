## Experiment 7: Digital to Analog Converter (DAC) using Proteus
## Aim
To design and simulate a Digital to Analog Converter (DAC) circuit using Proteus and observe the conversion of digital signals into analog output voltage.
## Apparatus / Software Required
•	Proteus Design Suite<br>
•	DAC IC (DAC0808)<br>
•	Resistors<br>
•	Operational Amplifier (e.g., µA741)<br>
•	Digital input switches<br>
•	Power supply<br>
## Theory
A Digital to Analog Converter (DAC) converts digital binary data into an equivalent analog voltage or current.
The DAC0808 is an 8-bit DAC that produces an analog current proportional to the digital input. An operational amplifier is used to convert the output current into a voltage signal.<br>
Features<br>
•	8-bit resolution<br>
•	Fast conversion<br>
•	Compatible with digital systems<br>
The analog output voltage depends on the digital input combination.<br>
## Circuit Diagram
<img width="1086" height="589" alt="Screenshot 2026-03-10 140019" src="https://github.com/user-attachments/assets/b21c00ae-a6c1-4236-85de-c35c8eb099d0" />
Design the circuit in Proteus using DAC0808 with:
•	8 digital switches for binary input
•	Op-Amp for current to voltage conversion
•	Output connected to voltmeter
## Procedure
1.	Open Proteus software.
2.	Select components:
o	DAC0808
o	Operational amplifier (741)
o	Resistors
o	Digital switches
3.	Connect binary inputs (D0–D7) using switches.
4.	Connect DAC output to the op-amp circuit.
5.	Connect a voltmeter at the output.
6.	Run the simulation.
7.	Change digital input combinations and observe the output voltage.

## Tabulation
| S.No | A | B | C | D | Digital Value | Theoretical Vout (V) |
| ---- | - | - | - | - | ------------- | -------------------- |
| 1    | 0 | 0 | 0 | 0 | 0             | 0                    |
| 2    | 0 | 0 | 0 | 1 | 1             | -0.3125              |
| 3    | 0 | 0 | 1 | 0 | 2             | -0.625               |
| 4    | 0 | 0 | 1 | 1 | 3             | -0.9375              |
| 5    | 0 | 1 | 0 | 0 | 4             | -1.25                |
| 6    | 0 | 1 | 0 | 1 | 5             | -1.5625              |
| 7    | 0 | 1 | 1 | 0 | 6             | -1.875               |
| 8    | 0 | 1 | 1 | 1 | 7             | -2.1875              |
| 9    | 1 | 0 | 0 | 0 | 8             | -2.5                 |
| 10   | 1 | 0 | 0 | 1 | 9             | -2.8125              |
| 11   | 1 | 0 | 1 | 0 | 10            | -3.125               |
| 12   | 1 | 0 | 1 | 1 | 11            | -3.4375              |
| 13   | 1 | 1 | 0 | 0 | 12            | -3.75                |
| 14   | 1 | 1 | 0 | 1 | 13            | -4.0625              |
| 15   | 1 | 1 | 1 | 0 | 14            | -4.375               |
| 16   | 1 | 1 | 1 | 1 | 15            | -4.6875              |


## Result
The Digital to Analog Converter circuit was successfully designed and simulated in Proteus, and the digital input was converted into corresponding analog voltage.

## Applications of ADC and DAC
•	Data acquisition systems<br>
•	Digital signal processing<br>
•	Microcontroller interfacing<br>
•	Audio and video processing<br>
•	Instrumentation systems<br>
