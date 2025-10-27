---
title: "Automatically Advancing LLM Expertise in Technology Judgment"
collection: publications
category: conferences
permalink: /publication/2025-05-20-advancing-llm-expertise
excerpt: "We introduce a large-scale benchmark evaluating how language models discern subtle conceptual distinctions between semantically similar inventions, revealing mechanisms of knowledge use and self-questioning in LLMs."
date: 2025-05-20
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2505.12452"
citation: 'Siyang Wu, H. Bao, N. Kunievsky, and James A. Evans. (2025). <i>Automatically Advancing LLM Expertise in Technology Judgment.</i> arXiv:2505.12452.'
---

Large language models (LLMs) are rapidly becoming core tools for science, engineering, and innovation. Their promise lies not just in remembering facts, but in putting knowledge to work. Despite their impressive ability to answer increasingly difficult questions, it remains unclear whether LLMs truly use their knowledge when confronted with new and challenging tasks. We address this question with a patent classification task that requires deep conceptual understanding: distinguishing objectively different but semantically similar patents. To evaluate this approach, we introduce a challenging new benchmark of 1.3 million post-2015 computer science patent pairs, characterized by dense technical jargon and strategically complex writing. We find that LLMs often fail our benchmark and struggle to distinguish among semantically similar patents. To probe this failure, we introduce a novel framework that decomposes model errors into two sources: missing and unused knowledge. Our approach asks models to generate clarifying questions to improve their understanding, and then compares three settings: raw performance, self-answered questions, and externally supplied answers. This decomposition reveals that LLMs often possess the relevant knowledge internally but fail to deploy it, while a smaller share of errors arises from genuine knowledge gaps. We then ask whether the ability of models to construct a task-specific database of questions and answers differs across models. We find that smaller models generate simpler, broadly transferable questions, while larger models propose more complex but less generalizable ones. This suggests new strategies for combining strengths across models. Our findings highlight a critical limitation of current LLMs and their evaluation: models often know more than they can use. LLM evaluation should shift from recall of static facts to application of dynamic knowledge.
