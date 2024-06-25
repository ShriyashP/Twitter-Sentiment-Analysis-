# Twitter Data Analysis Project

Overview

This project focuses on sentiment analysis of Twitter data to detect hate speech and classify sentiments expressed in tweets. The dataset includes 31,962 tweets, and the project aims to preprocess, clean, analyze, and visualize these tweets using advanced NLP techniques.

Features
- Preprocessing and Cleaning: Removed noise (Twitter handles, punctuation, special characters) to enhance data quality.
- Feature Extraction: Utilized Bag-of-Words and TF-IDF methods to convert text data into numerical features.
- Sentiment Analysis: Applied NLP techniques to classify tweets and detect hate speech, improving accuracy by 25%.

 Tools and Technologies

- Programming Languages and Libraries: Python, NLTK, TensorFlow, Scikit-learn, Pandas
- Machine Learning Models: Linear Support Vector Classification (LinearSVC)
- Text Processing Techniques: Tokenization, Stemming, Bag-of-Words, TF-IDF
- Data Visualization: WordCloud
- Development Environment: Google Colab

 Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks with code for preprocessing, feature extraction, and modeling.
- `scripts/`: Python scripts for data processing and model training.
- `results/`: Output files and visualizations.

 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/twitter-data-analysis.git
   cd twitter-data-analysis
   ```
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```


 Results

- Achieved a 25% improvement in sentiment analysis accuracy.
- Successfully detected hate speech with increased model performance.
- F1-Score: 74.80%

 License

This project is licensed under the MIT License.
