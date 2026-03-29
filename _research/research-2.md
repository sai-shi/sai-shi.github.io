---
title: "Research Project II: Human-LLM collaboration on efficient annotation and analysis of educational data"
excerpt: "Keywords: ranking, subjectivity, correlation, computer science."
collection: research
---
Part 1:
We study label-efficient rare-class discovery in large-scale text corpora under limited annotation budgets, where the goal is not exhaustive labeling but construction of a representative subset that achieves balanced coverage across semantic categories. Starting from a partial codebook, we formulate rare-theme discovery as a hierarchical sampling problem that jointly expands category coverage and refines the representation space. We propose a closed-loop framework that alternates between embedding learning, hierarchical clustering, rarity-aware node selection, and LLM-assisted annotation. The resulting subsets support scalable qualitative analysis of what themes students discuss, how they express them, and how evaluation patterns emerge across the hierarchy.

Part 2:
An ablation study is performed to evaluate the importance of different decisions for CS department ranking ([Our paper](https://doi.org/10.1007/s11192-023-04733-2)). The results show that the selection of publication venues has the highest impact on the ranking. In contrast, decisions related to publication recency, multi-author publications, and clustering publications into subareas have less impact. Overall, Pearson's correlation coefficient between the publication-based scores and the U.S. News ranking is above 0.90 for a large range of decisions, indicating a strong agreement between the objective measure and the subjective opinion of peers.  



