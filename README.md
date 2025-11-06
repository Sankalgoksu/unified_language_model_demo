## Project Overview

This project demonstrates a unified NLP pipeline capable of:
- Summarizing English text
- Translating the summary into Italian
- Performing sentiment analysis on the summary

It was built with Hugging Face Transformers and designed to run on Google Colab.  
The goal was to integrate multiple language models into a single workflow.



# Unified Language Model Demo

This project demonstrates a unified language model pipeline that performs three tasks using state-of-the-art transformer models:

1. Summarization (English)  
2. Translation (English → Italian)  
3. Sentiment Analysis

---

## Overview

The script allows the user to input any English text.  
It will:
- Generate a concise summary using a T5 model  
- Translate the summary into Italian  
- Classify the sentiment (positive/negative/neutral)

---

## How to Run

### Option 1: Run on Google Colab
1. Copy the code from `unified_language_model_demo.py`
2. Paste it into a new Colab notebook cell
3. Uncomment the installation line:

```python
!pip install transformers datasets accelerate
