---
title: "3. Scope and Coverage: Modeling the Full Energy Ecosystem"
weight: 3
description: "The infrastructure, resources, and operational domains WattSchema is designed to represent."
---

WattSchema is designed to model the systems that directly determine how a data center consumes, produces, and manages energy. While its foundation lies in traditional facility infrastructure, its scope reflects the rapidly changing energy landscape in which data centers now operate.

## 3.1 Beyond the Utility Feed: On-Site and Behind-the-Meter Resources

Historically, data center power models focused on utility service entrances, switchgear, uninterruptible power supply (UPS) systems, and downstream distribution. Today, that boundary is expanding.

New data center developments increasingly incorporate:

- On-site generation (diesel, natural gas, fuel cells, and emerging technologies)
- Solar photovoltaic (PV) and other distributed energy resources
- Battery energy storage systems (BESS)
- Microgrid configurations capable of islanded or grid-interactive operation
- Demand response and load-shedding capabilities

These systems are no longer peripheral. In many regions, grid interconnection delays and transmission constraints have made **behind-the-meter generation and storage key enablers of site development**. At the same time, regulators and utilities are asking large data center operators to reduce grid impact, participate in demand response programs, and demonstrate more flexible load behavior.

WattSchema explicitly models these resources and their relationships to core facility loads, allowing digital twins to represent not just how power is distributed, but how it is sourced, shifted, and managed over time.

This richer representation supports advanced forms of **scenario analysis and capacity planning** and the ability to evaluate “what-if” operational and infrastructure configurations, such as:

- How additional on-site generation changes available IT load capacity
- How storage duration affects ride-through and peak-shaving strategies
- How different redundancy strategies impact both reliability and grid dependency

By encoding these relationships semantically, WattSchema allows planning, optimization, and AI-driven systems to reason over infrastructure configurations in a structured way rather than relying solely on external spreadsheets or bespoke simulation models.
Several contributors to WattSchema bring deep expertise in photovoltaic systems, distributed generation, and backup power architectures, helping ensure that these behind-the-meter capabilities are modeled with the same rigor as traditional electrical distribution.


## 3.2 Core Infrastructure Domains

In addition to distributed energy resources, WattSchema covers the primary domains required to describe data center power and cooling systems:

- Utility service and interconnection points
- Medium- and low-voltage electrical distribution
- UPS systems and power conditioning equipment
- Cooling plants, chilled water systems, and heat rejection
- Sensors, meters, and control points
- Operational groupings such as redundancy blocks and capacity zones

Together, these domains form the semantic backbone of a data center energy digital twin.
