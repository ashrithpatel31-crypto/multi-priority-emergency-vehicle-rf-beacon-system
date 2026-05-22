# Multi-Priority Emergency Vehicle RF Beacon Signal Circuit

## Project Overview
This project is designed to provide intelligent traffic signal control for emergency vehicles using RF communication technology.

The system provides priority access to:
- Ambulance
- Fire Truck
- Police Vehicle

An automatic reset circuit restores normal traffic operation after the emergency vehicle passes.

---

## Features
- RF-based wireless communication
- Emergency vehicle priority logic
- Automatic traffic signal control
- Automatic reset using 555 Timer
- Low-cost hardware implementation
- Smart traffic management prototype

---

## Technologies Used
- RF Transmitter & Receiver (433 MHz)
- NE555 Timer IC
- Logic Gates
- LED Traffic Signals
- PCB Prototype Design
- Tinkercad Simulation

---

## System Architecture

![System Architecture](block-diagram/system-architecture.png)

---

## Circuit Diagram

![Circuit Diagram](circuit-diagram/rf-beacon-circuit-diagram.png)

---

## Traffic Signal Timing Diagram

![Timing Diagram](images/traffic-signal-waveform.png)

---

## Hardware Prototype

![Hardware Setup](hardware-setup/hardware-prototype.jpg)

---

## Working Principle

1. Emergency vehicle activates RF transmitter.
2. RF signal is transmitted wirelessly.
3. RF receiver detects the signal.
4. Priority logic circuit processes the signal.
5. Traffic signal changes to green.
6. Emergency vehicle passes intersection.
7. Automatic reset circuit restores normal traffic operation.

---

## Emergency Vehicle Priority Levels

| Vehicle Type | Priority Level |
|--------------|----------------|
| Ambulance | Highest |
| Fire Truck | Medium |
| Police Vehicle | Lowest |

---

## Components Used

- 433 MHz RF Transmitter Module
- 433 MHz RF Receiver Module
- NE555 Timer IC
- Logic Gate ICs
- LEDs
- Push Button Switches
- Resistors
- Capacitors
- PCB Board
- Power Supply

---

## Simulation

Tinkercad simulation was used to test:
- RF communication
- Priority logic operation
- Traffic signal switching
- Automatic reset functionality

---

## Applications

- Smart City Traffic Systems
- Emergency Vehicle Management
- Intelligent Transportation Systems
- Disaster Response Systems
- Military Convoy Management

---

## Advantages

- Faster emergency response time
- Reduced traffic congestion
- Reliable wireless communication
- Simple hardware implementation
- Low-cost design
- Easy maintenance

---

## Future Enhancements

- IoT Integration
- GPS-based Vehicle Detection
- AI-based Traffic Optimization
- Cloud-based Monitoring System
- Smart City Deployment

---

## Project Documentation

📄 [Project Report](docs/project-report.pdf)

📊 [Project Presentation](presentation/project-presentation.pptx)

---

## Hardware Setup

The hardware prototype was implemented using RF modules, logic gate circuits, LEDs, and a 555 timer-based automatic reset circuit.

---

## Authors

- Akula Ashrith
- Salendra Daya Sagar
- Boda Rohith Reddy
- Velpula Rama Krishna

Department of Electronics and Communication Engineering  
Anurag University

---

## License

This project is developed for academic and educational purposes.
