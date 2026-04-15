---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research sits at the intersection of blockchain protocols, verifiable computation,
        and machine learning. At Offchain Labs, I work on making decentralized systems more
        secure and efficient. Previously at Princeton CITP, I applied machine learning to
        questions in public policy and social science.

        I am always interested in collaborating — reach out via email or Twitter.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card
---
