# Sentiment-Analysis-on-Bengali-Text
This project focuses on developing a deep learning-based sentiment analysis system for Bengali text. Given the scarcity of resources in this language, the study compares CNN, RNN, and LSTM models for text classification.

🧠 Objectives

Classify Bengali text into sentiment categories.

Explore the effectiveness of deep learning on a low-resource language.

Compare deep learning with traditional machine learning methods.

📝 Dataset

Bengali comments labeled with sentiment categories.

Preprocessing included: removing non-Bengali characters, tokenization, stopword removal, and stemming.

⚙️ Methodology

Feature Extraction:

TF-IDF

Bag of Words (BoW)

Models Used:

Logistic Regression (baseline): Accuracy: 0.4174

CNN: Accuracy: 0.3107

RNN: Accuracy: 0.2718

LSTM: Accuracy: 0.1650 (training issue encountered)

Evaluation:

Deep learning models underperformed due to data limitations and training instability.

💡 Technologies

Python

scikit-learn

TensorFlow/Keras

bnlp, bangla-stemmer

📈 Conclusion

Logistic regression outperformed deep learning models for this Bengali sentiment analysis task, emphasizing the challenges of working with limited data and low-resource languages. Further improvements are needed in model design and training techniques.
