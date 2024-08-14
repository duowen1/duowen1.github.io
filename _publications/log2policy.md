---
title: "Log2Policy: An Approach to Generate Fine-Grained Access Control Rules for Microservices from Scratch"
collection: publications
permalink: /publication/log2policy
excerpt: 'This paper is about generating access control rules.'
date: 2023-12-04
venue: 'ACSAC'
slidesurl: 'https://www.acsac.org/2023/files/web/slides/xu-67-log2policy.pdf'
paperurl: 'https://dl.acm.org/doi/10.1145/3627106.3627137'
citation: 'Shaowen Xu, Qihang Zhou, Heqing Huang, Xiaoqi Jia, Haichao Du, Yang Chen, and Yamin Xie. 2023. Log2Policy: An Approach to Generate Fine-Grained Access Control Rules for Microservices from Scratch. In Proceedings of the 39th Annual Computer Security Applications Conference (ACSAC 23). Association for Computing Machinery, New York, NY, USA, 229¨C240. https://doi.org/10.1145/3627106.3627137'
---

Microservice application architecture is one of the most widely used service architectures in the industry. To prevent a compromised microservice from abusing other microservices, authorization policy is applied to regulate the access among them. However, configuring access control policy manually is challenging due to the complexity and dynamic nature of microservice applications. In this paper, we present Log2Policy, a novel approach to generate microservice authorization policy based on access logs. Our approach consists of three fundamental techniques: (1) a log-based topological graph generation mechanism that automatically infers the invocation logic among microservices, (2) a machine learning based attributes mining method that extracts the relevant attributes of requests, and (3) a policy upgrade mechanism based on traffic management that can significantly reduce the upgrade time. We have implemented a prototype of Log2Policy on mainstream microservice infrastructures and have evaluated it with several microservice applications. The results show that Log2Policy can generate fine-grained and effective access control rules and upgrade them with negligible overhead.