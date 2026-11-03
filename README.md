# HRME (Harness Resistor Matrix Encoder)



A multi-channel switching and encoding module based on MOSFET switches and VOM1271 optodrivers, designed in **KiCad**.



## 📌 Project Overview

The board features 9 independent load switching channels. Each channel utilizes a **VOM1271** photovoltaic optocoupler driver and an **IRLML6344** power MOSFET operating with precision resistor network/load circuits.



## 🛠 Specifications

* **Channels:** 9 independent channels[span_0](start_span)[span_0](end_span)

* **Power Supply:** +24V[span_1](start_span)[span_1](end_span)

* **Logic Control Voltage:** 5V[span_2](start_span)[span_2](end_span)

* **Key Components:**

&#x20; * Optodrivers: `VOM1271` (SOP-4)[span_3](start_span)[span_3](end_span)

&#x20; * Power MOSFETs: `IRLML6344` (SOT-23)[span_4](start_span)[span_4](end_span)

&#x20; * Resistors: Individual channel values ranging from 8.2 Ω to 2.2 kΩ[span_5](start_span)[span_5](end_span)

&#x20; * Connectors: Terminal blocks (`TZ0621038000G` \& `TZ0221018000G`)[span_6](start_span)[span_6](end_span)



## 📂 Repository Structure

* `HRME_V1.kicad_sch` - Schematic design file[span_7](start_span)[span_7](end_span)

* `HRME_V1.kicad_pcb` - PCB layout file[span_8](start_span)[span_8](end_span)[span_9](start_span)[span_9](end_span)

* `Libraries/` - Custom component symbols and footprint libraries

* `README.md` - Project documentation



## 🚀 How to Open

1. Install **KiCad** (v8.0 / v9.0+ recommended).

2. Clone or download this repository.

3. Open `HRME_V1.kicad_pro` using KiCad.

