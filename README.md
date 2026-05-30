Digital Elevator Controller

Overview
This project implements a digital elevator controller for a 10-floor building using finite state machine (FSM) design principles. The system accepts a destination floor, moves the elevator to the requested location, opens the door upon arrival, and returns to an idle state when passengers exit.

Course
ECE 2300L – Digital Logic Principles

Team Members
- Ty Instone
- Jeffrey Gomringer
- Glanda San

Project Features
- Finite State Machine (FSM) control
- Up/Down floor tracking
- Destination floor storage
- Comparator-based floor detection
- Door control logic
- CircuitVerse simulation
- Physical hardware prototype

Hardware Used
- 74LS04 Inverter
- 74LS08 AND Gates
- 74LS32 OR Gates
- 74LS74 D Flip-Flop
- 74LS190 Up/Down Counter
- 74LS163 Register
- 74LS85 Comparator
- 555 Timer
- LEDs
- Breadboards

How It Works
1. User selects a destination floor.
2. Destination is stored in a register.
3. Comparator compares current floor and destination.
4. FSM determines movement direction.
5. Elevator moves until destination is reached.
6. Door opens and remains open until riders exit.

Challenges Encountered
- Debugging floating inputs
- FSM implementation
- Latch behavior issues
- Door signal logic
- Physical wiring and testing

 What I Learned
- FSM design
- Hardware debugging
- Counter and comparator integration
- Circuit prototyping
- Team-based engineering development

Future Improvements
- Physical moving elevator
- LCD floor display
- Multiple floor requests
- Emergency stop system
- Motorized doors

