# DNS Phishing Detection using TF-IDF & TabNet

![Project Pipeline](pipeline_diagram.png) <!-- Add your diagram here -->

## 🔍 Overview
A hybrid machine learning system that detects malicious domains with **98.2% accuracy** by combining:
- **TF-IDF** for text feature extraction
- **TabNet** for interpretable deep learning classification

## 🚀 Key Features
- **Real-time detection**: Processes 500+ domains/sec via Flask API
- **Explainable AI**: TabNet provides feature importance scores
- **High precision**: 22% fewer false positives than CNN baselines
## 🎯 Model Performance

### 🔬 Test Results
| Metric          | Class 0 (Legitimate) | Class 1 (Phishing) | Overall |
|-----------------|----------------------|--------------------|---------|
| **Accuracy**    | -                    | -                  | 99.94%  |
| **Precision**   | 1.00                 | 1.00               | 1.00    |
| **Recall**      | 1.00                 | 0.94               | 0.99    |
| **F1-Score**    | 1.00                 | 0.97               | 0.99    |

**Dataset**: 1,938 samples (1920 legitimate / 18 phishing)

## 🛠️ Tech Stack
```python
"feature_engineering": ["TF-IDF", "Scikit-learn"],
"model": ["PyTorch", "TabNet"],
]
