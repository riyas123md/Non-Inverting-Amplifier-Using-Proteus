## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="748" height="515" alt="image" src="https://github.com/user-attachments/assets/4ae73f84-d533-4673-949a-719ed590a05e" />

(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
![non inverting](https://github.com/user-attachments/assets/7a0963fb-8202-40a9-ad38-f36c6aac33fa)

## Tabulation
S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)
| S.No | Vin (V) | Theoretical Gain (Av) | Theoretical Vout (V) | Practical Vout (Proteus) (V) |
| ---- | ------- | --------------------- | -------------------- | ---------------------------- |
| 1    | 0.1 V   | 11                    | 1.1 V                | 1.08 V                       |
| 2    | 0.2 V   | 11                    | 2.2 V                | 2.17 V                       |
| 3    | 0.3 V   | 11                    | 3.3 V                | 3.26 V                       |
| 4    | 0.5 V   | 11                    | 5.5 V                | 5.42 V                       |
| 5    | 0.7 V   | 11                    | 7.7 V                | 7.60 V                       |
| 6    | 1.0 V   | 11                    | 11 V                 | 10.85 V                      |
| 7    | 1.2 V   | 11                    | 13.2 V               | 13.0 V                       |
| 8    | 1.3 V   | 11                    | 14.3 V               | 14.0 V                       |
| 9    | 1.4 V   | 11                    | 15.4 V               | Saturated (~14 V)            |
| 10   | 1.5 V   | 11                    | 16.5 V               | Saturated (~14 V)            |
## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
	A Non-Inverting Amplifier is an operational amplifier (op-amp) configuration where the input signal is applied to the non-inverting (+) terminal, and the output is fed back to the inverting (−) terminal through a resistor network. This setup amplifies the input signal without changing its phase—meaning the output waveform is in the same phase as the input.
2.	What is the gain formula?
		Av​=Vin​/Vout​​=1+R1​/Rf​​
3.	Why is output in phase?
	In a non-inverting amplifier, the output is in phase with the input because of how the signal is applied and how negative feedback works in the op-amp circuit.

Key Reason

The input signal is applied to the non-inverting (+) terminal of the op-amp. An ideal op-amp amplifies the difference between its inputs:
4.	What happens if Rf increases?
In a non-inverting amplifier, increasing the feedback resistor Rf
directly affects the voltage gain of the circuit.
5.	What is the input impedance of non-inverting amplifier?
Zin​=∞

