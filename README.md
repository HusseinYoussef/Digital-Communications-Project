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
It is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Parameters
```
Random Integer Generator Set size = 2
Phase offset (rad) = 0
```
### Block Diagram
![BPSK Scheme](https://github.com/HusseinYoussef/Digital-Communications-Project/blob/master/BPSK/Figures/Scheme.png)

