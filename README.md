# BharatVaani: A Multilingual Indic Corpus and Latent Text-Guided Knowledge Distillation for Direct Speech-to-Speech Translation

The main contributions of this paper are as follows:

- We release [BharatVaani](https://huggingface.co/datasets/latentvector/BharatVaani), a multilingual parallel speech corpus comprising approximately **732 hours** of aligned speech across **35 Indic languages**.

<img width="753" height="660" alt="final-1new_mkbalignment1" src="https://github.com/user-attachments/assets/67d1c4a3-15c0-4b34-bf99-f8a7081af413" />

- We introduce a scalable pipeline for constructing multilingual parallel speech corpora and propose an **Adaptive Sliding Window Alignment Strategy** for accurate cross-lingual speech alignment.
  
<img width="659" height="905" alt="1final-new-sliding_window_v6" src="https://github.com/user-attachments/assets/96138a28-1946-4cee-8d99-aeee370dbe8c" />

- We propose **Latent Text-Guided Knowledge Distillation (LTKD)**, a framework for fully textless **direct speech-to-speech translation (DS2ST)** that distills latent linguistic knowledge from a multilingual teacher into an **S2UT** student.

<img width="1312" height="422" alt="final-ltkd_framework_v7" src="https://github.com/user-attachments/assets/1c81da23-22d0-4a81-be41-d0f3de222283" />

- We conduct a large-scale **DS2ST evaluation across 34 Indic languages to English**, including **20 languages not represented in benchmarks such as FLEURS**, showing that multilingual LTKD narrows the gap with text-supervised baselines and generalizes to unseen languages.
