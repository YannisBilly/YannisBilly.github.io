---
title: "Evaluation of pretrained language models on music understanding"
collection: publications
category: workshops
permalink: /publication/2024_Evaluation_of_preatrined_language_models
excerpt: 'Language models (BERT models and variants) are used off-the-shelf to obtain embeddings for music captions. This work proposes a novel way to quantify how much musical knowledge these models possess and check if they can be used off-the-shelf without fine-tuning.'
date: 2024-11-15
venue: '3rd Workshop on NL for Music and Audio (NLP4MusA)'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://aclanthology.org/2024.nlp4musa-1.16/'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
bibtex: './bibtex/vasilakis-etal-2024-evaluation_nlp4musa.bib'
---
### Abstract

Music-text multimodal systems have enabled new approaches to Music Information Research (MIR) applications such as audio-to-text and text-to-audio retrieval, text-based song generation, and music captioning. Despite the reported success, little effort has been put into evaluating the musical knowledge of Large Language Models (LLM). In this paper, we demonstrate that LLMs suffer from 1) prompt sensitivity, 2) inability to model negation (e.g. 'rock song without guitar'), and 3) sensitivity towards the presence of specific words. We quantified these properties as a triplet-based accuracy, evaluating the ability to model the relative similarity of labels in a hierarchical ontology. We leveraged the Audioset ontology to generate triplets consisting of an anchor, a positive (relevant) label, and a negative (less relevant) label for the genre and instruments sub-tree. We evaluated the triplet-based musical knowledge for six general-purpose Transformer-based models. The triplets obtained through this methodology required filtering, as some were difficult to judge and therefore relatively uninformative for evaluation purposes. Despite the relatively high accuracy reported, inconsistencies are evident in all six models, suggesting that off-the-shelf LLMs need adaptation to music before use.

---
### More info
Add your ideas here.

---