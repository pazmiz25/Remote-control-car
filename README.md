# TOM Remote Control Car

## Overview

TOM Remote Control Car is a hardware adaptation project based on an existing RF remote-controlled car.
The project focuses on modifying the original remote-control unit by connecting external switches to the remote-control PCB, while preserving the original wireless communication system of the car.

The main technical idea is to map the original button contacts on the remote PCB, solder parallel wired connections to these contact points, and connect them to external control devices such as foot pedals, low push buttons, and raised push buttons.

## Project Goal

The goal of this project is to redesign the physical control interface of a standard remote-controlled car without changing the car’s internal RF communication system.

Instead of replacing the electronics, the original remote-control circuit was reused, and only the input interface was modified.

## Technical Description

The original remote-control PCB was opened and analyzed in order to identify the contact points of each control button.
After mapping the button connections, wires were soldered in parallel to the original tactile switches. These wires were routed to external input devices, allowing the same electrical signals to be activated from outside the original remote casing.

The project includes:

* PCB contact mapping
* Hardware reverse engineering
* Soldering to button contact points
* Parallel switch wiring
* External switch interfacing
* Mechanical adaptation of the control interface
* Preservation of the original RF wireless communication system

## Control Interface

Three external control options were designed and tested:

* Foot pedals
* Low push buttons
* Raised push buttons

Each control option activates the original remote-control circuit through a wired connection, allowing the car to respond the same way it would when pressing the original remote buttons.

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
* Preserves the original RF communication system
* No modification to the car’s receiver circuit
* External buttons connected in parallel to the original remote buttons
* Modular input options for different control layouts
* Combines electronics, soldering, wiring, and mechanical prototyping

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

### Raised Button Interface

![High Buttons](Assets/High%20buttons.png)

### Foot Pedal Interface

![Leg Buttons](Assets/Leg%20buttons.png)

### Low Button Interface

![Low Buttons](Assets/Low%20buttons.png)

## Demo Video

[Watch the demo video](Assets/Video.mp4)

## Applications

This project demonstrates how an existing consumer electronic device can be adapted through hardware interface modification.
It is relevant to hardware prototyping, assistive technology, accessibility-oriented design, and educational electronics projects.

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
