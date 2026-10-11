# Space Station Escape Pod Controller

A sequential digital logic circuit designed.

## Overview

This project implements an 8-state escape pod launch controller using flip-flops and combinational logic gates. The controller follows a normal launch sequence and responds to emergency inputs by aborting or accelerating the sequence, depending on the current state.

## Features

- 8-state finite-state controller using three state bits
- Normal launch sequence and emergency-state transitions
- Combinational logic for next-state and output generation
- Green and red status LEDs
- Physical implementation using a breadboard and digital logic components

## Design Process

- Developed a state-transition diagram and transition table.
- Used Karnaugh maps to simplify the next-state and output Boolean equations.
- Created a circuit schematic from the simplified equations.
- Built the circuit and tested its normal and emergency behavior.

## Hardware Demonstration

The physical circuit was built and tested on a breadboard. The demonstration shows the state LEDs and status outputs responding to the clock and emergency input.

**Video demonstration:** [Insert video link]

## Technologies and Concepts

- Digital Logic Design
- Finite-State Machines
- Sequential Circuits
- Flip-Flops
- Boolean Algebra
- Karnaugh Maps
- Combinational Logic
- Breadboard Prototyping

## Academic Context

Completed as part of Penn State's CMPEN 270 coursework
