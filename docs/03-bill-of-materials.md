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

## Component Selection

| Component | Selected Part | Qty | Vendor | Status | Cost |
|-----------|---------------|:---:|--------|:------:|-----:|
| Flight Controller (AIO) | SpeedyBee F405 AIO 35A Bluejay (No Case) | 1 | SpeedyBee | ✅ Selected | TBD |
| Motors | SpeedyBee 1404 V2 4600KV | 4 | SpeedyBee | ✅ Selected | TBD |
| Propellers | Gemfan 3016 | 4 (Buy 20+) | Gemfan | ✅ Selected | TBD |
| FPV Camera | RunCam Nano 4 Mini | 1 | RunCam | ✅ Selected | TBD |
| Video Transmitter | SpeedyBee TX800 | 1 | SpeedyBee | ✅ Selected | TBD |
| ELRS Receiver | BETAFPV ELRS Nano Receiver (2.4 GHz) | 1 | BETAFPV | ✅ Selected | TBD |
| Battery | Tattu R-Line 650mAh 4S 95C XT30 | 2 | Tattu | ✅ Selected | TBD |
| FPV Goggles | BETAFPV VR03 | 1 | BETAFPV | ✅ Selected | TBD |
| Radio Controller | RadioMaster T8L ELRS | 1 | RadioMaster | ✅ Selected | TBD |
| Smoke Stopper | VIFLY Smoke Stopper | 1 | VIFLY | ✅ Selected | TBD |
| Battery Charger | ToolkitRC C6 50W AC | 1 | ToolkitRC | ✅ Selected | TBD |
| VTX Antenna | RushFPV Cherry II RHCP (U.FL) | 1 | RushFPV | ✅ Selected | TBD |
| XT30 Pigtail | 16 AWG Silicone Wire | 1 | Generic | ✅ Selected | TBD |
| Battery Strap | 15 × 200 mm Kevlar Strap | 2 | Generic | ✅ Selected | TBD |
| Charging Adapter | XT60 Female → XT30 Male | 1 | Generic | ✅ Selected | TBD |
| Heat Shrink | Assorted Sizes | 1 Kit | Generic | ✅ Selected | TBD |
| Capacitor | 470 µF Low ESR 25V | 1 | Generic | ✅ Selected | TBD |

## Mechanical & Electrical Specifications

| Component | Dimensions | Weight | Voltage | Mounting | Interface |
|-----------|-----------:|--------:|---------:|----------|-----------|
| SpeedyBee F405 AIO | 33 × 33 mm | 8.9 g | TBD | 25.5 × 25.5 mm | USB, UART, Motor Outputs |
| SpeedyBee 1404 V2 | 14 × 14 mm | TBD | 4600 KV | 9 × 9 mm M2 | 3-Phase Motor Wires |
| Gemfan 3016 | 3 in | TBD | N/A | 1.5 mm Shaft | N/A |
| RunCam Nano 4 Mini | 14 × 14 mm | TBD | TBD | 14 mm Nano | Analog Video |
| SpeedyBee TX800 | 28 × 28 mm | 3.3 g | 7–26 V | TPU Mount / Tape | Video + UART |
| ELRS Nano Receiver | 12 × 19 mm | 0.7 g | 5 V | Heat Shrink / Tape | CRSF + UART |
| Tattu R-Line Battery | TBD | 80–85 g | 14.8 V (4S) | Battery Strap | XT30 |
| BETAFPV VR03 | TBD | TBD | Internal Battery | Head Strap | 5.8 GHz Analog |
| RadioMaster T8L | TBD | TBD | TBD | Handheld | ELRS 2.4 GHz |
| VIFLY Smoke Stopper | TBD | TBD | TBD | Inline | XT30 / XT60 |
| ToolkitRC C6 | TBD | TBD | AC Input | Bench | XT60 + Balance Port |
| Rush Cherry II | TBD | TBD | Passive | U.FL | 5.8 GHz RF |
| XT30 Pigtail | TBD | TBD | TBD | Soldered | XT30 |
| Battery Strap | 15 × 200 mm | TBD | N/A | Mechanical | Strap |
| Charging Adapter | TBD | TBD | N/A | Inline | XT60 ↔ XT30 |
| Heat Shrink | Various | TBD | N/A | Heat Applied | Insulation |
| Capacitor | TBD | TBD | 25 V | Soldered | Power Filter |
