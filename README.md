# German-AI-Tutor
An AI-powered German speaking assistant designed to help non-native German learners practise speaking, improve their grammar, and understand spoken German through transcription and translation.

## Problem Statement

Non-native German learners often lack affordable opportunities to practise speaking German and receive meaningful feedback. Identifying grammatical mistakes, understanding spoken sentences, and improving pronunciation can be challenging without regular guidance.

This project aims to address these challenges through an AI-powered application that analyses German speech and provides language-learning assistance.

## Impact

The project aims to make German language learning more accessible by providing learners with an interactive tool for practising spoken German.

By combining speech recognition, grammar correction, and machine translation, the application can help users identify mistakes, understand their sentences, and improve their German communication skills.

## Scope

**Target Audience:** Non-native German learners and individuals practising German as a second language.

**Key Deliverables:**

- Audio input through uploaded or recorded German speech.
- German speech transcription using Whisper models.
- German grammar correction using an mBART-based model.
- German-to-English translation.
- A Streamlit interface for interacting with the AI pipeline.
- Planned pronunciation assessment and personalized learning feedback.

## AI Models

| Component | Selected Model |
|---|---|
| Speech Recognition | openai/whisper-base |
| German Speech Recognition | bofenghuang/whisper-small-cv11-german |
| Grammar Correction | MRNH/mbart-german-grammar-corrector |
| Translation | Aparna852/de-en-translator |

## Technologies

- Python
- Hugging Face Transformers
- PyTorch
- Librosa
- Streamlit
- Google Colab

## Project Status

Prototype development in progress.
