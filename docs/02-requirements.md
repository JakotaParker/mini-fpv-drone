# 02 — Requirements

Use `MUST`, `SHOULD`, and `MAY` to distinguish required, preferred, and optional features.

## Airframe Requirements

- **AF-001:** The frame MUST fit within the Ender 3 V2 build area.
- **AF-002:** The frame MUST support four motors intended for 3-inch propellers.
- **AF-003:** The design MUST provide adequate propeller-to-frame clearance.
- **AF-004:** The design MUST provide a defined flight-controller mounting pattern.
- **AF-005:** The design MUST provide a secure battery-retention method.
- **AF-006:** The design MUST keep wiring away from propeller paths.
- **AF-007:** The design SHOULD allow damaged components to be replaced without destroying the frame.
- **AF-008:** The frame SHOULD include accessible USB and battery connections.
- **AF-009:** The frame SHOULD include replaceable camera or antenna mounts.

## Manufacturing Requirements

- **MF-001:** Frame V1 MUST complete a supervised full print before being approved for assembly.
- **MF-002:** Print settings MUST be recorded for every test.
- **MF-003:** Failed prints MUST include a short failure description and corrective action.
- **MF-004:** Critical mounting dimensions MUST be measured after printing.
- **MF-005:** The prototype SHOULD print without requiring excessive support material.

## Electronics Requirements

- **EL-001:** The power system MUST be compatible with the selected battery voltage.
- **EL-002:** The ESC current rating MUST provide appropriate margin for the selected motors and propellers.
- **EL-003:** The receiver MUST be compatible with the selected radio protocol.
- **EL-004:** The flight controller MUST provide the required UARTs and motor outputs.
- **EL-005:** All solder joints MUST be visually inspected before power is applied.
- **EL-006:** Initial power-up MUST use a smoke stopper.
- **EL-007:** Continuity MUST be checked before connecting a LiPo battery.

## Firmware Requirements

- **FW-001:** A Betaflight configuration backup MUST be saved before major configuration changes.
- **FW-002:** Receiver input MUST be verified without propellers installed.
- **FW-003:** Motor order and direction MUST be verified without propellers installed.
- **FW-004:** Failsafe behavior MUST be configured and tested.
- **FW-005:** Arming controls MUST be deliberately assigned and documented.

## Test Requirements

- **TS-001:** Propellers MUST remain removed during electronics bench testing.
- **TS-002:** The first hover test MUST occur in a controlled open area.
- **TS-003:** A preflight inspection MUST be completed before every test flight.
- **TS-004:** Damage, instability, overheating, or signal loss MUST stop the test.
