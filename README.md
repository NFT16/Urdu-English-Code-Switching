# Urdu-English Code-Switching Speech Processing

## Overview
Automatic translation of Urdu-English code-switched speech
using OpenAI Whisper

## Dataset
- 60 audio files | 6 speakers (1 Male, 5 Female)
- Professional domain: office, academic, IT, healthcare
- Annotations: Roman Urdu, Nastaliq Urdu, English translation

## Results
| Metric | Score |
|--------|-------|
| Mean BLEU | 46.17 |
| Mean chrF | 76.26 |
| Files Processed | 60 / 60 |
| Perfect BLEU 100 | 5 files |

## Tech Stack
Python · Jupyter Notebook · OpenAI Whisper Medium  
Librosa · Pandas · Matplotlib · sacrebleu

## Project Structure
| File | Purpose |
|------|---------|
| Code_Switching_MainFile.ipynb | Main notebook |
| Code_Switching_GUI.ipynb | Main notebook |
| Translations.xlsx | Dataset metadata |
| Audios/ | Original audio files |
| Audios_Processed/ | Preprocessed audio files |
| results.csv | Evaluation results |
| eda_overview.png | EDA charts |
| evaluation_results.png | BLEU/chrF charts |