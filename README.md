# Fake News Detection on Social Media Content Using Deep Learning

## Introduction
The rapid spread of information through social media platforms has made it increasingly difficult to discern credible news from misinformation. The proliferation of fake news has led to widespread public confusion, undermined trust in legitimate sources, and posed significant risks to public health and safety. To address this, artificial intelligence, particularly deep learning, offers a promising solution. This project aims to develop a deep learning model to detect and filter out false information from digital platforms by analyzing textual content. This will help identify misleading information and protect the public from the adverse effects of misinformation.

## Approach

### Data Collection
The team has gathered a comprehensive dataset from various social media platforms, which serves as the foundation for model training and evaluation.

### Data Preprocessing
The collected data is meticulously cleaned and prepared for model training, ensuring that the input features are in a suitable format for the machine learning and deep learning techniques.

## Model Development
- Logistic Regression (LR) Model
- Convolutional Neural Networks (CNN)

## Model Performance

### Logistic Regression Performance
- **Accuracy:** 83.26%
- **Precision for Class 0 (Real):** 0.71
- **Precision for Class 1 (Fake):** 0.86
- **Recall for Class 0:** 0.52
- **Recall for Class 1:** 0.93
- **F1-Score for Class 0:** 0.60
- **F1-Score for Class 1:** 0.89

This classification report provides a detailed breakdown of the model's performance, indicating its capability to distinguish between real and fake news effectively. The high precision and recall for Class 1 highlight the model's proficiency in identifying fake news.

### CNN Model Performance
**Epoch Results:**
- **Epoch 10/10:**
  - Loss: 0.0090
  - Accuracy: 0.9972
  - Validation Loss: 0.9461
  - Validation Accuracy: 0.7967

**Final Evaluation Metrics:**
- **Precision:**
  - Fake: 0.94
  - Real: 0.99
- **Recall:**
  - Fake: 0.95
  - Real: 0.98
- **F1-Score:**
  - Fake: 0.95
  - Real: 0.98
- **Support:**
  - Fake: 1461
  - Real: 4539
- **Overall Accuracy:** 97%
The <b>Convolutional Neural Network (CNN)</b> stands out as the best-performing model based on performance metrics in detecting fake news.

## Future Scope
- **Model Enhancements**
  - Ensemble methods
  - Transfer learning
  - Regular updates and maintenance
  - Model retraining
  - Algorithm optimization
- **Ethical Considerations**
  - Bias mitigation
  - Privacy and security
- **Scalability and Deployment**
  - Scalable solutions
  - Cloud integration

