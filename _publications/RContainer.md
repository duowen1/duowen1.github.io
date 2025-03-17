---
title: "RContainer: A Secure Container Architecture through Extending ARM CCA Hardware Primitives"
collection: publications
permalink: /publication/rcontainer
excerpt: 'This paper is about protecting container applications'
date: 2025-02-28
venue: 'NDSS'
paperurl: 'https://www.ndss-symposium.org/wp-content/uploads/2025-328-paper.pdf'
---

Containers have become widely adopted in cloud platforms due to their efficient deployment and high resource utilization. However, their weak isolation has always posed a sig nificant security concern. In this paper, we propose RContainer, a novel secure container architecture that protects containers from untrusted operating systems and enforces strong isolation among containers by extending ARM Confidential Computing Architecture (CCA) hardware primitives. RContainer introduces a small, trusted mini-OS that runs alongside the deprivileged OS, responsible for monitoring the control flow between the operating system and containers. Additionally, RContainer uses shim-style isolation, creating an isolated physical address space called con shim for each container at the kernel layer through the Granule Protection Check mechanism. We have implemented RContainer on ARMv9-A Fixed Virtual Platform and ARMv8 hardware SoC for security analysis and performance evaluation. Experimental results demonstrate that RContainer can significantly enhance container security with a modest performance overhead and a minimal Trusted Computing Base (TCB).