# Quality-preserving-Model-for-Electronics-Production-Quality-Tests-Reduction
## About

This repository contains the full implementation of an AI-driven adaptive test selection framework for electronics manufacturing quality assurance.

In high-volume electronics production, every board must pass a multi-step test sequence before shipment. Most test steps are redundant — they detect no defects. This work proposes a framework that:

1. **Identifies** the minimum-cost subset of test steps that preserves complete defect coverage
2. **Characterises** the full cost-risk trade-off using Pareto analysis
3. **Adapts** in real time using a Thompson Sampling Multi-Armed Bandit agent when production conditions change

The framework is validated on two industrial PCBA datasets — Functional Circuit Test (FCT) with 172 steps across 13,699 board runs, and End-of-Line (EOL) test with 55 steps across 15,218 board runs — including a validation period with genuine concept drift.
