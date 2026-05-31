# Event-Triggered Decentralized Swarm Coordination

[![IEEE](https://img.shields.io/badge/Publication-IEEE-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

## Overview

This repository accompanies the IEEE-published research work:

**"AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance"**

The proposed framework combines:

- Event-Triggered Control
- Particle Swarm Optimization (PSO)
- Distributed Model Predictive Control (DMPC)
- Vehicle-to-Vehicle (V2V) Communication

to achieve efficient decentralized coordination of autonomous vehicle swarms while significantly reducing computational and communication overhead.

---

## Key Contributions

- Event-triggered optimization mechanism
- Decentralized multi-vehicle coordination
- Reduced computational complexity
- Lower communication load
- Improved traffic safety
- Collision-free operation in simulation

---

## Experimental Results

| Metric | Baseline | Event-Triggered PSO-DMPC |
|----------|----------|----------|
| Active Optimization Calls | 100% | 7.5% |
| Computational Cost | 100% | 16% |
| Mean Time-To-Collision (MTTC) | 20.2 s | 38.6 s |
| MTTC Improvement | — | +90.5% |
| Collision Events | Multiple | 0 |

---

## Simulation Environment

- SUMO Traffic Simulator
- Python
- Particle Swarm Optimization (PSO)
- Distributed Model Predictive Control (DMPC)
- DSRC / IEEE 802.11p Communication Model

---

## Repository Structure

```text
Event-Triggered-Decentralized-Swarm-Coordination/
│
├── README.md
├── LICENSE
├── CITATION.cff
│
├── docs/
│   ├── formation_spacing_stability.png
│   ├── formation_consistency.png
│   ├── safety_margin.png
│   ├── communication_efficiency.png
│   └── pso_convergence.png
│
└── paper/
    └── publication_information.md
```

---

## Selected Figures

### Formation Spacing Stability

![Formation Stability](docs/formation_spacing_stability.png)

### Safety Margin Improvement

![Safety Margin](docs/safety_margin.png)

### Communication Efficiency

![Communication Efficiency](docs/communication_efficiency.png)

### PSO Convergence

![PSO Convergence](docs/pso_convergence.png)

---

## Publication

IEEE Conference Publication (2026)

**AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance**

Authors:

- SreeDharshan G J
- Surya Narayanan
- M aravindan

---

## Citation

Please use the repository citation provided in:

```text
CITATION.cff
```

---

## License

This repository is released under the MIT License.

The repository is intended for academic visibility and reproducibility of published research. The complete implementation and proprietary research assets are not included.
