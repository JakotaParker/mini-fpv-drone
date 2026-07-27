# 03 — Bill of Materials

**Version:** V1.0

**Status:** Frozen for Prototype V1

**Last Updated:** July 2026

Do not mark a component as selected until its dimensions, voltage, current rating, protocol, and mounting compatibility have been checked.

| Subsystem | Component | Candidate / Part Number | Qty | Selected? | Cost | Compatibility Notes |
|---|---|---:|---:|---|---:|---|
| Airframe | Custom Frame V1 | Onshape design | 1 | Prototype | TBD | Full print not validated |
| Propulsion | Brushless motor | TBD | 4 | Yes | TBD | Match prop, voltage, mounting pattern |
| Propulsion | 3-inch propeller set | TBD | 4 sets | Yes | TBD | Check shaft and frame clearance |
| Control | Flight controller / AIO | TBD | 1 | Yes | TBD | Check mounting, UARTs, ESC rating |
| Radio | ELRS receiver | TBD | 1 | Yes | TBD | Match transmitter frequency |
| FPV | FPV camera | TBD | 1 | Yes | TBD | Check voltage and physical dimensions |
| FPV | Video transmitter | TBD | 1 | Yes | TBD | Check voltage, output, mounting |
| FPV | VTX antenna | TBD | 1 | Yes | TBD | Match connector and frequency |
| Power | LiPo battery | TBD | 2+ | Yes | TBD | Match cell count and connector |
| Power | Battery connector | TBD | 1 | Yes | TBD | Match current demand |
| Hardware | Screws / standoffs | TBD | Set | Yes | TBD | Match frame and electronics |
| Safety | Smoke stopper | Existing or TBD | 1 | Yes | TBD | Required for first power-up |
| Safety | LiPo-safe charging/storage gear | TBD | 1 | Yes | TBD | Required for battery handling |

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
| Flight Controller (AIO) | SpeedyBee F405 AIO 35A Bluejay (No Case) | 1 | SpeedyBee | Selected | $57 |
| Motors | SpeedyBee 1404 V2 4600KV | 4 | SpeedyBee | Selected | $50 |
| Propellers | Gemfan 3016 | 4 sets (16 props) | Gemfan | Selected | $16 |
| FPV Camera | RunCam Nano 4 Mini | 1 | RunCam | Selected | $24 |
| Video Transmitter | SpeedyBee TX800 | 1 | SpeedyBee | Selected | $34 |
| ELRS Receiver | BETAFPV ELRS Nano Receiver (2.4 GHz) | 1 | BETAFPV | Selected | $10 |
| Battery | Tattu R-Line 650mAh 4S 95C XT30 | 2 | Tattu | Selected | $33 |
| FPV Goggles | BETAFPV VR03 | 1 | BETAFPV | Selected | $86 |
| Radio Controller | RadioMaster T8L ELRS | 1 | RadioMaster | Selected | $35 |
| Smoke Stopper | VIFLY Smoke Stopper | 1 | VIFLY | Selected | $13 |
| Battery Charger | ToolkitRC C6 50W AC | 1 | ToolkitRC | Selected | $30 |
| VTX Antenna | Included SpeedyBee MMCX Antenna | 1 | SpeedyBee | Included with TX800 | $0 |
| XT30 Pigtail | 16 AWG Silicone Wire | 5 | Generic | Selected | $10 |
| Battery Strap | 15 × 200 mm Kevlar Strap | 2 | Generic | Selected | $8 |
| Charging Adapter | XT60 Female → XT30 Male | 1 | Generic | Selected | $8 |
| Heat Shrink | XHF UL Listed 225 Pcs Length 3.45 | 1 Kit | XHF | Selected | $10 |
| Capacitor | 470 µF Low ESR 25V | 1 | Generic | Selected | $7 |
Total Extended Cost (Pre-Tax) : $ 431

## Mechanical & Electrical Specifications

| Component | Dimensions | Weight | Voltage | Mounting | Interface |
|-----------|-----------:|--------:|---------:|----------|-----------|
| SpeedyBee F405 AIO | 33 × 33 mm | 8.9 g | TBD | 25.5 × 25.5 mm | USB, UART, Motor Outputs |
| SpeedyBee 1404 V2 | 14 × 14 mm | TBD | 4600 KV | 9 × 9 mm M2 | 3-Phase Motor Wires |
| Gemfan 3016 | 3 in | TBD | N/A | 1.5 mm Shaft | N/A |
| RunCam Nano 4 Mini | 14 × 14 mm | TBD | TBD | 14 mm Nano | Analog Video |
| SpeedyBee TX800 | 28 × 28 mm | 3.3 g | 3.7-5 V | TPU Mount / Tape | Video + UART |
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

### Propulsion Verification

- Motor: SpeedyBee 1404 V2 4600KV
- Propeller: Gemfan 3016
- Battery: 4S LiPo
- Maximum thrust per motor: 431 g
- Maximum combined thrust: 1,724 g
- Target all-up weight: ≤250 g
- Estimated thrust-to-weight ratio at 250 g: 6.9:1
- ESC current verification: Pending
- Compatibility status: Verified for thrust
