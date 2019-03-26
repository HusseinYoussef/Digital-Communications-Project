# Digital-Communications-Project
Simulating the performance of different modulation schemes, BPSK, QPSK, FSK, QAM16, QAM64 in an AWGN environment.

## General Parameters
```
For Random Integer Generator: 
    Initial seed = 37
    Sample time = 1
    Samples per frame = 100
    
AWGN Channel Initial seed = 67    
```
## Modulation Schemes
### BPSK - Binary Phase Shift Keying:
BPSK is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Parameters
```
Random Integer Generator Set size = 2
Phase offset (rad) = 0
```
### Block Diagram
![BPSK Scheme](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/Scheme.png)

### At Transmitter Side -Modulator- (Before Noise)
![BPSK Before Noise](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/Before%20Noise.png)

### At Receiver Side -Demodulator- (After Noise = -10 db)
![BPSK Noise -10](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/After%20Noise%20at%20-10%20db.png)

### At Receiver Side -Demodulator- (After Noise = 10 db)
![BPSK Before Noise](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/After%20Noise%20at%2010%20db.png)

### BER Diagram
![BER Diagram](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/BER%20Diagram.png)
___
### QPSK - Quadrature Phase Shift Keying:
Quadrature Phase Shift Keying (QPSK) is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

### Parameters
```
Random Integer Generator Set size = 4
Phase offset (rad) = pi/4
```
### Block Diagram
![QPSK Scheme](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/QPSK/Figures/Scheme.png)

### At Transmitter Side -Modulator- (Before Noise)
![QPSK Before Noise](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/QPSK/Figures/Before%20Noise.png)

### At Receiver Side -Demodulator- (After Noise = -10 db)
![QPSK Noise -10](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/QPSK/Figures/After%20Noise%20at%20-10%20db.png)

### At Receiver Side -Demodulator- (After Noise = 10 db)
![QPSK Before Noise](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/QPSK/Figures/After%20Noise%20at%2010%20db.png)

### BER Diagram
![BER Diagram](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/QPSK/Figures/BER%20Diagram.png)
___
