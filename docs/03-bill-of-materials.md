# 03 — Bill of Materials

Do not mark a component as selected until its dimensions, voltage, current rating, protocol, and mounting compatibility have been checked.

| Subsystem | Component | Candidate / Part Number | Qty | Selected? | Cost | Compatibility Notes |
|---|---|---:|---:|---|---:|---|
| Airframe | Custom Frame V1 | Onshape design | 1 | Prototype | TBD | Full print not validated |
| Propulsion | Brushless motor | TBD | 4 | No | TBD | Match prop, voltage, mounting pattern |
| Propulsion | 3-inch propeller set | TBD | 2+ sets | No | TBD | Check shaft and frame clearance |
| Control | Flight controller / AIO | TBD | 1 | No | TBD | Check mounting, UARTs, ESC rating |
| Radio | ELRS receiver | TBD | 1 | No | TBD | Match transmitter frequency |
| FPV | FPV camera | TBD | 1 | No | TBD | Check voltage and physical dimensions |
| FPV | Video transmitter | TBD | 1 | No | TBD | Check voltage, output, mounting |
| FPV | VTX antenna | TBD | 1 | No | TBD | Match connector and frequency |
| Power | LiPo battery | TBD | 2+ | No | TBD | Match cell count and connector |
| Power | Battery connector | TBD | 1 | No | TBD | Match current demand |
| Hardware | Screws / standoffs | TBD | Set | No | TBD | Match frame and electronics |
| Safety | Smoke stopper | Existing or TBD | 1 | TBD | TBD | Required for first power-up |
| Safety | LiPo-safe charging/storage gear | TBD | 1 | TBD | TBD | Required for battery handling |

## BOM Decision Checklist

Before selecting a part, confirm:

- Physical dimensions
- Mounting-hole pattern
- Weight
- Input voltage
- Current rating
- Connector type
- Radio/video protocol
- Firmware support
- Seller reputation
- Replacement availability
- Total system compatibility

## Component Compatibility Matrix

| Component | Candidate | Dimensions | Weight | Voltage | Mounting Pattern | Interface | Status | Cost | QTY | Vendor |
|---|---|---:|---:|---:|---|---|---|---|---|
| AIO | SpeedyBee F405 AIO 35A Bluejay No case | 33 x 33 mm | 8.9 g | TBD | 25.5 × 25.5 mm | USB/UART/Motor outputs | Selected |
| Motor | SpeedyBee 1401 V2 | 14 mm x 4 mm | TBD | 4600 KV | 9 × 9 mm M2 | 3 phase wires | Selected |
| Propeller | Gemfan 3016 | 3 inch | TBD | N/A | 1.5 mm shaft | N/A | Selected |
| FPV camera | RunCam Nano 4 Mini | 14 x 14 mm | TBD | TBD | 14 mm Nano | Analog video | Selected |
| Video transmitter | SpeedyBee TX800 | 28 x 28 mm | 3.3 g | 7-26 V | Double Sided Tape OR TPU Mount 20 x 20 mm | Video/UART | Selected |
| ELRS receiver | ELRS Nano Receiver | 12 x 19 mm | 0.7 g | 5 V | Heat Shrink/ Double Sided Tape | CRSF/UART | Selected |
| Battery | Tattu R-Line 650mAh 4S 95C XT30 | TBD | 80-85 g | 14.8 V (4S Nominal) | Strap area | XT30 | Selected |
| Goggles | BETAFPV VR03 | TBD | TBD | Internal Battery/USB Charging | Strap area | 5.8 GHz Analog RF | Selected |
| Controller | RadioMaster T8L | TBD | TBD | TBD | Strap area | ELRS 2.4 GHz | Selected |
| Smoke Stopper | VIFLY Smoke Stopper | TBD | TBD | TBD | Strap area | XT30 / XT60 | Selected |
| Battery Charger | ToolkitRC C6 50W AC charger | TBD | TBD | TBD | Strap area | XT60 + Balance Port | Selected |
| VTX Antenna | RUSHFPV Cherry2 Antenna II RHCP | TBD | TBD | TBD | Strap area | U.FL → 5.8 GHz RF | Selected |
| Battery Connector | XT30 Pigtail 16 AWG Silicone Wire | TBD | TBD | TBD | Strap area | Power connector | Selected |
| Battery Strap | 15 × 200 mm Kevlar Battery Strap | TBD | TBD | TBD | Strap area | Mechanical Mount | Selected |
| Charging Adapter | XT60 Female → XT30 Male | TBD | TBD | TBD | Strap area | XT60 ↔ XT30 | Selected |
| Heat Shrink Tubing | Amazon | TBD | TBD | TBD | Strap area | Insulation | Selected |
| Capacitor | 470 µF Low ESR 25V | TBD | TBD | TBD | Strap area | Power connector | Selected |

