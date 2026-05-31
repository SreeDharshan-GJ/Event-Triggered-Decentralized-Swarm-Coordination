# 🚗 AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance

![IEEE](https://img.shields.io/badge/Publication-IEEE%20RAEEUCCI%202026-blue)
![Best Paper](https://img.shields.io/badge/Award-Best%20Paper-gold)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)
![SUMO](https://img.shields.io/badge/Simulation-SUMO-orange)
![Multi-Agent](https://img.shields.io/badge/AI-Multi--Agent%20Systems-green)

---

## 📌 Overview

This repository showcases the research work:

### **AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance**

An IEEE-published autonomous vehicle coordination framework that combines:

* Event-Triggered Control
* Particle Swarm Optimization (PSO)
* Distributed Model Predictive Control (DMPC)
* Vehicle-to-Vehicle (V2V) Communication
* Safety-Constrained Multi-Agent Coordination

Unlike conventional approaches that perform optimization continuously, the proposed framework activates intelligent coordination only during safety-critical situations, drastically reducing computational overhead while maintaining collision-free operation.

---

## 🏆 Highlights

✅ IEEE Conference Publication

✅ IEEE RAEEUCCI 2026 Best Paper Award

✅ Zero collisions across 10,000 simulation timesteps

✅ 92.5% reduction in active optimization

✅ 84% reduction in computational cost

✅ 90.5% improvement in Mean Time-To-Collision (MTTC)

✅ 81.9% reduction in speed variance

✅ Scalability validated up to 26 autonomous vehicles

---

## 🧠 Research Motivation

Large-scale autonomous vehicle swarms require:

* Continuous communication
* Real-time trajectory planning
* Collision avoidance
* Computationally efficient coordination

Most existing PSO-DMPC approaches execute optimization at every timestep, resulting in:

* High CPU usage
* Increased communication traffic
* Poor embedded deployment feasibility

This work introduces an event-triggered architecture where optimization occurs only when safety constraints are violated.

---

## 🏗️ System Architecture

### Vehicle Layer

Each autonomous vehicle independently monitors:

* Position
* Velocity
* Heading
* Inter-vehicle spacing

### Event Detection Layer

A coordination event is triggered when:

```math
d_{ij} < d_{safe}
```

where:

* (d_{ij}) = inter-vehicle distance
* (d_{safe}) = dynamic safety threshold

### Optimization Layer

The framework integrates:

#### Particle Swarm Optimization (PSO)

Used to:

* Generate warm-start solutions
* Accelerate optimization convergence
* Reduce search complexity

#### Distributed Model Predictive Control (DMPC)

Used to:

* Generate collision-free trajectories
* Maintain formation stability
* Enforce safety constraints

### Communication Layer

Vehicles communicate using:

* IEEE 802.11p DSRC
* 5.9 GHz V2V communication
* 300 m communication range

Communication occurs only during safety-critical events.

---

## 🔬 Core Contributions

### 1. Event-Triggered PSO-DMPC Framework

First integration of:

* Event-triggered coordination
* PSO warm-start optimization
* Distributed MPC control

for decentralized autonomous vehicle swarm coordination.

---

### 2. Computational Efficiency

Compared with continuous optimization:

| Metric                 | Improvement |
| ---------------------- | ----------- |
| Active Optimization    | ↓ 92.5%     |
| Computational Cost     | ↓ 84%       |
| Communication Overhead | ↓ 92.5%     |

---

### 3. Safety Enhancement

| Metric           | Baseline | Proposed |
| ---------------- | -------- | -------- |
| MTTC             | 20.25 s  | 38.57 s  |
| Improvement      | —        | +90.5%   |
| Near-Miss Events | 3083     | 2748     |
| Collision Events | Multiple | 0        |

---

### 4. Formation Stability

The proposed method improves:

* Inter-vehicle spacing consistency
* Formation cohesion
* Speed stability

while reducing speed variance by:

```text
81.9%
```

compared to baseline traffic behavior.

---

## 📊 Experimental Results

### Safety Performance

| Metric             | Baseline | Continuous PSO | Event-Triggered PSO |
| ------------------ | -------- | -------------- | ------------------- |
| MTTC (s)           | 20.25    | 37.00          | 38.57               |
| Speed Variance     | 17.58    | 3.20           | 3.19                |
| CPU Cost (ms/step) | 0.12     | 2.80           | 0.45                |
| Collisions         | Present  | 0              | 0                   |

---

### Communication Efficiency

| Metric             | Continuous PSO | Event-Triggered PSO |
| ------------------ | -------------- | ------------------- |
| Message Rate       | 563.3 msg/s    | 495.8 msg/s         |
| AI Activation Rate | 100%           | 7.4%                |
| Transmission Load  | 100%           | 88%                 |

---

### Density Robustness

The framework was evaluated under:

* 5 vehicles
* 10 vehicles
* 20 vehicles
* 26 vehicles

Results demonstrate:

* Graceful degradation
* Stable coordination
* Zero collisions

across all density configurations.

---

## 📂 Repository Structure

```text
Event-Triggered-Decentralized-Swarm-Coordination/

├── docs/
│   ├── system_architecture.png
│   ├── pso_convergence.png
│   ├── formation_spacing_stability.png
│   ├── safety_margin.png
│   ├── communication_efficiency.png
│
├── paper/
│   └── publication_information.md
│
├── LICENSE
├── CITATION.cff
└── README.md
```

---

## 📈 Key Figures

Add the following figures from your publication:

### System Architecture

```text
docs/system_architecture.png
```

### PSO Convergence

```text
docs/pso_convergence.png
```

### Formation Stability

```text
docs/formation_spacing_stability.png
```

### Safety Margin Improvement

```text
docs/safety_margin.png
```

### Communication Efficiency

```text
docs/communication_efficiency.png
```

---

## 📖 Publication

**IEEE RAEEUCCI 2026**

**AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance**

### Authors

* Aravindan M
* Surya Narayanan S
* Sree Dharshan G J
* Akankshya Sethi

---

## 📚 Citation

```bibtex
@inproceedings{sreedharshan2026eventtriggered,
  title={AI-Based Event-Triggered Decentralized Swarm Coordination for Multi-Vehicle Collision Avoidance},
  author={Aravindan, M and Narayanan, Surya and Sree Dharshan, G J and Sethi, Akankshya},
  booktitle={IEEE RAEEUCCI},
  year={2026}
}
```

---

## 👨‍💻 Author

### Sree Dharshan G J

AI Researcher | Multi-Agent Systems | Autonomous Systems

Research Areas:

* Multi-Agent Systems
* Reinforcement Learning
* Autonomous Vehicles
* Distributed Optimization
* Event-Triggered Control
* Agentic AI

---

## ⚠️ Repository Notice

This repository is intended for academic visibility and dissemination of published research.

The complete implementation, simulation source code, optimization routines, and experimental assets are not included due to publication and intellectual property considerations.

Only publication-related materials, figures, and project documentation are provided.

---

## 📜 License

MIT License
