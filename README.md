# Causal Octonion Control for MPPT (Intensional Formalism)

This repository contains the core mathematical implementation of the **Intensional Maxwellian Formalism** applied to distributed multi-phase power converters. 

Unlike standard PID or MPC controllers, this algorithm operates on an intensional logic framework where the identity of origin alters the value ($x \cdot x \neq x^2$). It utilizes a non-associative causal memory layer (Octonions) and an associator projection `[X, Y, Z] = (XY)Z - X(YZ)` to natively resolve magnetic saturation, thermal degradation, and distributed swarm synchronization via the shared DC bus without communication wires.

## 📄 Academic Publication (Prior Art)
The full theoretical framework, physical limits mapping, and hardware implementation details on the STM32G431 microcontroller are formally published and timestamped on HAL Science.

**Read the Whitepaper:** *[URL odkaz bude doplněn po schválení HAL administrátory]*

## ⚖️ Licensing & Commercial Use
This project operates under a Dual-Licensing model to protect the intensional architecture from undocumented corporate exploitation.

* **Academic & Non-Commercial Use:** This source code is licensed under the **GPLv3 License**. You are free to study, modify, and distribute it, provided any derivative work is also open-sourced under GPLv3.
* **Commercial Integration:** Implementing this causal control architecture (the octonion associator and swarm frequency shift keying) into proprietary, closed-source power electronics (e.g., commercial charge controllers, inverters) strictly requires a **Commercial License**. 

For commercial licensing inquiries, please contact the author directly.

