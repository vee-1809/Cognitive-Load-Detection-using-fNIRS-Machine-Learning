# Cognitive Load Detection Using fNIRS & Machine Learning

This project builds a real-time system that detects a subject’s cognitive load level using fNIRS (functional near-infrared spectroscopy) brain signal data and adapts instructional content accordingly.

## Project Goals

- Detect and classify cognitive load from fNIRS signals
- Simulate real-time streaming and prediction
- Adapt explanations dynamically using both static templates and GPT-4
- Allow user override for prompt customization

## Features

- Feature extraction from multichannel fNIRS CSV data
- Random Forest model for cognitive load classification
- Chunked simulation to mimic real-time inference
- OpenAI GPT-4 integration for personalized content adaptation
- User-typed prompts for testing instructional flexibility

## File Overview

- `Cognitive_Load_Detection_fNIRS_Final_Colab.ipynb`: Full, polished Colab-compatible notebook
- `polished_cognitive_load_detection_fnirs.py`: Clean version of the project as a Python script

## Requirements

- Python 3.8+
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`
- `openai` (for GPT-4 integration)
- fNIRS `.csv` files (1 per subject)

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib openai



