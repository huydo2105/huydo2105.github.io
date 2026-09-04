---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a **PhD Candidate in Distributed Systems and Blockchain** at [Université Paris-Est Créteil (UPEC)](https://www.u-pec.fr), France, advised by [Dr. Sami Souihi](https://scholar.google.com/citations?user=Gk74iYQAAAAJ), [Dr. Thiago Abreu](https://scholar.google.com/citations?user=Y3B0d-cAAAAJ), and [Dr. Sara Tucci-Piergiovanni](https://scholar.google.com/citations?user=rY0LCEkAAAAJ). I am also a CIFRE fellow collaborating with [Ejara](https://ejara.io) and UPEC, funded by ANRT.

Prior to starting my PhD, I received my Computer Science Engineer degree from [Hanoi University of Science and Technology (HUST)](https://www.hust.edu.vn), Vietnam.

## Research Interests

My research sits at the intersection of **distributed systems, peer-to-peer networks, and blockchain technology**:

- **Offline & Resilient Payment Systems**: Developing decentralized, off-chain payment mechanisms over wireless mesh and opportunistic networks to enable peer-to-peer transactions in internet-constrained and rural environments.
- **Blockchain Scalability & Sharding**: Designing adaptive sharding mechanisms (leveraging Deep Reinforcement Learning) to optimize throughput and latency in next-generation networks (5G network slicing).
- **Opportunistic & Delay-Tolerant Networks**: Enhancing routing protocols (e.g., epidemic routing with reinforcement learning) and establishing node trust and reliability via blockchain integration.
- **BFT Consensus & Quorum Protocols**: Implementing resilient quorum-based consensus and finalization protocols for off-chain settlement and fault tolerance.
- **AI-Enhanced Networking**: Applying Federated Learning and Reinforcement Learning to optimize network throughput, node coordination, and resource allocation.

## Current Research: PhD Thesis

> **Thesis Title**: *An Opportunistic Mesh Network for P2P Cryptocurrency Transactions based on a Resilient Blockchain Infrastructure*

In many regions of the world, unstable or non-existent internet infrastructure prevents individuals from accessing modern digital financial tools. My thesis tackles this challenge by:
1. Enabling secure, decentralized, peer-to-peer offline transactions over Wireless Mesh Networks (evaluated using Mininet-WiFi).
2. Leveraging smart contract-driven authority nodes and collateral mechanisms for off-chain trust and dispute resolution.
3. Designing quorum-based weighted voting protocols for transaction validation and eventual settlement on a resilient blockchain layer.
4. Utilizing Federated Learning and Reinforcement Learning algorithms to dynamically optimize routing and network reliability.

## Selected Publications

{% for paper in site.data.papers limit:3 %}
{% include paper.html paper=paper %}
{% endfor %}

<p><a href="/publications/" class="btn btn--primary">View All Publications &rarr;</a></p>

## Recent Awards & Honors

- **CIFRE Grant (2024 – 2027)**: Awarded by ANRT, Ejara, and Université Paris-Est Créteil (UPEC).
- **Third Prize at Etherlink Summer Hackathon (2025)**: Organized by Etherlink, Trillitech, and Encode Club.
- **Second Prize at Tezos Hackathon (2022)**: Tezos Africa Hackathon.

<p><a href="/awards/" class="btn btn--inverse">View Awards & Fellowships &rarr;</a></p>
