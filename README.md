# Text Classification with TensorFlow

This project classifies Amazon product reviews as positive or negative using deep learning models built with TensorFlow.  

---

## Project Overview
- Dataset: Amazon product reviews (ratings + review text)
- Labels:
  - Ratings 4–5 → Positive (1)
  - Ratings 1–2 → Negative (0)
  - Rating 3 → Neutral (removed)
- Task: Binary Sentiment Classification  

---

## Steps
1. Data Preprocessing
   - Removed missing values and neutral reviews
   - Tokenized review text
   - Padded sequences for equal length
   - Handled class imbalance using class weights  

2. Models Built
   - Embedding + Dense model (simple baseline)  
   - Bidirectional LSTM model (deep learning sequence model)  

3. Evaluation
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Visualizations: Training/Validation curves and Confusion Matrix  

---

## Results
- Both models achieved very high accuracy (~100%) on test data.  
- Confusion matrices showed near-perfect classification.  
- Note: The dataset is highly imbalanced (many more positive reviews). Further testing on unseen data is recommended.  

---

## Repository Structure
