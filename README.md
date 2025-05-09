# Hand-Written-Digit-Recognition

This project was completed as part of **STA 6366: Data Science I** at the University of Central Florida.

## Overview

Handwritten Digit Recognition (HDR) remains a classic benchmark in machine learning due to the complexity of diverse handwriting styles. This study compares two classical statistical classifiers:

- **Gaussian Naive Bayes (GNB)**
- **Linear Discriminant Analysis (LDA)**

These models are evaluated on the **MNIST dataset** to assess their effectiveness in digit classification.

## Dataset

- MNIST: 60,000 training images and 10,000 test images of handwritten digits (0–9).
- Each image: 28×28 pixels, grayscale, flattened into 784-dimensional feature vectors.

## Methods

### Gaussian Naive Bayes (GNB)
- Assumes feature independence.
- Computationally efficient.
- Prone to lower accuracy in high-dimensional correlated data.

### Linear Discriminant Analysis (LDA)
- Assumes shared covariance structure among classes.
- Captures correlations between features.
- Better at separating visually similar digits.

## Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

## Results

| Model | Accuracy |
|-------|----------|
| GNB   | 55.58%   |
| LDA   | 87.30%   |

- **LDA significantly outperforms GNB**, highlighting the importance of modeling shared feature variance in image classification tasks.


## Key Takeaways

- GNB struggles with high-dimensional, correlated input.
- LDA offers a solid, interpretable baseline for image-based classification.
- Statistical methods can still compete effectively with more complex models in HDR tasks.

## Course Info

- **Course:** STA 6366 – Data Science I  
- **Institution:** Department of Statistics and Data Science, University of Central Florida.  
- **Instructor:** [Dr. Rui Xie]  
- **Term:** [Fall 2025]

## Contact

For questions or collaborations, feel free to reach out via [GitHub Issues](https://github.com/Dipok009/Hand-Written-Digit-Recognition) or connect on [LinkedIn](https://www.linkedin.com/in/dipok-deb/).

---



