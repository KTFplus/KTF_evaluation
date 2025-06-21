# KTF_evaluation
Korean Pronunciation Evaluation using Whisper-based ASR &amp; Similarity Metrics

# KTF Pronunciation Evaluation

This repository contains the core evaluation logic for the pronunciation feedback module of the **KTF (Korean Training & Feedback)** project.

The system evaluates Korean pronunciation accuracy using Whisper-based automatic speech recognition (ASR), compares it against reference sentences, and analyzes errors based on insertion, deletion, and substitution.

---

## Features

- **Korean Speech Recognition**: Based on [Whisper-Large-v3](https://huggingface.co/openai/whisper-large-v3) model (Hugging Face)
- **Pronunciation Evaluation**: Sentence-level matching, similarity scoring
- **Error Analysis**: Insertion, deletion, substitution counts
- **Backend Compatibility**: API-ready evaluation logic (FastAPI supported)
- **Notebook-based Prototyping**: Easy testing & visualization in Colab

---

## File Structure

| File Name            | Description                                   |
|----------------------|-----------------------------------------------|
| `KTF_evaluate.ipynb` | Evaluation logic for Korean pronunciation     |
| *(future)* API files | (To be added for full backend integration)   |

---

## How to Use

1. Run `KTF_evaluate.ipynb` in Colab or locally (Python 3.10+ recommended)
2. Upload a Korean speech `.wav` file
3. Select a `sentence_id` and compare the recognized text with reference
4. View similarity score and error types

---

## Tech Stack

- Python 3.10+
- Whisper ASR (HuggingFace)
- Cosine Similarity & Levenshtein distance
- FastAPI (for backend integration)
- Google Colab (for prototyping)

---

## Project Note

This module is part of the broader **KTF** initiative, aiming to support language learners with accurate and intuitive pronunciation feedback through AI.

