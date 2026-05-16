# Part 3: NLP Sequence Modeling

This folder contains the Part 3 NLP project for customer support sentiment classification.

## Contents

- `notebook.ipynb`: Notebook with dataset understanding, preprocessing, text vectorization, baseline modeling, and sequence-modeling discussion.
- `customer_support_text_classification.csv`: Dataset with customer messages and sentiment labels.
- `requirements.txt`: Python package requirements for running the notebook.
- `results/`: Generated model evaluation outputs.
  - `model_evaluation.csv`
  - `sample_predictions.txt`
  - `summary_metrics.csv`
  - `sample_preprocessing.csv`

## How to run

1. Create and activate a Python environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `notebook.ipynb` and run the cells.

## Project goals

- Understand dataset structure and sentiment classes.
- Clean and preprocess text for NLP.
- Compare TF-IDF vectorization and baseline classification.
- Describe a sequence-based architecture for RNN/LSTM models.
- Reflect on attention and transformer concepts.
