# Engine Fuel Economy Improvement Using MATLAB Simulink

A PID-based closed-loop engine control system simulated in MATLAB Simulink R2020b.

## Project Overview
This model simulates how a PID controller maintains the correct air-fuel ratio 
in an engine, improving fuel economy by automatically adjusting fuel injection 
when load conditions change.

## Files
- `engine_control.slx` — Simulink model
- `Screenshot 2026-02-27 155049.png` — Engine Speed / AF Ratio Output scope
- `Screenshot 2026-02-27 155059.png` — Controller Output Signal scope
- `Screenshot 2026-02-27 155112.png` — Error Signal scope

## Results
- Output settles at setpoint (1.0) within ~1 second
- Zero steady-state error
- No oscillation or overshoot
- PID gains: Kp=100, Ki=10, Kd=5

## Tools Used
- MATLAB R2020b
- Simulink
