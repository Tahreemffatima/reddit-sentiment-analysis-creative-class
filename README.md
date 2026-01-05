# Reddit Sentiment Analysis: Creative Class Response to Global Events

A quantitative analysis examining how the creative class responds to major global events through sentiment analysis and engagement dynamics on Reddit.

## 📋 Project Overview

This research investigates sentiment and engagement patterns in art-related subreddits (/Art, /Music, /Europe, /News) surrounding three critical global events:
- **Russia-Ukraine War** (2022-2023)
- **Climate Change** (2005-2023)
- **Hong Kong Protests** (2019-2022)

**Author:** Tahreem Fatima
**Institution:** Middlesex University  
**Program:** MSc Data Science (Distinction)  


## 🔍 Methodology

1. **Data Collection**: 2.64TB Reddit dataset from Academic Torrents (40,000 subreddits, 2005-2023)
2. **Data Preprocessing**: Cleaning, filtering using BERT embeddings and cosine similarity
3. **Text Classification**: LLaMA 3-8B for topic classification (91-95% accuracy)
4. **Sentiment Analysis**: VADER for sentiment scoring
5. **Emotion Detection**: DistilBERT-based emotion classification
6. **Topic Modeling**: BERTopic for thematic analysis

## 🔑 Key Findings

### Russia-Ukraine War
- **Pro-Russia posts** had highest engagement despite lower frequency
- Negative sentiment and **anger** were primary engagement drivers
- 91% classification accuracy

### Climate Change  
- Growing **frustration** with increasing anger and sadness over time
- Pro-Climate Change posts showed highest engagement
- Focus on renewable energy, policy critique, and climate activism

### Hong Kong Protests
- Strong support for **pro-democracy** movements
- Positive sentiment in Pro-HK Protest posts most engaging
- Discussions centered on freedom of speech and government influence

## 📁 Repository Structure
```
├── Final_EU.ipynb                      # Main analysis notebook (Europe subreddit)
├── Llama_3_Sentiment_Analysis.ipynb    # LLaMA 3 classification implementation
├── Climate_Change.ipynb                # Climate change analysis
├── RU_War_Sentiment.ipynb             # Russia-Ukraine war analysis
├── Art_Sudreddit.ipynb                # Art subreddit analysis
├── requirements.txt                    # Python dependencies
└── README.md                          # This file
```

## 🛠️ Technologies Used

- **Python 3.10+**
- **LLaMA 3-8B**: Text classification
- **BERT & DistilBERT**: Embeddings and emotion detection
- **VADER**: Sentiment analysis
- **BERTopic**: Topic modeling
- **Libraries**: transformers, torch, pandas, numpy, altair, scikit-learn

## 📊 Results Summary

- **Overall Accuracy**: 91-95% for text classification
- **Engagement Correlation**: 0.63-0.75 between scores and comments
- **Primary Emotions**: Anger, sadness, fear across all topics
- **Key Insight**: Emotionally charged content drives significantly higher engagement

## 🚀 Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Running the Notebooks
Each notebook is self-contained and can be run independently:
- Open in Google Colab or Jupyter Notebook
- Ensure GPU runtime for LLaMA 3 classification
- Follow cell-by-cell execution

## ⚠️ Important Notes

- Notebooks contain **cell outputs cleared** to remove API tokens
- Original data source: [Academic Torrents Reddit Dataset](https://academictorrents.com/details/56aa49f9653ba545f48df2e33679f014d2829c10)
- Processing requires significant computational resources (T4 GPU, 15GB VRAM recommended)

## 📝 Citation
```
Fatima, T. (2024). Quantitative Analysis of How the Creative Class Responds to Global Events 
by Examining Discussions and Sentiments in Art-related Subreddits. 
```

## 📧 Contact

For questions or collaboration:
- **Email**: tahreem.ffatima@gmail.com

## 📄 License

This project is for academic purposes. Please cite appropriately if using this work.

---

**Keywords**: Sentiment Analysis, NLP, LLaMA 3, Reddit Analysis, Social Media Analytics, Creative Class, BERT, Topic Modeling
