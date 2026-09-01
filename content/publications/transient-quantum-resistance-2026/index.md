---
title: 'Transient Quantum Resistance, with Application to Ethereum Consensus'

authors:
  - me
  - Matteo Campanelli
  - Rosario Gennaro

date: '2026-08-11T00:00:00Z'
publishDate: '2026-08-11T00:00:00Z'

publication_types: ['article']

publication: '*IACR ePrint 2026/1660*'
publication_short: '*ePrint 2026/1660*'

abstract: >
  We introduce transient quantum resistance, an approach enabling pre-quantum cryptographic
  primitives to remain secure beyond the quantum computing era in scenarios requiring only
  temporary forgery prevention. The method binds temporary keys to permanent post-quantum
  identities within defined timeframes. Applied to Ethereum's consensus layer, we propose
  preserving BLS signatures with aggregation capabilities while maintaining a single ~96-byte
  BLS signature — about three orders of magnitude smaller than alternative quantum-resistant
  methods. Security relies on the hardness of a modified Diffie-Hellman problem for the
  duration of an Ethereum epoch.

summary: >
  Transient quantum resistance lets pre-quantum primitives like BLS remain secure post-quantum
  for bounded time windows, preserving Ethereum consensus's compact 96-byte signatures while
  binding keys to post-quantum identities.

tags:
  - Ethereum
  - Post-quantum cryptography
  - BLS signatures
  - Consensus

featured: true

links:
  - name: ePrint
    url: https://eprint.iacr.org/2026/1660

projects: []
slides: ""
---
