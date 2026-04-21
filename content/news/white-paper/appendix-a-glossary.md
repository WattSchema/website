---
title: "Appendix A: Glossary"
weight: 9
description: "Key terms used throughout the WattSchema white paper."
---

**ASHRAE Standard 223**: A standard defining machine-readable semantic models for physical systems using technologies like RDF, SHACL, and SPARQL. It provides a foundational graph-based semantic framework for interoperable, automated systems.

**Battery Energy Storage System (BESS)**: A system that stores electrical energy in batteries for use in backup power, load shifting, peak shaving, or grid-support functions.

**Behind-the-Meter Resources**: Energy resources located on the customer side of a utility meter, such as solar PV, BESS, and on site generators. These resources contribute to local generation, resiliency, and grid-interactive operations.

**Brick Schema**: An open schema for representing building equipment, sensors, actuators, and telemetry points. It defines relationships like `hasPoint` and `isPartOf` to support structured, interoperable building data.

**Chiller**: Cooling equipment that removes heat from the chilled-water loop serving data center cooling loads, operating under defined control logic and thermal constraints.

**Digital Twin**: A virtual representation of a physical system that uses real-time and historical data to model and reflect the system’s behavior, conditions, and performance.

**Distributed Energy Resources (DERs)**: Small-scale energy generation or storage technologies—such as solar PV, fuel cells, or batteries—located close to the load they serve.

**Fabric IQ (Microsoft Fabric IQ)**: Microsoft Fabric’s semantic layer designed to unify meaning across datasets, analytics, and AI workflows. WattSchema can map into Fabric IQ to support AI-driven infrastructure understanding.

**Firmware Revision**: The specific version of embedded software running on equipment, relevant for tracking configuration, compatibility, and operational behavior.
**Medium- and Low-Voltage Distribution**: Electrical distribution tiers within a data center. Medium voltage typically includes utility interconnection and major switchgear, while low voltage powers downstream equipment such as IT racks.

**Microgrid**: A localized electrical system capable of operating either connected to or independent from the main grid, often incorporating DERs, controls, and islanding capability.

**Ontology**: A structured system for defining concepts, relationships, and categories so that software systems can interpret and reason about information.
**OPC Unified Architecture (OPC UA)**: A communication standard used in industrial automation, enabling structured, secure, and interoperable information exchange between control systems. WattSchema provides an OPC UA Companion Specification version for OT integration.

**Power Meter**: A device that measures specific electrical quantities at defined points within a power topology, providing context-rich telemetry for operations and modeling.

**Redundancy Strategy**: An operational approach ensuring continuous service by duplicating critical components or paths (`e.g., N+1, 2N`). Essential for data center reliability and fault tolerance.

**Resource Description Framework (RDF)**: A graph-based semantic data model used to represent entities, relationships, and properties in a machine-readable format. WattSchema’s canonical form is an RDF ontology in Turtle (`.ttl`) format.

**Semantic Understanding**: The ability of systems to interpret the meaning, relationships, and contextual roles of entities—enabling correct reasoning, automation, and safe decision-making.

**SHACL (Shapes Constraint Language)**: A framework for validating RDF graphs to ensure semantic models meet defined completeness and correctness requirements (e.g., validating commissioning or vendor model exchanges).

**Single-Line Diagram**: A simplified electrical schematic showing components and connections in a power system. Traditionally used for design but often insufficient for semantic or machine-readable modeling.

**Solar Photovoltaic (PV)**: On-site renewable energy generation technology converting sunlight into electricity, increasingly common in data center energy ecosystems.

**Uninterruptible Power Supply (UPS)**: A system composed of converters, switches, and stored energy (e.g., batteries) designed to maintain continuous power to loads during utility interruptions.

**WattSchema**: An open-source ontology for modeling data center power and cooling systems. Built on ASHRAE 223 and aligned with standards such as Brick and RealEstateCore, it enables simulation, automation, reasoning, and AI-driven operations across IT and OT environments.

**Utility Interconnection**: The point at which a data center connects electrically to the external grid, including service entrances, transformers, and associated protection equipment.

**Validation (Model Validation)**:  Processes ensuring that a semantic model is complete, correct, and consistent with design requirements. Enabled in WattSchema through SHACL-based constraints.
