---
title: "Study on the effectiveness of NLP tools for syntactic analysis of French texts."
date: 2019-06-06
pubtype: "Paper"
featured: true
description: "The paper was a thourough study on the effectiveness of NLP tools (spaCy, MaltParser, and others) when applied on French texts."
tags: ["NLP","Data science","Language processing","Python"]
image: "/img/nlp.png"
link: "https://www.researchgate.net/project/Etude-sur-lefficacite-des-outils-danalyse-du-texte-NLP-sur-les-textes-en-francais"
fact: "The analysis reflected the bad interpretation of the French texts by the current tools."
weight: 400
sitemap:
  priority : 0.8
---

NLP (natural language processing) is the field of artificial intelligence that deals with the processing, analysis and understanding of natural language. It began to emerge and play an indispensable role since the 1950s with its usefulness in document translation, text indexing, and text-like data mining.

The advancement in the use of NLP tools has followed an exceptional development, from an automatic translator at the beginning to an assistant that structures information into computer-understandable data to eventually a more developed and complex form that began since the 2000s with the help of growth in artiﬁcial intelligence hardware, big data, and deep learning. It is now the basis of all search engines, text ﬁlters(SPAM detectors) and even speech recognition technology.

The project "Study on the eﬃciency of French text parsing tools" is in line with the project "Study of the performance of POS-taggers applied to the French language" which consisted of re-launching comparisons on the results of the POS-tagging outputs of its tools with a French language corpus(French TreeBank). Similarly, this project focused on the comparison of the same NLP tools but in another more complex domain, namely syntactic dependency.

This research was applied to the basic French texts' corpus (a.k.a French TreeBank -FTB-), which consists of articles from multiple newspapers published between 1990 and 1993. The corpus itself is not vast, it carried over 21 500 senteces with 664 500 tokens (POS-tags), but it was suitable for a medium size analysis.

The analysis was a syntactic analysis, which in simple words means finding the relations between the words of a given sentence. The steps taken were simple and clear:

- Clean&format the corpus.
- Adapt the texts to each tool.
- Analyse the texts and aggregate the outputs.
- Cross-validate over the same texts.
- Plot the results for each tool.
- (Bonus) Compare&Plot the inference time for each tool.

