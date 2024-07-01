---
title: "VisLTR: Visualization-in-the-Loop Table Reasoning"
collection: publications
permalink: /publication/publication-1
excerpt: 'Table reasoning transforms user requirements into corresponding answers according to the provided table, which is often integrated with natural language interfaces for lay users to explore tabular data effortlessly...'
date: 2024-06-06
venue: 'Journal 1'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2406.03753'
citation: 'Hao J, Liang Z, Li C, et al. VisLTR: Visualization-in-the-Loop Table Reasoning[J]. arXiv preprint arXiv:2406.03753, 2024.'
---

Abstract: Table reasoning transforms user requirements into corresponding answers according to the provided table, which is often integrated with natural language interfaces for lay users to explore tabular data effortlessly. Recent research exploits large language models to facilitate table reasoning, by transforming vague user requirements into structured query languages (SQLs). However, these SQL-based approaches often overlook changes in data patterns, suffer from LLM drift, and limit exploration to only text queries. To this end, VisLTR is designed as a visualization-in-the-loop table reasoning framework that leverages visualizations as a proxy to provide concise data representations, capture interesting data patterns, and support cross-modal analysis. We describe VisLTR as a process consisting of four major modules: 1) visualization alignment that utilizes large vision-language models to align visualizations across various modalities, including chart, text, and sketch; 2) visualization referencing that decomposes a table into multifaceted visualization references that comprehensively represent the table; 3) visualization pruning that incorporates data and retrieval pruning to excise visualization references with poor information and enhance retrieval efficiency; and 4) visualization interaction that offers an interactive visual interface with multi-modal interactions for user-friendly table reasoning. Quantitative evaluation demonstrates the effectiveness of the alignment model in cross-modal visualization pairings. We further demonstrate applications of the framework on various table reasoning tasks such as table summarization and pattern detection.