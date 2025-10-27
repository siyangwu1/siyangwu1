---
title: "Mapping Overlaps in Benchmarks through Perplexity in the Wild"
collection: publications
category: conferences
permalink: /publication/2025-09-28-mapping-overlaps-in-benchmarks
excerpt: "We connect benchmark semantics, performance, and token-level perplexity signatures to uncover hidden overlaps and define new evaluation axes for LLM benchmarking."
abstract: "We develop signatures of capacity familiarity to characterize large language model (LLM) benchmarks and their meaningful overlaps. Benchmark signatures probe the capacity required for benchmark performance. We formally define them as a set of salient tokens drawn from in-the-wild, naturally authored corpora, where LLM token perplexity, reflecting more or less pre-training exposure, becomes highly predictive of LLM benchmark performance. Through a large-scale meta-evaluation, we extract benchmark signatures via stepwise forward selection with linear regressions across 32 LLMs and 88 benchmarks spanning diverse knowledge, coding, logic, instruction following, math, language, reasoning, and world modeling. Our analysis situates signatures in relation to both the semantic similarity of benchmark questions and the correlation of model performance. While performance overlaps are universally high and semantic overlaps remain confined to a narrow mid-range, benchmark signatures prove highly informative in capturing variation, overlap, and divergence. We observe overlap in knowledge and reasoning subtasks, whereas multilingual and cultural benchmarks exhibit less similarity, even compared to cross-task overlap. Notably, performance-level results are strongly influenced by benchmark-orthogonal factors such as question format, highlighting limitations in LLM generalization, the conflation of performance with ability, and issues inherent in current mainstream benchmark agreement studies. Benchmark signatures, however, remain robust to such effects. Ultimately, we identify cross-functional overlaps across logic, math, language, instruction following, and world modeling, with coding emerging as the least overlapping domain. Together, these findings provide mechanistic insights into benchmark validity and LLM sensitivities, and sketch the underlying landscape of interconnected LLM capabilities."
date: 2025-09-28
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2509.23488v1"
citation: 'Siyang Wu*, H. Bao*, S. Li*, Ari Holtzman, and James A. Evans. (2025). <i>Mapping Overlaps in Benchmarks through Perplexity in the Wild.</i> arXiv:2509.23488v1.'
author: "Siyang Wu*, H. Bao*, S. Li*, Ari Holtzman, and James A. Evans"
---


