# C1 — English to Urdu Machine Translation

## Project Information
- **Course:** AI-101 Introduction to Artificial Intelligence
- **Task:** C1 — Machine Translation
- **Dataset:** OPUS-100 (English–Urdu)
- **Model:** Helsinki-NLP/opus-mt-en-ur
- **Framework:** Hugging Face Transformers
- **Hardware:** Google Colab Tesla T4 GPU

## Objective
The objective of this project is to develop an English-to-Urdu machine translation system using a pretrained sequence-to-sequence model.

## Dataset
The OPUS-100 English–Urdu dataset was used.

- Training examples used: 20,000
- Validation examples used: 1,000
- Test examples evaluated: 500

## Methodology
1. Loaded the OPUS-100 English–Urdu dataset.
2. Tokenized English input and Urdu target sentences.
3. Loaded the pretrained MarianMT model.
4. Fine-tuned the model for one epoch.
5. Generated Urdu translations for test sentences.
6. Evaluated translation quality using BLEU and chrF.

## Results

| Metric | Score |
|---|---:|
| BLEU | 23.02 |
| chrF | 43.55 |
| Training Loss | 0.4505 |
| Validation Loss | 0.8763 |

## Limitations
Some translations contain grammatical errors, missing information, or differences in meaning. Translation quality may improve with more training data and additional fine-tuning.

## Dataset Citation
OPUS-100: A Multilingual Corpus for Evaluation of Low-Resource Languages. Hugging Face: Helsinki-NLP/opus-100.

## AI Use Disclosure
AI tools assisted with documentation and understanding implementation concepts. Model training, evaluation, and reported results are based on actual project experiments.
