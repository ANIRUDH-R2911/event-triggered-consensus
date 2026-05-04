# Event-Triggered-Consensus
# Communication-Efficient Event-Triggered Consensus in Multi-Agent Systems

## Overview

This project investigates communication-efficient consensus protocols in multi-agent systems using event-triggered control mechanisms. A simulation framework is developed to compare continuous consensus with event-triggered strategies.

## Key Contributions

* Implemented continuous and event-triggered consensus algorithms
* Evaluated static, decaying, and neighbor-relative triggering schemes
* Achieved up to **99% reduction in communication events**
* Analyzed trade-off between communication cost and convergence speed
* Verified absence of Zeno behavior

## Methods

* Continuous consensus (baseline)
* Static threshold event-triggered consensus
* Decaying threshold triggering
* Neighbor-relative triggering

## Results

* All methods converge to the same consensus value
* Significant communication reduction (up to 99%)
* Clear trade-off between convergence and communication

## Technologies Used

* Python
* NumPy
* Matplotlib
* NetworkX

## How to Run

```bash
pip install -r requirements.txt
python src/main.py
```

## Future Work

* Extend to nonlinear dynamics
* Real-world robotic implementation
* Learning-based triggering strategies

## Course   
- **Purdue University** – AAE 59000: Multi-agent Autonomy and Control 
