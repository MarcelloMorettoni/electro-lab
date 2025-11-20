# ElectroLab Open

ElectroLab Open is a simulator built with HTML5 Canvas, TailwindCSS, and a custom real-time circuit solver.  
The goal is to provide a clean, intuitive interface suitable for learning electronics, prototyping circuits, and experimenting with microcontrollers — all running client-side with no backend.

---

## Demo

![ElectroLab Screenshot](./screen.png)

---

## Features

### Interactive Circuit Building
- Drag-and-drop components  
- Snap-to-grid canvas  
- Visual pins and color-coded wiring  
- Real-time measurement updates  
- Smooth editing with a simple, minimal interface  

### Power Components
- Batteries (AA and 9V)
- Variable DC supply
- AC source (sine wave)
- Solar cell
- Function generator

### Passive Components
- Resistor  
- Potentiometer  
- Capacitor  
- Inductor  
- Thermistor  
- LDR

### Switches and Relays
- SPST switch  
- Push button  
- SPDT relay

### Diodes and Rectifiers
- Standard diode  
- LED  
- RGB LED  
- Bridge rectifier  

### Transistors
- NPN BJT  
- N-channel MOSFET  

### Analog ICs
- 741 operational amplifier  
- 7805 voltage regulator  

### Digital and Logic Components
- AND gate  
- NOT gate  
- 555 timer  

### Sensors
- Ultrasonic sensor  

### Actuators
- DC motor  
- Servo motor  
- Buzzer  

### Displays
- 7-segment display  
- LCD 16×2 (simplified I²C model)

### Microcontroller
- Arduino Uno (abstract pins)

### Measurement Tools
- Voltmeter  
- Oscilloscope with real-time waveform rendering  

### Connectors
- Ground  
- VCC node

---

## Simulation Engine

ElectroLab includes a custom lightweight node-based solver with:
- Union-Find node grouping  
- Relaxation voltage solver  
- AC waveform generation  
- Component-specific behavior models (LED thresholding, motor RPM, relay coil actuation, 7-segment decoding, oscilloscope sampling)

The simulation runs in real time at approximately 60 frames per second.

---

## Installation and Usage

### Local Usage
Clone the repository and open the HTML file in any modern browser.
