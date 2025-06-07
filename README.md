# sentiment_analysis_dashboard
Streamlit dashboard for sentiment analysis using DistilBERT with emoji analysis

# 📊 Sentiment Analysis Dashboard

A comprehensive Streamlit dashboard for sentiment analysis powered by DistilBERT with advanced emoji analysis and negation handling.

## 🚀 Features

- **AI-Powered Analysis**: Uses DistilBERT for accurate sentiment classification
- **Emoji Sentiment Analysis**: Analyzes emoji sentiment separately and combines with text
- **Advanced Negation Handling**: Properly handles complex negation patterns
- **Real-time Predictions**: Interactive text input for instant sentiment analysis
- **Comprehensive Visualizations**: 
  - Sentiment distribution charts
  - Confusion matrix heatmaps
  - Performance metrics
  - Emoji impact analysis
- **Multi-tab Interface**: Organized analysis across Text, Emoji, and Combined sentiment tabs

## 🛠️ Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/sentiment-analysis-dashboard.git
cd sentiment-analysis-dashboard
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Run the application:**
```bash
streamlit run sentiment_dashboard.py
```

## 📊 Usage

1. **Upload CSV File**: Upload a CSV file with 'text' and 'sentiment' columns (or 'tweets' and 'sentiment')
2. **Real-time Analysis**: Use the text input field to analyze sentiment in real-time
3. **Explore Visualizations**: Navigate through different tabs to see various analysis results
4. **View Performance**: Check model performance with confusion matrix and classification reports

## 📁 Project Structure

```
sentiment-analysis-dashboard/
│
├── sentiment_dashboard.py    # Main Streamlit application
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
├── .gitignore             # Git ignore file
└── sample_data/           # Sample CSV files (optional)
    └── sample_tweets.csv
```

## 🔧 CSV Format

Your CSV file should have the following columns:
- `text` or `tweets`: The text content to analyze
- `sentiment`: The true sentiment labels (Positive, Negative, Neutral)

Example:
```csv
text,sentiment
"I love this product! 😍",Positive
"This is okay, nothing special",Neutral
"Terrible experience 😠",Negative
```

## 🎯 Model Features

### Text Analysis
- **DistilBERT**: Pre-trained transformer model for sentiment classification
- **Negation Handling**: Advanced detection of negation patterns
- **Context Awareness**: Handles neutral indicators and ambiguous expressions

### Emoji Analysis
- **Emoji Extraction**: Identifies and extracts emojis from text
- **Sentiment Mapping**: Maps emojis to sentiment scores
- **Combined Analysis**: Weights text and emoji sentiment for final prediction

### Performance Metrics
- Precision, Recall, F1-Score
- Confusion Matrix
- Classification Report
- Emoji Impact Analysis

## 🛡️ Requirements

- Python 3.7+
- Streamlit
- Transformers (HuggingFace)
- NLTK
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **HuggingFace Transformers** for the DistilBERT model
- **Streamlit** for the amazing web framework
- **NLTK** for natural language processing tools

## 📧 Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/sentiment-analysis-dashboard](https://github.com/yourusername/sentiment-analysis-dashboard)

---

⭐ If you found this project helpful, please give it a star!
