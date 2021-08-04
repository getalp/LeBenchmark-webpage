---
layout: page
title: Tasks
permalink: /tasks/
---
  
We benchmark our SSL models on 4 different tasks (ASR, SLU, AST and AER) that were chosen with the following criteria:
    - diversity of problems: classification (AER), sequence labelling (SLU) and conditional natural language generation (ASR, AST),
    - diversity of information extracted: transcript (ASR), semantics (SLU), translation (AST) and paralinguistics (AER),
    - diversity of annotated resources available for downstream task: large (ASR), medium (SLU, AST) or small (AER).
  
## 1. Automatic Speech Recognition

**ETAPE** & **ESTER** The ASR tasks target two different types of corpora: Common Voice and ETAPE. Common Voice is a very large crowdsourced corpus (477h) of read speech in French with transcripts - training: 428 h, development: 24 h, and test: 25 h. ETAPE is a smaller (36 h) but more challenging corpus composed of diverse French TV broadcast programs - training: 22 h, development: 7 h, and test: 7 h.
   

## 2. Spoken Language Understanding
   
   **MEDIA** The MEDIA corpus is used for the French SLU benchmark. The corpus is made up of 12,908 utterances (41.5 h) for training, 1,259 utterances (3.5 h) for development and 3,005 utterances (11.3 h) for test.
   

## 3. Speech-to-text Translation
   
   **CV2** & **mTEDx** We selected subsets having French as the source language in two large multilingual speech corpora: CoVoST-2 and multilingual TEDx. Our benchmark covers translation directions from French to three target languages: English (en), Portugese (pt), and Spanish (es), with following training sizes: 50 h (TEDx/en), 38 h (TEDx/es), 25 h (TEDx/pt), and 180 h (CoVoST2/en).


## 4. Automatic Emotion Recognition

  **RECOLA** & **AlloSat** We used the RECOLA dataset, which contains 3.8 h of noise-free recordings of spontaneous interactions beetween French-speaking subjects solving a collaborative task in remote condition-training, development and test partitions include each one third of the data. AlloSat is a more recent corpus containing 37 h of real-life call center conversations in French-training: 25.6 h, development: 5.8 h, and test: 6.0 h. Both datasets are annotated by several annotators using time-continuous dimensions which are averaged to define an emotion gold-standard: arousal (from passive to active) and valence (from negative to positive) for RECOLA, and a dimensional axis ranging from frustration to satisfaction for AlloSat.
