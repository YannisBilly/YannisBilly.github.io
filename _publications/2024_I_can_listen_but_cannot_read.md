---
title: "I can listen but cannot read: An evaluation of two-tower multimodal systems for instrument recognition"
collection: publications
category: conferences
permalink: /publication/2024_I_can_listen_but_cannot_read
excerpt: 'Joint Audio-Text models have been used for Music Information Retrieval with mediocre performance in multiclass classification tasks. This consists of the first thorough analysis for the potential pitfalls in these systems through an oversimplistic instrument recognition task. Language models seem to not understand intstrumentation and Audio Encoders posses adequate musical knowledge.'
date: 2024-11-14
venue: 'International Society for Music Information Retrieval (ISMIR)'
slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://zenodo.org/records/14877475'
citation: 'Yannis Vasilakis, Rachel Bittnerand Johan Pauwels, ‘I Can Listen but Cannot Read: An Evaluation of Two-Tower Multimodal Systems for Instrument Recognition’, in Proceedings of the 25th International Society for Music Information Retrieval Conference, San Francisco, California, USA and Online, Nov. 2024, pp. 897–905. doi: 10.5281/zenodo.14877475.'
bibtex: './bibtex/ismir_an_evaluation_of_vasilakis_2024.bib'
---
### Abstract

Music two-tower multimodal systems integrate audio and text modalities into a joint audio-text space, enabling direct comparison between songs and their corresponding labels. These systems enable new approaches for classification and retrieval, leveraging both modalities. Despite the promising results they have shown for zero-shot classification and retrieval tasks, closer inspection of the embeddings is needed. This paper evaluates the inherent zero-shot properties of joint audio-text spaces for the case-study of instrument recognition. We present an evaluation and analysis of two-tower systems for zero-shot instrument recognition and a detailed analysis of the properties of the pre-joint and joint embeddings spaces. Our findings suggest that audio encoders alone demonstrate good quality, while challenges remain within the text encoder or joint space projection. Specifically, two-tower systems exhibit sensitivity towards specific words, favoring generic prompts over musically informed ones. Despite the large size of textual encoders, they do not yet leverage additional textual context or infer instruments accurately from their descriptions. Lastly, a novel approach for quantifying the semantic meaningfulness of the textual space leveraging an instrument ontology is proposed. This method reveals deficiencies in the systems' understanding of instruments and provides evidence of the need for fine-tuning text encoders on musical data.

---
### More info
Add your ideas here.

---