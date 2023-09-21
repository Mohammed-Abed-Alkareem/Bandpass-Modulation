# Bandpass-Modulation
Gaining practical experience in digital modulation techniques (ASK), (FSK),  (PSK), and (QPSK),



# Summary
The objective of this project is to gain hands-on experience in designing and simulating digital modulation techniques, including Amplitude Shift Keying (ASK), Frequency Shift Keying (FSK), Phase Shift Keying (PSK), and Quadrature Phase Shift Keying (QPSK) using MATLAB Simulink.

# Specifications

1. Introduction
• Provide a brief introduction to digital modulation techniques, including ASK, FSK, PSK, and QPSK.
• Explain the importance of modulation in digital communication systems.

2. Simulink Model Setup
• Create a new Simulink model.
• Set up the simulation parameters (e.g., sample time, simulation duration).

3. ASK Modulation
• Add an ASK modulation block to the Simulink model.
• Configure the ASK modulation parameters (e.g., carrier frequency, modulation index).
• Connect the ASK modulator to a random data source.

4. FSK Modulation
• Add an FSK modulation block to the Simulink model.
• Configure the FSK modulation parameters (e.g., carrier frequencies for 0 and 1).
• Connect the FSK modulator to the same random data source as ASK.

5. PSK Modulation
• Add a PSK modulation block to the Simulink model.
• Configure the PSK modulation parameters (e.g., phase offsets for 0 and 1).
• Connect the PSK modulator to the same random data source as ASK and FSK.


6. QPSK Modulation
• Add a QPSK modulation block to the Simulink model.
• Connect the QPSK modulator to the same random data source as ASK, FSK, and PSK.

7. Channel Modeling
• Add a channel block to simulate the communication channel.
• Optionally, introduce noise or other impairments in the channel.

8. Demodulation
• Add corresponding ASK, FSK, PSK, and QPSK demodulation blocks to the Simulink model.
• Connect the demodulators to the output of the channel block.

9. Data Recovery
• Add data decision blocks for each modulation scheme to recover the digital data from the demodulated signal.
• Connect the data decision blocks to the outputs of the respective demodulators.

10. Simulation and Analysis
• Configure simulation parameters (e.g., signal-to-noise ratio, modulation index).
• Run the simulation and observe the results.
• Calculate and analyze the Bit Error Rate (BER) for each modulation scheme.
• Compare the performance of ASK, FSK, PSK, and QPSK under different channel conditions.

# Author

### Mohammed Abed Alkareem
### Mosa Sbieh
