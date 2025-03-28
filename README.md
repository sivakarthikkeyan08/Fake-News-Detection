# Fake News Detection

## Overview
Fake news has become a major issue in the digital age, influencing public opinion and spreading misinformation. This project implements a **Fake News Detection System** using **Machine Learning** techniques. It classifies news articles as either **Real** or **Fake** using **Natural Language Processing (NLP)** and machine learning models.

## Features
- Preprocessing of text data (stopword removal, tokenization, cleaning)
- Feature extraction using **TF-IDF Vectorization**
- Machine learning models: **Logistic Regression** and **Decision Tree**
- Accuracy evaluation of models
- Manual testing by inputting custom news articles

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib & Seaborn
- TfidfVectorizer

## Dataset
The dataset consists of two files:
- **True.csv** – Contains real news articles.
- **Fake.csv** – Contains fake news articles.

Each dataset includes:
- `title`: Headline of the article (removed in preprocessing)
- `text`: News content (used for analysis)
- `subject`: Category of the news (removed in preprocessing)
- `date`: Published date (removed in preprocessing)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download necessary NLTK resources:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```
4. Run the model:
   ```bash
   python fake_news_detection.py
   ```

## Usage
1. The script loads and preprocesses the dataset.
2. It trains two models: **Logistic Regression** and **Decision Tree**.
3. It evaluates the models and prints their accuracy.
4. You can manually test the model by entering custom news articles.

Example:
```bash
Enter news text: "Breaking: Scientists discover a new cure for cancer!"
Output: "Real News"
```

## Future Enhancements
- Implement a **web-based UI** for easier interaction.
- Use **Deep Learning models (LSTMs, Transformers)** for better accuracy.
- Integrate **real-time news scraping** for live detection.

## Contributors
- **Sivakarthikkeyan**
- **Sriram**
- **Sivasanjay**
- **Shakgeendan**

## License
This project is licensed under the MIT License.

