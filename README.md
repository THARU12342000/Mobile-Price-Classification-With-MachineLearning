📱 Mobile Price Classification
🏷 Project Overview
In today’s competitive smartphone market, determining the right price for a mobile phone is essential for manufacturers and consumers. This project aims to build a machine learning model to classify mobile phones into different price ranges based on their technical features.

By analyzing features such as battery power, clock speed, internal memory, and mobile weight, we leverage machine learning techniques to help manufacturers make informed pricing and product decisions, while also assisting consumers in choosing the right product for their needs.

📊 Dataset
Dataset Name: Mobile Price Classification

Source: Kaggle
Features Used:
Battery Power
Clock Speed
Internal Memory
Mobile Weight
🧠 Machine Learning Models
1️⃣ Random Forest
Training Accuracy: 100%
Testing Accuracy: 92.25%
Key Insights:
High training accuracy indicates the model captures the dataset patterns well.
Slight overfitting observed as the test accuracy is ~8% lower than training accuracy.
Struggles slightly with Class 2 predictions.
2️⃣ Support Vector Machine (SVM)
Training Accuracy: 97.69%
Testing Accuracy: 96.75%
Key Insights:
Balanced performance across all classes.
Minimal difference between training and testing accuracy, indicating good generalization.
Model is well-suited for deployment.
📈 Conclusion
Random Forest: Excellent training accuracy but requires fine-tuning to improve performance for Class 2.
SVM: Balanced and well-generalized performance, making it deployment-ready.
Both models demonstrate the power of machine learning in classifying mobile price ranges effectively.

🚀 Repository Contents
notebooks/
Jupyter notebooks for data analysis and model training.
models/
Saved models for Random Forest and SVM.
src/
Source code for preprocessing, feature engineering, and training pipelines.
data/
Preprocessed dataset files.
🛠 Technologies Used
Programming Language: Python
Libraries:
Pandas, NumPy (Data Analysis)
Scikit-learn (Machine Learning)
Matplotlib, Seaborn (Visualization)
📂 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/mobile-price-classification.git
