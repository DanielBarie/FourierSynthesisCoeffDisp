# Fourier Synthesis Demo App with Coefficient Visual Display
Fourier Synthesis Demo App with Coefficient Display

![App Main Screen](app_screen.png)

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

