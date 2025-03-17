---
title: "ConMonitor: Lightweight Container Protection with Virtualization and VM Functions"
collection: publications
permalink: /publication/conmonitor
excerpt: 'This paper is about container isolation.'
date: 2024-11-20
venue: 'SoCC'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3698038.3698520'
citation: 'Shaowen Xu, Qihang Zhou, Zhicong Zhang, Xiaoqi Jia, Donglin Liu, Heqing Huang, Haichao Du, and Zhenyu Song. 2024. ConMonitor: Lightweight Container Protection with Virtualization and VM Functions. In Proceedings of the 2024 ACM Symposium on Cloud Computing (SoCC 24). Association for Computing Machinery, New York, NY, USA, 755–773. https://doi.org/10.1145/3698038.3698520'
---

Containers are widely used in multi-tenant cloud computing for their ease of deployment, minimal overhead, and fast start-up. However, the intrinsic shared kernel model of containers poses significant security threats, risking confidentiality and integrity from co-located containers or compromised OS. Researchers have proposed various methods to protect containers from untrusted OS, but few consider both the universality and efficiency. In this paper, we present ConMonitor, a lightweight and efficient container protection architecture. ConMonitor protects the security of container application data by introducing a compact virtualization software, called ConVisor, as a trusted computing base. ConVisor enforces isolation of the physical memory between containers and the kernel, and monitors the sensitive operations performed by the OS. To ensure the security of ConMonitor, we implement a Container Guardian to serve as an intermediary for the kernel, managing sensitive operations. Moreover, we also leverage the VMFUNC feature to achieve fast context switching, thereby mitigating the performance penalty associated with frequent context switching. We have implemented ConMonitor on Intel CPU with Virtualization Technology, and the evaluation results show that ConMonitor can protect the security of container applications with a negligible performance overhead.

