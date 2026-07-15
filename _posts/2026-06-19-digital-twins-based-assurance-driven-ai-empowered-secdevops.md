---
title: "Digital Twins-based Assurance-driven AI-empowered SecDevOps"
date: 2026-06-19
permalink: /posts/2026/06/digital-twins-based-assurance-driven-ai-empowered-secdevops/
tags:
  - secassured
  - secdevops
  - digital twins
  - ai engineering
  - cybersecurity
---

By Phu Nguyen and Adela Nedisan Videsjorden (SINTEF).

Digital systems are now assembled from software, hardware, cloud services, third-party dependencies, and constantly changing operational environments. That makes security assurance harder to treat as a one-time activity. It has to evolve together with the system itself.

This post presents the SECASSURED vision: Digital Twins-based Assurance-driven AI-empowered SecDevOps for continuously securing digital infrastructures.

![SECASSURED overview showing assurance-driven AI-empowered SecDevOps with SecDevTwin and SecOpsTwin](/images/posts/SECASSURED_overview-002.png)

*Figure: SECASSURED overview of the closed-loop flow between development-time and operations-time security assurance.*

What the vision adds
======

Security assurance as the driving force
------
Instead of treating security as a late-stage checkpoint, the vision places assurance at the center of the development and operations lifecycle. The goal is to support trustworthy, certifiable systems across the software supply chain.

Two complementary security twins
------
The approach combines two digital twins that work together:

- `SecDevTwin`: a development-oriented security twin that models architecture, software components, dependencies, infrastructure, and assurance artefacts. It supports shift-left assurance and helps evaluate security properties before deployment.
- `SecOpsTwin`: an operational security twin that represents runtime state using telemetry, events, alerts, and monitoring data. It enables continuous runtime assurance, including anomaly detection, forecasting, simulation, and automated response.

Feedback in both directions
------
The twins exchange evidence continuously so that development and operations reinforce each other:

- Development-to-Operations flow: architectural context, assurance cases, compliance evidence, and development-time assessments support better runtime monitoring and response.
- Operations-to-Development flow: runtime anomalies, incidents, threat intelligence, and infrastructure changes feed back into future development, simulation, and assurance work.

A closed-loop security lifecycle
------
Together, the twins create a knowledge-driven lifecycle where security assurance can be refined using both simulated and real operational evidence. That makes the system more adaptive, more observable, and easier to improve over time.

Source
======

Original article: [Digital Twins-based Assurance-driven AI-empowered SecDevOps](https://secassured.eu/insights/digital-twins-based-assurance-driven-ai-empowered-secdevops/)
