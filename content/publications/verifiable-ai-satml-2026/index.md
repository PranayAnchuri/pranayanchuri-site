---
title: 'Towards Verifiable AI with Lightweight Cryptographic Proofs of Inference'

authors:
  - me
  - Matteo Campanelli
  - Paul Cesaretti
  - Rosario Gennaro
  - Tushar M. Jois
  - Hasan S. Kayman
  - Tugce Ozdemir

date: '2026-03-19T00:00:00Z'
publishDate: '2026-03-19T00:00:00Z'

publication_types: ['paper-conference']

publication: In *IEEE Conference on Secure and Trustworthy Machine Learning (SaTML) 2026*
publication_short: In *SaTML 2026*

abstract: >
  We address the challenge of verifying AI inference for cloud-deployed models. Rather
  than employing full cryptographic proofs — which impose prohibitive computational
  overhead — we present a verification framework and protocol that replaces full
  cryptographic proofs with a lightweight, sampling-based approach. The method uses
  Merkle-tree vector commitments to record execution traces, selectively opening entries
  along randomly sampled paths. Evaluated on ResNet-18 and Llama-2-7B, the approach
  reduces proving times from the order of minutes to the order of milliseconds.

summary: >
  A sampling-based verification framework for AI inference that replaces full
  cryptographic proofs with Merkle-tree commitments, reducing proving times from
  minutes to milliseconds on models including ResNet-18 and Llama-2-7B.

tags:
  - Verifiable AI
  - Cryptographic proofs
  - Machine learning
  - Zero-knowledge

featured: true

hugoblox:
  ids:
    arxiv: 2603.19025

links:
  - type: preprint
    provider: arxiv
    id: 2603.19025

projects: []
slides: ""
---
