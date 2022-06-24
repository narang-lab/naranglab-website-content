---
title: "Quantum Information Science"
date: 2022-06-23
lastmod: 2022-06-23
draft: false
description: "Quantum Information Science"
slug: "quantum-information-science"
tags: []
showDateUpdated: true
---

![Quantum Information Science Banner](img/graphics_quantum-information-science_banner.png)

Our work in the quantum information subfield follows the integrated approach to quantum science embodied in the NarangLab. At the hardware level we work on many of the most promising quantum computing technologies - from the well established super-conducting platforms to photonic architectures with their promise of faster, potentially room-temperature devices - in collaboration with partners across industry and academia. Higher up the quantum technology stack, we work on quantum firmware-level circuit optimization and compilation tasks, while at the software level our work on classical preprocessing enables fruitful utilization of otherwise limited near term Noisy Intermediate-Scale Quantum hardware.

Prof. Narang’s newly developed class (ES 170, Quantum Engineering) at Harvard covers many of these topics in an immediate and practical fashion, and uses IBM's open-source quantum platforms to run NISQ algorithms and simulate molecules and materials. Course materials are readily available at request.

### Quantum building blocks and hardware

Optical quantum hardware promises much higher clock-rates compared to more mature platforms, as well as the potential to work at non-cryogenic temperatures. However, it also faces challenges due to the difficulty to create nonlinear interactions between photonic qubits. The group is exploring multiple lines of attack to these challenges, including the design of novel quantum defects, exotic vacancies in diamond lattices, and strongly nonlinear optical materials. At the same time, we are exploring quantum control schemes and corresponding bosonic error correcting codes that simplify the material requirements for such devices.

### Quantum compilation and circuit optimization

In the era of noisy-intermediate-scale quantum computers, we expect to see quantum devices with increasing numbers of qubits emerge. However, the connectivity between qubits will remain restricted, necessitating careful allocation of quantum registers to avoid costly operations, moving qubits between sparsely connected regions of the quantum chip. In the NarangLab we are developing compilation and circuit-optimization classical algorithms to optimize this allocation task, enabling the use of the hardware for otherwise prohibitive tasks. 

### Algorithms for small quantum devices

QAOA, VQE and other variational quantum-classical quantum algorithms have gained a great deal of attention as some of the most promising algorithms able to be run on near-term noisy quantum devices. However, improperly chosen initialization parameters for these algorithms can severely hamper their performance. By employing both classical and quantum optimization techniques for the pre- and post-processing steps, we develop methods to significantly improve the performance of these hybrid algorithms.

--- 
