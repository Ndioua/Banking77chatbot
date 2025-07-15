# Banking77chatbot
# Sentiment-Aware Intent Classification on Banking77

This project explores whether automatically generated sentiment features can improve **intent classification** performance on the Banking77 dataset. It also investigates how **sentiment-adaptive response strategies** can improve user experience in chatbot systems.

## Objectives

1. **Can sentiment features improve intent classification?**
2. **How can chatbot response strategies be adjusted based on sentiment + intent?**
3. **Does sentiment help disambiguate close intent categories?**

---

## Repository Structure

├── data/
│ ├── Banking77.csv # Full labeled dataset with intents
│ ├── Banking20SampleManual.xlsx # Manual sentiment annotations (200 samples)
│ ├── intent_sentiment_responses.xlsx # Rule-based chatbot responses
│
├── notebooks/
│ ├── 1_data_loading_cleaning.ipynb # Load, preprocess, sample, and annotate data
│ ├── 2_sentiment_analysis.ipynb # FinBERT sentiment inference and validation
│ ├── 3_model_1_text_only.ipynb # DistilBERT / logistic regression (text only)
│ ├── 4_model_2_text_plus_sentiment.ipynb # Classification with sentiment feature
│ ├── 5_response_generation.ipynb # Sentiment-aware response template merging
│ ├── 6_confusion_intents_logreg.ipynb # Logistic regression for ambiguous intents
│
├── README.md # Project overview and structure

