# TOM Remote Control Car

## Overview

TOM Remote Control Car is a hardware adaptation project based on an existing RF remote-controlled car.
The project focuses on modifying the original remote-control unit by interfacing external switches with the remote-control PCB, while preserving the original wireless communication system of the car.

The main technical idea is to map the original button contacts on the remote PCB, solder parallel wired connections to these contact points, and connect them to external control devices such as large push buttons and foot pedals.

## Project Goal

The goal of this project is to redesign the physical control interface of a standard remote-controlled car without changing its internal RF communication system.

## Technical Description

The original remote-control PCB was opened and analyzed in order to identify the contact points of each control button.
After mapping the button connections, wires were soldered in parallel to the original tactile switches. These wires were then routed to external input devices, allowing the same electrical signals to be triggered from outside the original remote casing.

The project includes:

* PCB contact mapping
* Hardware reverse engineering
* Soldering to button contact points
* Parallel switch wiring
* External switch interfacing
* Mechanical adaptation of the control interface
* Preservation of the original RF communication system

## Control Interface

Several external control options were designed and tested:

* Foot pedals
* Low push buttons
* Raised push buttons

Each control option activates the original remote-control circuit through a wired connection, allowing the car to respond exactly as it would when pressing the original remote buttons.

## System Architecture

```text
External Buttons / Foot Pedals
              ↓
Wired Switch Connections
              ↓
Original Remote-Control PCB
              ↓
RF Wireless Communication
              ↓
Remote-Control Car
```

## Main Features

* Uses the original remote-control electronics
* No modification to the car’s RF receiver
* External buttons connected in parallel to original remote buttons
* Simple and reliable hardware implementation
* Modular input options for different control layouts
* Combines electronics, soldering, and mechanical prototyping

## Tools and Components

* RF remote-controlled car
* Original remote-control PCB
* External push buttons
* Foot pedals
* Wires
* Soldering equipment
* Basic hand tools
* Mechanical mounting materials

## Project Images

Add photos of the project here:

```markdown
![Remote PCB](images/remote-pcb.jpg)
![External buttons](images/external-buttons.jpg)
![Final setup](images/final-setup.jpg)
```

## Demo Video

Add a demo video link here:

```markdown
[Watch the demo video](https://...)
```

## Applications

This project demonstrates how an existing consumer electronic device can be adapted through hardware interface modification.
It is especially relevant for accessibility-oriented design, assistive technology, and educational hardware prototyping.

## Skills Demonstrated

* Hardware modification
* Circuit analysis
* PCB contact identification
* Soldering
* Switch interfacing
* RF system preservation
* Mechanical adaptation
* User-centered engineering design

## Author

Paz Mizrahi
Electrical and Electronics Engineering Student
