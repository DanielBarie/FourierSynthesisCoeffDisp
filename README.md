# Fourier Synthesis Demo App with Coefficient Display
Fourier Synthesis Demo App with Coefficient Display

# Implemented Functions
## Rectangular 1
Rectangular Pulse Train without DC Offset.
![Rectangular Pulse Train #1](rectangular_1.png)
```
f = rectangularPulse(-1,1,x)  + rectangularPulse(-1,1,x-3) + rectangularPulse(-1,1,x+3) -.5;
```
Period is 3.

## Rectangular 2
Rectangular Pulse Train with DC Offset.
![Rectangular Pulse Train #2](rectangular_2.png)
```
f = rectangularPulse(-1,1,x)  + rectangularPulse(-1,1,x-3) + rectangularPulse(-1,1,x+3);
```
Period is 3.

