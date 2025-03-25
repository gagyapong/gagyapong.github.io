---
title: "LCUGA 2025 Presentation"
excerpt: "How Clean Should My Data Be?. <br/><img src='/images/500x300.png'>"
collection: portfolio
---

This study examines the effectiveness of Transformer models in morphological segmentation for
Nyangbo (Kwa, Gur), a tonal and endangered language spoken in Ghana. Four datasets—noisy,
cleaned, noisy_reduced, and combined—were used to evaluate the performance of a supervised
Transformer model. Results show that the model achieves superior performance with larger, noisy
datasets and combined datasets compared to smaller, cleaned datasets. Specifically, segmentation
and gloss prediction with noisy data resulted in an F1 score of 33.29%, outperforming the 29.96%
F1 score achieved with cleaned data. For segmentation alone, the model recorded F1 scores of
62.57% (noisy) and 57.82% (cleaned), illustrating the importance of balancing data size and
quality. Additionally, Morfessor 2.0 was trained in both supervised and unsupervised settings to
evaluate its ability to process a low-resource tonal language, with the supervised model achieving
an F1 score of 72%.
Nyangbo’s unique linguistic features, including its agglutinative structure and complex tonal
system, present significant challenges for morphological segmentation. In this language, entire
sentences can be represented as single words. For example:
1. a-tɛ́-ba-dɛ́-mᴐ-ɛ́
3SG-NEG-FUT-DIRECTIONAL-VERB-OBJ
‘S/he will not go and see her/him.
’
This example highlights the interaction of multiple morphemes, including the pronominal affix a-
, negation affix tɛ ́ -, tense affix ba-, directional marker dɛ ́ -, verb mᴐ, and the object pronoun -í,
which assimilates to -ɛ ́ . The ability to accurately segment such structures is critical for
computational linguistic applications.
Key findings suggest that combining noisy and cleaned datasets enhances generalization while
using exclusively noisy data risks overfitting to noise patterns. Figures depicting training losses
for noisy and cleaned datasets indicate that cleaner datasets promote better convergence, whereas
noisy datasets introduce variability during training. Error analysis further revealed common
challenges, including substitution errors driven by phonological similarities, omission of crucial
morphemes, and unnecessary insertions, particularly with tonal and morphologically complex
forms. These findings provide guidance for improving machine learning models for low-resource
languages through strategic data preparation and curation. 
