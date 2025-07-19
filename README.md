# PCM_Demodulator
# Objective
The PCM (Pulse Code Modulation) Demodulator project focuses on the recovery of analog signals from digitally encoded PCM signals. 
# Tools & technologies
IC SN74HC595 (SHIFT REGISTER)
IC CD4027BE (JK-FLIP FLOP)
IC TL084CN (OP-AMP)
# Working Principle
- PCM (Pulse Code Modulation) demodulation involves reconstructing the original analog signal from a series of binary pulses.
- The demodulator receives the binary PCM signal, which represents quantized amplitude levels of the original signal.
- It first decodes the binary data into corresponding quantized amplitude levels using a digital-to-analog converter (DAC).
- These amplitude levels are held for a specific sampling period using a sample-and-hold circuit.
- A low-pass filter is then used to smooth the stepped waveform into a continuous analog signal, closely resembling the original input.
# Construction
- Input Low-Pass Filter (LPF): Removes high-frequency noise from the received PCM signal.
- Clock Recovery Circuit: Synchronizes timing to accurately sample each pulse.
- Sampler & Decoder: Samples each pulse and converts binary codes into discrete amplitude levels.
- Digital-to-Analog Converter (DAC): Converts decoded digital values to analog voltage.
- Output LPF: Smoothens the analog output to reconstruct the original analog signal.
# Output
The output of a PCM demodulator is the **reconstructed analog signal** from the received digital PCM bitstream.
# Application
Telecommunication system, Satellite, Radio, Broadcasting, Medical Electronics
