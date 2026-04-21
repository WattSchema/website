---
title: "6. Multiple Representations, One Conceptual Model"
weight: 6
description: "How the ontology is kept conceptually aligned across RDF, Fabric IQ, and OPC UA."
---

WattSchema is delivered through multiple technical representations to support adoption across Information Technology (IT), Operational Technology (OT), and analytics domains. While these technologies differ in syntax and tooling, they are intentionally aligned at the conceptual level.

WattSchema is like a superhero story told both as a comic book and a movie. The medium is different, but the characters, relationships, and story beats are the same. Someone familiar with one version can easily follow the other.

## 6.1 RDF Ontology

The canonical representation of WattSchema is an RDF-based ontology expressed in Turtle (`.ttl`) format. This form supports:

- Semantic reasoning and inference
- Formal validation
- Linked data integration with other ontologies


It serves as the reference model from which other representations are derived.

## 6.2 WattSchema and Microsoft Fabric IQ

**Microsoft Fabric** has recently released [Fabric IQ](https://blog.fabric.microsoft.com/en-us/blog/introducing-fabric-iq-the-semantic-foundation-for-enterprise-ai) as a semantic foundation for enterprise AI, enabling consistent meaning across data assets, analytics, and AI agents.

WattSchema aligns naturally with this approach. The Fabric IQ representation of WattSchema:

- Reuses the same core concepts as the RDF ontology
- Adapts them to Fabric’s analytics and AI workflows
- Enables AI systems to reason about infrastructure context, not just raw data

By mapping WattSchema concepts into Fabric IQ, organizations can integrate data center infrastructure semantics directly into enterprise analytics and agentic AI systems, without requiring those systems to understand RDF or semantic web tooling.

The result is **semantic continuity**: the same conceptual model supports both operational infrastructure modeling and enterprise-scale AI.


## 6.3 WattSchema as an OPC UA Companion Specification

To support industrial automation and control systems, WattSchema is also expressed as an **OPC UA Companion Specification**, aligned with the practices of the OPC Foundation.

The OPC UA representation:

- Uses OPC UA’s object, variable, and type system
- Is designed for real-time, operational environments
- Integrates naturally with  programmable logic controllers (PLCs), supervisory control and data acquisition (SCADA), and control platforms

While the technical encoding differs from RDF or Fabric IQ, the **conceptual model is the same**. Equipment types, relationships, and semantics correspond directly, enabling consistent interpretation across IT and OT boundaries.

This alignment reduces translation friction between analytics platforms and control systems, supporting closed-loop optimization and automation scenarios.
