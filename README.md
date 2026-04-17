# light-tracking-robot
Sensor-based autonomous robot for light tracking using differential sensing
# Braitenberg Light-Tracking Robot (Design–Build–Test Project)

## Overview

This project involved the design, construction, and testing of a Braitenberg vehicle using the LEGO Mindstorms EV3 platform. The system demonstrates how simple sensor-motor connections can produce complex autonomous behaviours.

## System Architecture

* Dual light sensors for differential sensing
* EV3 microcontroller for control logic
* Motor-driven differential drive system
* Modular mechanical design using LEGO components

## Behaviours Implemented

The robot was developed across three stages with increasing complexity:

### Vehicle 1: Basic Behaviour

* Forward/backward motion
* Single-sensor light response

### Vehicle 2: Reactive Behaviour

* Dual-sensor attraction and repulsion ("Love" and "Fear")
* Directional control based on light intensity differences

### Vehicle 3: Inhibited Control

* Speed modulation based on sensor input
* Smooth stopping and improved stability near light source

## Experimental Analysis

* Characterised sensor response vs distance and angle
* Identified hardware limitations such as:

  * Sensor asymmetry (up to ~24% variation)
  * Narrow field of view (±40° effective range)
* Analysed system stability and tracking behaviour across configurations
* Evaluated stopping distance and response consistency over multiple trials

## Key Engineering Insights

* Simple control laws can generate complex behaviour (Braitenberg principle)
* Sensor limitations significantly impact system performance
* Feedback-based control improves stability and repeatability

## Tools & Components

* LEGO Mindstorms EV3 platform
* EV3 graphical programming environment
* Light sensors and motor control system

## Learning Outcomes

* Sensor-based control systems design
* Experimental testing and data analysis
* Iterative system development (Design–Build–Test methodology)
* Understanding of real-world hardware limitations in robotics
