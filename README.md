# Cognitive Load Detection Using fNIRS & Machine Learning

This project builds a real-time system that detects a subject’s cognitive load level using fNIRS (functional near-infrared spectroscopy) brain signal data and adapts instructional content accordingly.

It combines signal processing, machine learning, and GPT-4-driven instructional adaptation to simulate how educational content might change dynamically based on a learner’s cognitive state.

---

## Project Goals

- Detect and classify cognitive load from raw fNIRS signals
- Simulate real-time streaming and prediction
- Adapt explanations dynamically using both predefined templates and GPT-4
- Support user-typed prompts to explore instructional strategies

---

## Features

- Feature extraction from multichannel fNIRS data
- Cognitive load classification using a Random Forest model
- Chunked time-series simulation to mimic real-time flow
- GPT-4 content adaptation via OpenAI API
- User override to test custom instruction prompts
- Visualization of cognitive load predictions over time

---

## Requirements

- Python 3.8 or later
- Packages:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `openai`
    
## Setup

1. Place your subject `.csv` files (fNIRS data) in the project directory. Each file should contain channel-wise recordings per timepoint.

2. Add your OpenAI API key in the notebook or script:
```python
import openai
openai.api_key = "your-api-key"

