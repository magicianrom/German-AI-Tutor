
# German-AI-Tutor

An AI-powered German speaking assistant designed to help non-native German learners understand spoken German, identify grammatical mistakes, and translate their speech into English using deep learning and natural language processing models.

## Problem Statement

Non-native German learners often lack affordable opportunities to practise speaking German and receive meaningful feedback. Identifying grammatical mistakes, understanding spoken sentences, and improving pronunciation can be challenging without regular guidance.

This project aims to address these challenges through an AI-powered application that analyses German speech and provides language-learning assistance.

## Impact

The project aims to make German language learning more accessible by providing learners with an interactive tool for analysing their spoken German.

By combining speech recognition, grammar correction, and machine translation, the application can help users understand their spoken sentences, identify grammatical mistakes, and improve their German communication skills.

## Scope

**Target Audience:** Non-native German learners and individuals practising German as a second language.

**Key Deliverables:**

- Audio input through uploaded German audio recordings (M4A/MP3).
- German speech transcription using Whisper models.
- Comparison of general-purpose and German-specific speech recognition models.
- German grammar correction using an mBART-based model.
- German-to-English translation of corrected German sentences.
- A Streamlit interface for interacting with the AI pipeline.
- Future pronunciation assessment and learning feedback.

## AI Models

| Component | Selected Model |
|---|---|
| Speech Recognition (Baseline) | `openai/whisper-base` |
| German Speech Recognition | `bofenghuang/whisper-small-cv11-german` |
| Grammar Correction | `MRNH/mbart-german-grammar-corrector` |
| German-to-English Translation | `Aparna852/de-en-translator` |

## Project Structure

| File | Purpose |
|---|---|
| `notebooks/german_tutor.ipynb` | Notebook for loading and preprocessing audio recordings, testing and comparing Whisper models, correcting German grammar, and translating German speech into English. |
| `app.py` | Planned Streamlit application that will allow users to upload German audio and view transcription, grammar correction, and translation results. |
| `data/` | Directory for storing datasets and sample audio files used for testing and evaluation. |
| `requirements.txt` | Python dependencies required to run the project, including Transformers, PyTorch, Librosa, Datasets, and SoundFile. |
| `.gitignore` | Specifies files and folders that should not be uploaded to GitHub, such as temporary files, environment variables, and personal audio recordings. |
| `README.md` | Project documentation explaining the problem statement, impact, scope, selected AI models, and project overview. |

## Technologies

- Python
- Hugging Face Transformers
- PyTorch
- Librosa
- Hugging Face Datasets
- Streamlit
- Google Colab

## Project Status

Prototype development in progress.
