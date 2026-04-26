# Fake News Detection using IndicBERT Transformer

## Project Overview

This project focuses on detecting fake news using Transformer-based Deep Learning and Natural Language Processing (NLP) techniques. The goal is to classify news articles as Fake or Real by analyzing textual content using the IndicBERT Transformer model.

The model was trained and evaluated on the TALLIP Fake News Dataset and achieved strong performance across multiple domains such as Business, Celebrity, Education, Entertainment, Politics, Sports, and Technology.

This approach improves contextual understanding of text and provides better semantic learning compared to traditional machine learning models.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* PyTorch
* Hugging Face Transformers
* IndicBERT
* NLP Techniques
* Matplotlib
* Scikit-learn

---

## Dataset Used

Dataset Name: TALLIP Fake News Dataset

Source: IIT Patna (AI-NLP-ML Resources)

Dataset Link:
http://www.iitp.ac.in/~ai-nlp-ml/resources/data/TALLIP-FakeNews-Dataset.zip

---

## Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Text Tokenization using IndicBERT Tokenizer
4. Transformer-based Model Training
5. Model Evaluation
6. Domain-wise Performance Analysis
7. Final Prediction and Reloaded Model Testing

---

## Model Performance

### Overall Results

* Accuracy: 86.01%
* Precision: 0.86
* Recall: 0.86
* F1-Score: 0.86

### Domain-wise Performance

The model was tested across multiple domains:

* Business → 78.18%
* Celebrity → 84.81%
* Education → 96.72%
* Entertainment → 90.48%
* Politics → 93.33%
* Sports → 79.10%
* Technology → 85.92%

Best performance was observed in Education and Politics domains.

---

## Screenshots

### Overall Model Accuracy
![Overall Accuracy](overall_model_accuracy.png)

### Domain-wise Performance
![Domain Performance 1](domain_wise_performance_1.png)
![Domain Performance 2](domain_wise_performance_2.png)

---

## How to Run

1. Open the notebook in Google Colab
2. Upload the dataset files
3. Install required libraries and transformer dependencies
4. Run all cells sequentially
5. View predictions and evaluation results

---

## Future Improvements

* Fine-tuning with larger multilingual datasets
* BERT / RoBERTa comparative analysis
* Real-time fake news verification system
* Web deployment using Flask or Streamlit

---
