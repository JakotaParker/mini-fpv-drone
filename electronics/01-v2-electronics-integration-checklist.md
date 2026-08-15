# V2 Drone — Electronics Integration Checklist

Use this checklist to guide the V2 drone from completed frame to first powered flight.

---

## Phase 1 — Electronics Planning

- [x] Create an electronics assembly sequence before soldering anything
- [x] Review the exact SpeedyBee F405 AIO wiring and pad diagram
- [ ] Identify the connection point for each subsystem:
  - [x] Motor 1
  - [x] Motor 2
  - [x] Motor 3
  - [x] Motor 4
  - [x] Battery / XT30
  - [x] Capacitor
  - [x] Receiver
  - [x] FPV camera
  - [x] TX800 VTX
  - [ ] Buzzer, if used
- [ ] Identify the required power rails and signals:
  - [x] VBAT
  - [x] 5V
  - [x] Ground
  - [x] UART TX
  - [x] UART RX
  - [x] Video signal
  - [x] Motor phases
- [x] Create the complete electrical wiring diagram
- [ ] Label every wire and destination pad
- [ ] Create a physical wire-routing plan for the V2 frame
- [ ] Decide the electronics stack / component placement order
- [ ] Confirm USB access after the AIO is installed
- [ ] Confirm planned wire paths cannot reach the propellers
- [ ] Save the wiring diagram to the GitHub repository

---

## Phase 2 — Parts Arrival and Unboxing

### Documentation Setup

- [x] Set up camera / Meta glasses before opening packages
- [X] Record all packages together
- [x] Record the unboxing of each major component
- [x] Capture close-up footage of each electronic component
- [x] Capture the V2 frame beside the real components
- [x] Photograph component labels, model numbers, and connectors

### Initial Inspection

- [X] Inspect every package for shipping damage
- [x] Confirm each received component matches the ordered model
- [x] Confirm all expected accessories and cables are included
- [x] Do not solder anything yet

---

## Phase 3 — Physical Component Verification

Measure every component with digital calipers and compare the measurements against the CAD envelopes and manufacturer specifications.

### Motors

- [x] Measure motor diameter
- [x] Measure motor height
- [x] Measure shaft diameter
- [x] Measure mounting-hole spacing
- [x] Verify mounting screw size
- [x] Verify motor screws do not extend into the motor windings

### SpeedyBee F405 AIO

- [x] Measure board length
- [x] Measure board width
- [x] Measure board thickness / installed height
- [x] Measure mounting-hole spacing
- [x] Measure mounting-hole diameter
- [x] Verify USB connector location
- [x] Verify battery pads
- [x] Verify motor pads
- [x] Verify UART pads
- [x] Verify video pads

### RunCam Nano 4

- [x] Measure camera width
- [x] Measure camera height
- [x] Measure camera depth
- [x] Verify cable exit direction
- [x] Verify lens clearance

### SpeedyBee TX800 VTX

- [x] Measure board length
- [x] Measure board width
- [x] Measure board thickness
- [x] Verify antenna connector orientation
- [x] Verify power / signal connection locations

### Receiver

- [x] Measure receiver length
- [x] Measure receiver width
- [x] Measure receiver thickness
- [x] Verify antenna arrangement
- [x] Verify wire / pad orientation

### Battery

- [x] Measure battery length
- [x] Measure battery width
- [x] Measure battery height
- [x] Measure battery weight
- [x] Verify XT30 lead length
- [x] Verify battery orientation in the frame

### Other Components

- [x] Verify propeller diameter
- [x] Verify propeller shaft / mounting interface
- [ ] Measure antenna dimensions
- [ ] Verify capacitor dimensions
- [ ] Verify hardware and screw dimensions

### Documentation

- [x] Update `07-component-inventory.md`
- [x] Change verified measurements to **Physically Verified**
- [x] Record any differences between listed and measured dimensions
- [x] Photograph caliper measurements where useful

---

## Phase 4 — V2 Frame Fit Test

Install or position every component without permanent wiring.

### Motors and Propulsion

- [ ] Mount all four motors
- [ ] Verify motor-hole alignment
- [ ] Verify screw length
- [ ] Temporarily install props or use prop envelopes to verify clearance
- [ ] Check full propeller sweep

### Electronics

- [ ] Position the AIO
- [ ] Position the FPV camera
- [ ] Position the TX800
- [ ] Position the receiver
- [ ] Position the antenna
- [ ] Position the capacitor
- [ ] Position the battery

### Clearance Checks

- [ ] Check propeller clearance
- [ ] Check USB-port accessibility
- [ ] Check battery-connector routing
- [ ] Check antenna clearance
- [ ] Check camera field of view
- [ ] Check camera lens protection
- [ ] Check that motor wires can reach the AIO
- [ ] Check receiver wire routing
- [ ] Check VTX wire routing
- [ ] Check camera wire routing
- [ ] Check that no wire can enter the propeller sweep
- [ ] Check that components do not interfere with one another

### Documentation

- [ ] Photograph the complete mock assembly
- [ ] Record any fitment problems
- [ ] Update CAD if required
- [ ] Update GitHub documentation with fit-test results

---

## Phase 5 — TPU Mount Verification and Printing

### Before Printing

- [ ] Compare each TPU CAD model against real component measurements
- [ ] Correct dimensions if necessary
- [ ] Add appropriate TPU fit clearance / tolerance
- [ ] Confirm screw holes and slots align
- [ ] Confirm wire-routing openings remain accessible

### TPU Print Testing

- [ ] Slice the smallest / fastest TPU mount first
- [x] Run a TPU calibration print
- [ ] Inspect print quality
- [ ] Test-fit the component
- [ ] Adjust CAD if necessary
- [ ] Reprint the test mount if required

### Final TPU Parts

- [x] Print battery mount
- [ ] Print camera mount, if TPU
- [ ] Print antenna mount
- [ ] Print receiver mount, if used
- [ ] Print VTX mount / retention part, if used
- [ ] Test-fit every finished TPU part

### Documentation

- [ ] Record TPU slicer settings
- [ ] Photograph or record TPU printing
- [ ] Document fit adjustments
- [ ] Export updated STL / STEP files to GitHub

---

## Phase 6 — Electronics Bench Test

Before permanently installing or soldering the complete system:

### Inspection

- [ ] Inspect AIO for visible damage
- [ ] Inspect motor wires and windings
- [ ] Inspect receiver
- [ ] Inspect TX800
- [ ] Inspect camera
- [ ] Inspect antenna connectors
- [ ] Inspect battery connector

### Flight Controller

- [ ] Connect the AIO to the computer using a known-good USB data cable
- [ ] Verify the flight controller powers from USB
- [ ] Verify Betaflight Configurator detects the flight controller
- [ ] Record the current firmware version
- [ ] Save a backup / dump of the original Betaflight configuration
- [ ] Verify board orientation in Betaflight

### Peripheral Planning

- [ ] Confirm receiver protocol
- [ ] Confirm required UART for receiver
- [ ] Confirm VTX control method
- [ ] Confirm camera voltage requirement
- [ ] Confirm receiver voltage requirement
- [ ] Confirm TX800 voltage requirement
- [ ] Compare all requirements against the wiring diagram

- [ ] Do not connect the LiPo until battery wiring has been completed and inspected

---

## Phase 7 — Soldering

Keep propellers removed during the entire electronics setup process.

### Preparation

- [ ] Prepare soldering iron
- [ ] Prepare solder and flux
- [ ] Prepare wire cutters and wire strippers
- [ ] Prepare heat shrink
- [ ] Prepare multimeter
- [ ] Prepare smoke stopper
- [ ] Secure the board in a PCB holder / helping hands
- [ ] Tin wires before attaching them
- [ ] Tin pads as appropriate

### Suggested Soldering Order

1. [ ] Battery lead / XT30
2. [ ] Capacitor
3. [ ] Motor 1
4. [ ] Motor 2
5. [ ] Motor 3
6. [ ] Motor 4
7. [ ] Receiver
8. [ ] FPV camera
9. [ ] TX800 VTX
10. [ ] Buzzer / remaining accessories

### After Each Subsystem

- [ ] Inspect solder joints
- [ ] Check for solder bridges
- [ ] Verify polarity
- [ ] Verify correct pad selection
- [ ] Perform continuity checks where appropriate
- [ ] Check wire strain relief
- [ ] Photograph completed connections
- [ ] Update wiring documentation if routing changes

### Before First LiPo Connection

- [ ] Perform final visual inspection
- [ ] Check XT30 polarity
- [ ] Check VBAT-to-GND for an unintended short
- [ ] Verify capacitor polarity
- [ ] Verify every powered peripheral's polarity
- [ ] Remove propellers
- [ ] Connect LiPo through a smoke stopper
- [ ] Verify normal startup
- [ ] Disconnect immediately if the smoke stopper indicates a fault

---

## Phase 8 — Betaflight Configuration

### Flight Controller

- [ ] Confirm FC orientation
- [ ] Verify accelerometer response
- [ ] Verify gyro response
- [ ] Calibrate accelerometer if appropriate

### Receiver

- [ ] Configure receiver UART
- [ ] Configure receiver protocol
- [ ] Bind transmitter to receiver
- [ ] Verify channel inputs
- [ ] Verify channel mapping
- [ ] Set arm switch
- [ ] Configure desired flight modes
- [ ] Configure and test failsafe

### Motors

**Propellers must remain removed.**

- [ ] Verify motor 1 assignment
- [ ] Verify motor 2 assignment
- [ ] Verify motor 3 assignment
- [ ] Verify motor 4 assignment
- [ ] Verify each motor spins
- [ ] Verify motor direction
- [ ] Correct motor direction if required

### FPV System

- [ ] Verify camera powers correctly
- [ ] Verify video feed
- [ ] Configure VTX
- [ ] Verify VTX channel / band / power configuration
- [ ] Verify antenna is connected before transmitting

### Configuration Backup

- [ ] Save final Betaflight configuration
- [ ] Export CLI `diff all`
- [ ] Store configuration backup in GitHub documentation

---

## Phase 9 — Final Assembly

- [ ] Install TPU mounts
- [ ] Secure AIO
- [ ] Secure receiver
- [ ] Secure TX800
- [ ] Secure FPV camera
- [ ] Secure antenna
- [ ] Secure capacitor
- [ ] Route motor wires
- [ ] Route receiver wires
- [ ] Route camera / VTX wires
- [ ] Add heat shrink where needed
- [ ] Add strain relief where needed
- [ ] Secure battery lead
- [ ] Verify USB port remains accessible
- [ ] Verify antenna cannot enter propeller sweep
- [ ] Verify battery cannot move into propeller sweep
- [ ] Verify no wire can touch a propeller
- [ ] Verify no screw is loose
- [ ] Install battery
- [ ] Measure final all-up weight
- [ ] Photograph the completed V2 drone

---

## Phase 10 — First Flight Preparation

### Final Safety Inspection

- [ ] Check all frame screws
- [ ] Check all motor screws
- [ ] Check electronics mounting
- [ ] Inspect solder joints
- [ ] Inspect battery lead
- [ ] Inspect antenna
- [ ] Verify receiver connection
- [ ] Verify FPV video
- [ ] Perform receiver range check
- [ ] Perform failsafe test
- [ ] Verify motor order
- [ ] Verify motor direction
- [ ] Verify propeller orientation

### Propeller Installation

Only install propellers after all motor and failsafe testing is complete.

- [ ] Install correct propeller on Motor 1
- [ ] Install correct propeller on Motor 2
- [ ] Install correct propeller on Motor 3
- [ ] Install correct propeller on Motor 4
- [ ] Verify propeller orientation one final time

### First Hover

- [ ] Select a safe open test area
- [ ] Power the drone
- [ ] Verify receiver and video link
- [ ] Arm from a safe distance
- [ ] Perform a short low-altitude hover
- [ ] Land
- [ ] Disarm
- [ ] Disconnect battery
- [ ] Inspect the drone after the hover
- [ ] Check motor temperatures
- [ ] Check electronics mounting
- [ ] Check frame and TPU mounts
- [ ] Record any problems or changes required

---

## Phase 11 — Engineering Documentation

- [ ] Update `07-component-inventory.md`
- [ ] Add final wiring diagram
- [ ] Add physical electronics layout
- [ ] Add soldering / wiring photos
- [ ] Record final component locations
- [ ] Record final wire-routing decisions
- [ ] Record Betaflight configuration
- [ ] Record TPU settings
- [ ] Record completed drone weight
- [ ] Document problems encountered
- [ ] Document design changes made after physical testing
- [ ] Update V2 CAD / STEP / STL files if required
- [ ] Commit completed V2 integration documentation to GitHub

---

## Build Status

- [ ] Mechanical V2 frame complete
- [ ] Components physically verified
- [ ] TPU mounts complete
- [ ] Wiring diagram complete
- [ ] Electronics bench-tested
- [ ] Soldering complete
- [ ] First power-up successful
- [ ] Betaflight configured
- [ ] Final assembly complete
- [ ] First hover successful
- [ ] V2 documentation complete
