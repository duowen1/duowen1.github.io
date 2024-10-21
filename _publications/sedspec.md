---
title: "SEDSpec: Securing Emulated Devices by Enforcing Execution Specification"
collection: publications
permalink: /publication/sedspec
excerpt: 'This paper is about protecting the emulated Devices'
date: 2024-06-23
venue: 'DSN'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10646946'
citation: 'Y. Chen et al., "SEDSpec: Securing Emulated Devices by Enforcing Execution Specification," 2024 54th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), Brisbane, Australia, 2024, pp. 522-534, doi: 10.1109/DSN58291.2024.00056. keywords: {Performance evaluation;Runtime;Automation;Instruments;Emulation;Prototypes;Object recognition;device emulation;anomaly detection;execution specification;program analysis}'
---

Device emulation is a vital aspect of virtualization, yet remains vulnerable to security threats. Prior research has focused on monitoring I/O data flow or identifying internal device anomalies but often falls short in precision and automation. In this paper, we propose a novel method that leverages the normal operations of an emulated device to formulate an execution specification. The specification acts as a criterion to evaluate the device's behavior and state transitions. We implement SEDSpec, a prototype system that automatically generates the execution specification for an emulated device and devises three check strategies for identifying any deviations from this specification, thereby ensuring normal operations and enhancing the security of the emulated device. We evaluate SEDSpec with five different execution specifications. The results show that SEDSpec can detect anomalies caused by vulnerability exploitation while maintaining the devices' regular functioning with minimal performance overhead.