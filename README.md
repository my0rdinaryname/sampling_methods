# Sampling Assignment – Credit Card Dataset

## Objective
To study the effect of different sampling techniques on imbalanced data and analyze their impact on the accuracy of various machine learning models.

## Dataset
Credit card transaction dataset with a highly imbalanced target class.

## Sampling Techniques Used
1. Random Over Sampling
2. SMOTE
3. Random Under Sampling
4. SMOTE + Tomek Links
5. No Sampling (Original Data)

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- Support Vector Machine

## Results
Accuracy results are stored in `results.csv`.

## Observations
- Oversampling techniques like SMOTE generally perform better.
- Tree-based models are less sensitive to imbalance.
- SVM performs poorly without proper sampling.

## Conclusion
Sampling techniques significantly affect model performance on imbalanced datasets. SMOTE combined with ensemble models yielded the best results.

## How to Run
```bash
pip install -r requirements.txt
python sampling_assignment.py
