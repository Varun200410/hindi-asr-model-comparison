# hindi-asr-model-comparison
# Hindi Conversational ASR Model Comparison & Evaluation

## Project Overview
This project presents a comparative evaluation of multiple Automatic Speech Recognition (ASR) models on Hindi conversational speech data. The objective is to benchmark different speech-to-text systems and compare their transcription quality using standard evaluation metrics.

The project was developed as part of an AI evaluation assignment focused on real-world Hindi conversational audio transcription.

---

## Problem Statement
Automatic Speech Recognition systems often perform differently depending on language, accent, conversational context, and background noise.

Hindi conversational speech presents challenges such as:

- Informal speaking patterns
- Regional pronunciation variations
- Background disturbances
- Partial/incomplete utterances
- Context ambiguity

This project compares multiple ASR models to determine which performs best for Hindi conversational speech recognition.

---

## Objectives
The primary objectives of this project are:

- Compare transcription outputs from multiple ASR models
- Evaluate recognition accuracy against human-annotated transcripts
- Measure transcription quality using industry-standard metrics
- Visualize model performance differences
- Identify the most reliable ASR model for Hindi speech transcription

---

## Dataset
The dataset consists of Hindi conversational speech segments with:

- Audio segment links
- Human ground truth transcripts
- Predictions from multiple ASR models

### Dataset Features
Each sample includes:

- Segment ID
- Audio URL
- Human transcription
- Model-generated transcription outputs

### Language
Hindi

### Data Type
Conversational Speech Audio

---

## Models Compared
The following ASR models were benchmarked:

- Model H
- Model i
- Model k
- Model l
- Model m
- Model n

(Replace with actual model names if available)

---

## Evaluation Metrics
The following speech recognition evaluation metrics were used:

### Word Error Rate (WER)
Measures transcription errors at word level.

Formula:

WER = (Substitutions + Deletions + Insertions) / Total Words

Lower WER indicates better performance.

---

### Character Error Rate (CER)
Measures character-level transcription errors.

Lower CER indicates better recognition quality.

---

### Accuracy Comparison
Relative transcription accuracy across models.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- JiWER
- Kaggle Notebook Environment

---

## Project Workflow

### Step 1: Data Preparation
- Load Hindi conversational speech benchmark dataset
- Organize human and model transcripts

### Step 2: Metric Computation
Calculate:

- WER
- CER
- Model comparison statistics

### Step 3: Performance Analysis
Compare all ASR models against human transcripts.

### Step 4: Visualization
Generate charts for:

- WER comparison
- CER comparison
- Overall performance ranking

---

## Project Structure
```bash
hindi-asr-model-comparison/
│
├── data/
│   └── Question_4_Task.csv
│
├── notebooks/
│   └── asr_model_comparison.ipynb
│
├── images/
│   └── results_visualization.png
│
├── requirements.txt
├── README.md
└── LICENSE
Author

Prakhar Kishore
