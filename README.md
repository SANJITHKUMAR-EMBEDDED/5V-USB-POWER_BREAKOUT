# USB-C to 3.3V Power Supply

![3D Render of Board](usb_to_3.3v_front)

A simple and robust power supply board that takes 5V from any USB-C port and provides a stable 3.3V output. This is **Project 1** of my #50BoardChallenge to become a job-ready PCB design engineer.

## Features
* USB-C Power Input
* 3.3V LDO Regulator (AP2112K)
* Header pin outputs for both 5V and 3.3V
* 4x 3mm Mounting Holes for stable mounting

## Professional Design Rules
This board was designed using a professional workflow in KiCad:
* **Solid `GND` Plane:** Used a solid copper pour on the bottom layer for low noise and a stable return path.
* **Power Traces:** Used KiCad's **Net Classes** to define wide `20mil` traces for the `+5V`, `+3.3V`, and `GND` nets.
* **Decoupling:** Placed input and output capacitors as close as possible to the regulator for stability.
* **DRC:** The final design passed all Design Rules Checks with **0 errors and 0 warnings**.
