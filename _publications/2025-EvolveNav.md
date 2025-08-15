---
title: "EvolveNav: Self-Improving Embodied Reasoning for LLM-Based Vision-Language Navigation"
collection: publications
category: conferences
permalink: /publication/2025-EvoleNav
excerpt: 'Navigation, Embodied AI, Self-improving Reasoning, Large Language Model'
date: 2025-06-02
venue: 'Under Review'
slidesurl: # 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2506.01551'
citation: '@article{lin2025evolvenav,
  title={EvolveNav: Self-Improving Embodied Reasoning for LLM-Based Vision-Language Navigation},
  author={Lin, Bingqian and Nie, Yunshuang and Zai, Khun Loun and Wei, Ziming and Han, Mingfei and Xu, Rongtao and Niu, Minzhe and Han, Jianhua and Lin, Liang and Lu, Cewu and others},
  journal={arXiv preprint arXiv:2506.01551},
  year={2025}
}'
---

Building Vision-Language Navigation (VLN) agents which can navigate following natural language instructions is a long-standing goal in human-robot interaction applications. Recent studies have revealed the potential of training open-source Large Language Models (LLMs) to unleash LLMs' reasoning ability for improving navigation, and simultaneously mitigate the domain gap between LLMs' training corpus and the VLN task. However, these approaches primarily adopt direct input-output mapping paradigms, causing the mapping learning difficult and the navigational decisions unexplainable. Chain-of-Thought (CoT) training is a promising way to improve both navigational decision accuracy and interpretability, while the complexity of the navigation task makes the perfect CoT labels unavailable and may lead to overfitting through pure CoT supervised fine-tuning. In this paper, we propose a novel sElf-improving embodied reasoning framework for boosting LLM-based vision-language Navigation, dubbed EvolveNav. Our EvolveNav consists of two stages: (1) Formalized CoT Supervised Fine-Tuning, where we train the model with formalized CoT labels to both activate the model's navigational reasoning capabilities and increase the reasoning speed; (2) Self-Reflective Post-Training, where the model is iteratively trained with its own reasoning outputs as self-enriched CoT labels to enhance the supervision diversity. A self-reflective auxiliary task is also introduced to encourage learning correct reasoning patterns by contrasting with wrong ones. Experimental results on the popular VLN benchmarks demonstrate the superiority of EvolveNav over previous LLM-based VLN approaches.