📱 Mobile Price Classification

🌟 Overview

This project uses Machine Learning to classify mobile phones into four price ranges:

0: Low-cost
1: Medium-cost
2: High-cost
3: Very high-cost

By analyzing features like battery power, RAM, and screen resolution, we aim to help manufacturers position products competitively and assist consumers in making informed decisions.

📊 Dataset

The dataset, sourced from Kaggle, includes:
2000 entries with 20 features (e.g., battery power, camera, connectivity options).
Target variable: price_range.

🧠 Models and Results

Random Forest:
Training accuracy: 100%
Testing accuracy: 92.25% (minor overfitting detected).

Support Vector Machine (SVM):
Training accuracy: 97.69%
Testing accuracy: 96.75% (robust and well-balanced).

Conclusion: SVM is the recommended model due to its consistent performance across all classes.

🛠️ Applications

For Manufacturers: Optimize pricing and feature design.
For Consumers: Empower decision-making based on specifications.

📚 References

Dataset: Mobile Price Classification
