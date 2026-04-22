# Binary Sentiment Classification with Robustness Testing under Domain Shift and Calibration

**MSc Data Science Project**  
**Module:**  7PAM2002-0206-2025<br>
**Institution:** University of Hertfordshire

This project performs **binary sentiment analysis** using transformer-based language models and compares their performance on sentiment classification tasks.

The notebook includes experiments with:

- **DistilBERT**
- **RoBERTa**
- **GPT-2**

It also explores model evaluation, confidence calibration, and domain shift analysis.

---

## Project Overview

The aim of this project is to classify text into two sentiment categories:

- **Positive**
- **Negative**

The notebook demonstrates how transformer models can be used for sentiment classification and how their outputs can be evaluated beyond simple accuracy.

---

## Features

- Binary sentiment classification
- Use of pretrained transformer models
- Model comparison across multiple architectures
- Evaluation using performance metrics
- Confidence calibration analysis
- Domain shift / robustness analysis
- Visual output plots for interpretation

---

## Models Used

### 1. DistilBERT
A smaller and faster version of BERT, useful for efficient text classification tasks.

### 2. RoBERTa
A robustly optimized BERT-based model that often performs strongly on NLP classification tasks.

### 3. GPT-2
A generative transformer model adapted here for sentiment-related experimentation and comparison.

---

## Notebook Contents

The notebook includes the following stages:

1. Importing required libraries  
2. Loading and preparing the dataset  
3. Preprocessing text data  
4. Tokenization  
5. Loading pretrained transformer models  
6. Training / inference workflow  
7. Performance evaluation  
8. Calibration analysis  
9. Plot generation and result interpretation  

---

## Technologies Used

- Python
- Jupyter Notebook
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Notes
- Some parts of the notebook may take a long time to run because the models are fine-tuned on large datasets.
- A GPU is recommended for training.
- If you are viewing this on GitHub, open the notebook directly to see the workflow step by step.

---

## File Structure

```text
Binary-Sentiment-Classification-with-Robustness-Testing/
│
├── binary_sentiment.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Binary-Sentiment-Classification-with-Robustness-Testing.git
cd Binary-Sentiment-Classification-with-Robustness-Testing
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:
binary_sentiment.ipynb

5. Run the notebook cells in order.

---

## Output and Evaluation

The notebook includes saved outputs such as:

- model evaluation metrics
- comparison results
- calibration-related results
- robustness testing outputs
- visual plots and charts

These outputs are included so the notebook can be previewed more clearly on GitHub.

## Notes

- Some parts of the notebook may take a long time to run because the models are fine-tuned on large datasets.
- A GPU is recommended for training.
- If you are viewing this on GitHub, open the notebook directly to see the workflow step by step.

## Academic Context

This project was developed as part of a dissertation study in sentiment analysis, model calibration, and robustness under domain shift.

## Author

**Riyanka**

## License

This project is intended for academic and learning purposes.
