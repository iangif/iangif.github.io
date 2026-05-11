---
title: "Revisiting Age of Acquisition in Curriculum Learning: Disentangling Lexical Features and Semantic Structure"
collection: publications
category: conferences
permalink: /publication/2026-5-03-age-of-acquisition
excerpt: 'Exploring curriculum learning in the context of word embeddings using age-of-acquisition norms and correlated lexical features. (Contact me for preprint)'
date: 2026-5-03
venue: 'Conference on Computational Natural Language Learning (CoNLL)'
#slidesurl: 
#paperurl:
#bibtexurl: 
citation: '<b>Gifford, I.</b>, Shah, A., Chen, C., Kassab Bachi, T., and Portelance, E. 2026. Revisiting Age of Acquisition in Curriculum Learning: Disentangling Lexical Features and Semantic Structure. In Proceedings of the Conference on Computational Natural Language Learning (CoNLL). (to appear)'
---

### Presentations

- *Cognitive Science Undergraduate Research Forum (CogSURF) 2026* at McGill University

- *McGill's Conference from Linguistics Undergraduates (McCLU) 2026* at McGill University

- *Undergraduate Science Showcase 2026* at McGill University

### Abstract

Previous work has found that ordering training data by children’s Age of Acquisition (AoA) for words increases the stability of distributional word embeddings, suggesting that early-learned words play a privileged role in shaping semantic structure. In this study, we determine whether AoA itself drives these effects, or whether they emerge from correlated lexical factors such as frequency, concreteness, and phonological complexity. Using incremental Word2Vec training, we construct curricula ordered by AoA and by individual lexical features, while systematically controlling for vocabulary growth and deterministic ordering effects. We show that AoA-ordered curricula produce greater early-phase stability than shuffled baselines, even under controlled exposure conditions. We find that the advantage observed with AoA can be largely explained by correlated factors like overall word frequency. Despite limited gains on general similarity benchmarks, AoA-ordered embeddings outperform shuffled embeddings on a proxy domain-specific task: predicting human AoA norms. This advantage persists after debiasing timestamp effects, implying that AoA curricula induce developmentally meaningful semantic structure.