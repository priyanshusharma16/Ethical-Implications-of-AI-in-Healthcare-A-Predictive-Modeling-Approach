# Ethical AI in Healthcare: Diabetes Prediction Using SMOTE and Random Forest

This project explores how fairness techniques like SMOTE (Synthetic Minority Over-sampling Technique) can be applied in medical AI without significantly affecting model accuracy. The goal is to develop a predictive model that not only performs well but also treats both majority and minority classes fairly.

## 📌 Objective

- Develop predictive models for diabetes detection.
- Apply ethical AI methods to address class imbalance.
- Compare the performance of ethical and non-ethical models using standard evaluation metrics.

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- imbalanced-learn (SMOTE)

## 🧠 Models Used

- **Random Forest Classifier**  
  - Trained twice:
    - Without fairness (Non-Ethical Model)
    - With SMOTE applied (Ethical Model)

## 📊 Results Summary

| Model              | Accuracy | Recall (Class 1) | Comments                      |
|-------------------|----------|------------------|-------------------------------|
| Non-Ethical Model | 75.76%   | 0.66             | Slightly higher accuracy      |
| Ethical Model     | 75.32%   | 0.74             | Improved fairness for Class 1 |

- ROC curves of both models were nearly identical.
- Feature importance plots provided interpretability.

## 📈 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve

## 🔍 Key Takeaway

Ethical methods like SMOTE can reduce bias and improve fairness in healthcare AI systems without compromising performance.

## 🚀 Future Scope

- Test with other fairness techniques like re-weighting or adversarial debiasing.
- Expand to other healthcare datasets.
- Integrate privacy-preserving methods for patient data.

## 📎 License

This project is for academic and research purposes.
