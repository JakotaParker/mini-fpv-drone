# 05 — Test Plan

Testing progresses from the lowest-risk level to the highest-risk level. Do not skip directly to flight testing.

## Test Sequence

### T1 — CAD Review

Check:
- Motor-hole spacing
- Flight-controller-hole spacing
- Propeller clearance
- Camera dimensions
- Battery dimensions
- Wire-routing space
- USB access
- Fastener access

Result: `PASS / FAIL / NOT TESTED`

### T2 — Print Completion

Record:
- Material
- Nozzle diameter
- Nozzle temperature
- Bed temperature
- Layer height
- Wall count
- Infill percentage and pattern
- Print speed
- Supports
- Print duration
- Failure location, if any

Result: `PASS / FAIL / NOT TESTED`

### T3 — Dimensional Inspection

Measure:
- Overall wheelbase
- Motor-hole spacing
- Flight-controller-hole spacing
- Arm thickness
- Electronics-bay dimensions
- Camera-mount dimensions
- Battery area
- Propeller clearance

Result: `PASS / FAIL / NOT TESTED`

### T4 — Component Fit

Check every component without soldering where practical.

Result: `PASS / FAIL / NOT TESTED`

### T5 — Structural Bench Check

Check:
- Arm stiffness
- Layer separation
- Cracks
- Fastener pull-through
- Motor-mount deformation
- Battery retention

Result: `PASS / FAIL / NOT TESTED`

### T6 — Electrical Inspection

With the battery disconnected:
- Inspect solder joints.
- Test continuity.
- Confirm polarity.
- Check for shorts.
- Verify connector orientation.

Result: `PASS / FAIL / NOT TESTED`

### T7 — Smoke-Stopper Power Test

- Remove propellers.
- Use a smoke stopper.
- Watch for heat, smoke, odor, or abnormal current behavior.
- Disconnect immediately if abnormal behavior occurs.

Result: `PASS / FAIL / NOT TESTED`

### T8 — Betaflight Bench Test

- Verify board connection.
- Confirm gyro response.
- Verify receiver channels.
- Configure failsafe.
- Confirm motor order.
- Confirm motor direction.
- Save configuration backup.

Result: `PASS / FAIL / NOT TESTED`

### T9 — Controlled Hover

- Inspect aircraft.
- Use a clear open test area.
- Begin with a low hover.
- Land immediately if oscillation, overheating, signal loss, or structural problems appear.

Result: `PASS / FAIL / NOT TESTED`
