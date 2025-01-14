# 🎭 Emotion Detection in Text Using NLTK

This project demonstrates **emotion detection in text** using Python's **Natural Language Toolkit (NLTK)** and the **VADER (Valence Aware Dictionary and sEntiment Reasoner)** sentiment analysis tool. 🚀

---

## ✨ Features

- **Sentiment Analysis** 📊:
  - Analyzes text for positive, negative, neutral, and compound sentiment scores.
- **Emotion Classification** 🎭:
  - Maps sentiment scores to emotions like Joy, Sadness, Anger, Neutral, or Mixed Emotions.
- **Customizable Text Input** 📝:
  - Allows users to test different sentences and detect their corresponding emotions.

---

## 🛠️ Technologies Used

- **Python** 🐍: Core programming language.
- **NLTK**: Natural Language Toolkit for sentiment analysis and text preprocessing.

---

## 🚀 How It Works

1. **Input Text**:
   - Provide a sentence or paragraph for emotion detection.

2. **Sentiment Analysis**:
   - VADER analyzes the text to calculate sentiment scores:
     - **Positive (pos)**, **Negative (neg)**, **Neutral (neu)**, and **Compound**.

3. **Emotion Classification**:
   - Based on the sentiment scores:
     - **Joy**: Compound score >= 0.5.
     - **Sadness**: Compound score <= -0.5.
     - **Anger**: Negative score > 0.5.
     - **Neutral**: Neutral score > 0.7.
     - **Mixed Emotions**: Any other cases.

4. **Output**:
   - Displays the sentiment scores and the detected emotion.

---

## 📂 File Structure

```
DetectEmotionInText/
├── DetectEmotionInText.py      # Main script for emotion detection
├── README.md                   # Project documentation
```

---

## ⚙️ Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tanish141/DetectEmotionInText.git
   cd DetectEmotionInText
   ```

2. **Create a Virtual Environment (Optional)**:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install nltk
   ```

4. **Download NLTK Data**:
   Run the following commands in Python to download required NLTK packages:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

5. **Run the Script**:
   ```bash
   python DetectEmotionInText.py
   ```

---

## 🖥️ Example Usage

### Input:
```plaintext
I am so happy today! The weather is beautiful, and everything is going well. I feel very positive and motivated!
```

### Output:
```plaintext
Sentiment Scores: {'neg': 0.0, 'neu': 0.423, 'pos': 0.577, 'compound': 0.9567}
Detected Emotion: Joy
```

---

## 🌟 Key Learning Outcomes

- How to use VADER for sentiment analysis.
- Mapping sentiment scores to emotions for human-like text interpretation.
- Working with NLTK libraries for text analysis.

---

## 🤝 Contributions

Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project. ✨

---

## 📧 Contact

- **Email**: mrtanish14@gmail.com
- **GitHub**: https://github.com/Tanish141

---

🎉 **Happy Emotion Detection!**

