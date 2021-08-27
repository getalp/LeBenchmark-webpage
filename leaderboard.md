---
layout: page
title: Leaderboard
permalink: /leaderboard/
---
<script src="https://code.iconify.design/1/1.0.7/iconify.min.js"></script>

>Task-agnostic pre-training only (1 single SSL model for all tasks).
>AER results reported are obtained with the GRU-32 architecture


| Model | ASR-hybrid ETAPE | ASR-e2e CommonVoice | ASR-e2e ETAPE | SLU MEDIA | AST mTEDx fr-en | AST mTEDx fr-es | AST mTEDx fr-pt | AER RECOLA Valence   | AER RECOLA Arousal   | AER AlloSat   
| ----- | ----- | ----- | ------ | ---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | 
| MFB or Spectro or MFCC  | 31.93 | 20.59 | 54.36 |  31.10 | 1.10 | 0.87 | 0.32 | 0.373 | 0.655 | 0.611 | 
| W2V-Fr-1K-base <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-1K-base"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>     | 35.69 | - | - | 23.27  | 8.98 | 5.64 | 0.49 | 0.331 | 0.654 | 0.641 | 
| W2V-Fr-1K-large <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-1K-large"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>   | 34.91 | - | - | 20.66  | 14.46 | 14.77 | 9.37 | **0.555** |**0.709** | 0.601 | 
| W2V-Fr-3K-base <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-3K-base"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>                            | 27.82 | 13.22 | 28.86 | 18.56 | 14.80 | 14.27 | 4.72 | 0.388 | 0.700 | **0.732** | 
| W2V-Fr-3K-large <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-3K-large"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>                           | 28.56 | **9.75** | **26.14** | **15.95**  | 18.00 | 18.12 | 9.55 | 0.202 | 0.267 | 0.468 | 
| W2V-Fr-7K-base <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-7K-base"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>                            | 27.09 | 12.88 | 28.16 | 18.86 | 14.50 | 13.61 | 2.66 | 0.406 | 0.700 | 0.653 | 
| W2V-Fr-7K-large <a href="https://huggingface.co/LeBenchmark/wav2vec2-FR-7K-large"><span class="iconify" data-icon="ion-md-link" data-inline="false"></span></a>                           | **25.64** | 9.94 | 27.25 | 16.35  | **19.04** | **18.24** | **10.98** | 0.214 | 0.203 | 0.510 | 


> Results on test sets 
>
><sub> **ASR ETAPE** : Automatic Speech Recognition - WER (%)
>
><sub> **ASR CommonVoice** : Automatic Speech Recognition - WER (%)
>
><sub> **SLU MEDIA** : Spoken Langue Understanding - Concept Error Rate - CER (%)
>
><sub> **AST mTEDx** : Speech to Text Translation - BLEU (for 3 language pairs: fr-en, fr-es and fr-pt)
>
><sub> **AER RECOLA Arousal** : Automatic Emotion Recognition - Concordance Correlation Coefficient for Arousal
>
><sub> **AER RECOLA Valence** : Automatic Emotion Recognition - Concordance Correlation Coefficient for Valence
>
><sub> **AER AlloSat** : Automatic Emotion Recognition - Concordance Correlation Coefficient for Satisfaction
