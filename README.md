Fake News Detection 📰🚀
📌 Project Objective
The goal of this project is to build a Fake News Detection system using machine learning algorithms without using NLP-based techniques. The model predicts whether a news article is Fake or Real based on statistical and metadata-based features such as word count, punctuation frequency, and other structured data attributes.

🛠️ Techniques & Methodologies Used
This project uses Supervised Machine Learning algorithms to classify news articles. Instead of NLP-based approaches like TF-IDF or word embeddings, we focus on structured numerical features extracted from the news content.

Data Preprocessing

Extracting metadata-based features (word count, punctuation count, uppercase words, etc.)
Encoding categorical variables
Machine Learning Models Used

Random Forest Classifier
Logistic Regression
Linear Regression (for experimentation)
Gradient Boosting (XGBoost, LightGBM)
Model Evaluation Metrics

Accuracy
Precision & Recall
F1 Score
🔗 Dataset
Since CSV files are large, they are stored in Google Drive and accessed directly using Pandas.

Fake News Data: Fake.csv
Real News Data: True.csv
Manual Testing Data: Manual_Testing.csv
⚙️ Tools & Technologies Used
Programming Language: Python 🐍
Libraries Used:
Pandas - Data Handling
NumPy - Numerical Computation
Scikit-Learn - Machine Learning Models
Matplotlib & Seaborn - Data Visualization

📌 Future Enhancements
Integrate with a web application for real-time detection
Improve dataset with additional metadata
