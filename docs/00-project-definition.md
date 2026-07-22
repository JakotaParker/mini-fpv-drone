# 00 — Project Definition

## Project Name

Mini 3-Inch FPV Drone

## Problem Statement

Design and build a compact FPV quadcopter using a custom 3D-printed frame while developing practical skills in CAD, additive manufacturing, electronics, soldering, flight-controller configuration, troubleshooting, and technical documentation.

## Mission

The first completed aircraft should be a manually piloted, line-of-sight and FPV-capable mini quadcopter that can take off, hover, maneuver, land, and survive normal beginner-level testing.

Autonomous capability is outside the first build scope, but the project should establish skills and architecture that can support later embedded-systems and autonomous-drone work.

## Scope

### Included in the Initial Build

- Custom 3D-printed frame
- Four brushless motors
- Flight controller
- Electronic speed-control system
- ExpressLRS receiver
- FPV camera
- Video transmitter
- Antenna
- LiPo battery
- Radio transmitter
- FPV goggles
- Betaflight setup
- Bench testing
- Controlled flight testing
- Engineering documentation

### Not Included in the Initial Build

- GPS navigation
- Autonomous waypoint flight
- Computer vision
- Payload delivery
- Long-range operations
- Military or weapon applications
- Fully optimized production-grade frame

## Current State

- Frame V1 CAD: complete in Onshape
- Full Frame V1 print: not yet validated
- Electronics layout: preliminary
- Final component selection: incomplete
- Wiring: not started
- Firmware configuration: not started
- Flight testing: not started

## Design Constraints

- Printer: Ender 3 V2
- Prototype material: PLA+
- Propeller class: 3 inch
- Frame should be printable on the available printer
- Components must remain accessible for repair
- Propellers must have adequate clearance
- Wiring must avoid propellers and sharp frame edges
- Battery and electronics must be securely retained
- The first aircraft should prioritize learning, repairability, and safe testing over maximum performance

## Success Criteria

The first build is successful when it can:

1. Complete a full frame print without a critical manufacturing defect.
2. Fit the selected motors, flight controller, camera, receiver, VTX, and battery-retention hardware.
3. Pass continuity and smoke-stopper testing.
4. Connect to Betaflight and correctly recognize the receiver and sensors.
5. Spin each motor in the correct direction under controlled bench conditions.
6. Arm safely.
7. Perform a stable takeoff, hover, controlled maneuver, and landing.
8. Produce enough documentation for the build to be reproduced or improved.

## Open Decisions

- Exact wheelbase
- Target all-up weight
- Motor size and KV
- Propeller type
- Battery cell count and capacity
- AIO versus separate flight-controller and ESC architecture
- Receiver model
- FPV camera and VTX
- Frame material after PLA+ prototyping
- Final budget
