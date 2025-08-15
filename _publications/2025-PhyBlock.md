---
title: "PhyBlock: A Progressive Benchmark for Physical Understanding and Planning via 3D Block Assembly"
collection: publications
category: conferences
permalink: /publication/2025-PhyBlock
excerpt: 'Embodied AI, Vision-Language Understanding, Vision Language Models, Benchmark'
date: 2025-06-10
venue: 'Under Review'
slidesurl: # 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2506.08708'
citation: '@article{ma2025phyblock,
  title={PhyBlock: A Progressive Benchmark for Physical Understanding and Planning via 3D Block Assembly},
  author={Ma, Liang and Wen, Jiajun and Lin, Min and Xu, Rongtao and Liang, Xiwen and Lin, Bingqian and Ma, Jun and Wang, Yongxin and Wei, Ziming and Lin, Haokun and others},
  journal={arXiv preprint arXiv:2506.08708},
  year={2025}
}'
---

While vision-language models (VLMs) have demonstrated promising capabilities in reasoning and planning for embodied agents, their ability to comprehend physical phenomena, particularly within structured 3D environments, remains severely limited. To close this gap, we introduce PhyBlock, a progressive benchmark designed to assess VLMs on physical understanding and planning through robotic 3D block assembly tasks. PhyBlock integrates a novel four-level cognitive hierarchy assembly task alongside targeted Visual Question Answering (VQA) samples, collectively aimed at evaluating progressive spatial reasoning and fundamental physical comprehension, including object properties, spatial relationships, and holistic scene understanding. PhyBlock includes 2600 block tasks (400 assembly tasks, 2200 VQA tasks) and evaluates models across three key dimensions: partial completion, failure diagnosis, and planning robustness. We benchmark 21 state-of-the-art VLMs, highlighting their strengths and limitations in physically grounded, multi-step planning. Our empirical findings indicate that the performance of VLMs exhibits pronounced limitations in high-level planning and reasoning capabilities, leading to a notable decline in performance for the growing complexity of the tasks. Error analysis reveals persistent difficulties in spatial orientation and dependency reasoning. Surprisingly, chain-of-thought prompting offers minimal improvements, suggesting spatial tasks heavily rely on intuitive model comprehension. We position PhyBlock as a unified testbed to advance embodied reasoning, bridging vision-language understanding and real-world physical problem-solving.