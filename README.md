# AI/ML Internship Tasks – DevelopersHub Corporation

This repository contains all tasks completed during the **AI/ML Engineering Internship** at DevelopersHub Corporation.
It includes Phase 1 (basic tasks) and Phase 2 (advanced tasks – at least 3 required).

## About the Internship
- Focus: From basic data exploration → advanced ML pipelines, transformers, LLMs, multimodal, conversational AI
- Technologies used: pandas, scikit-learn, Hugging Face Transformers, Gradio, joblib
- Goal: Build real-world ML engineering skills and portfolio

## Project Structure
- **phase-1-basic/** → Initial tasks
- **phase-2-advanced/** → Advanced tasks

## Completed Tasks

### Phase 1 – Basic Tasks

| Task # | Name | Objective | Dataset | Model/Tool | Key Results / Learnings |
|--------|-----------------------------------|---------------------------------------------------------------------------|--------------------------|-----------------------------|------------------------------------------------------|
| 1 | Iris Dataset Exploration | Load, inspect, visualize Iris dataset | Iris (seaborn) | pandas, seaborn, matplotlib | Petal features best separate species |
| 2 | Short-Term Stock Price Prediction | Predict next day's closing price | Apple (AAPL) stock | Linear Regression | Captures general trend (hard to predict stocks) |
| 6 | House Price Prediction | Predict house prices based on features | California Housing | Linear Regression | Reasonable performance (MAE/RMSE reported) |

### Phase 2 – Advanced Tasks

| Task # | Name | Objective | Dataset | Technologies Used | Status | Key Results / Notes |
|--------|-------------------------------------------|---------------------------------------------------------------------------|--------------------------|--------------------------------------------|------------|----------------------------------------------------------|
| 1 | News Topic Classifier Using BERT | Fine-tune DistilBERT to classify news into 4 topics | AG News | Hugging Face Transformers, Gradio | Completed | ~89% accuracy on test set (1 epoch, 8k subset) |
| 2 | End-to-End ML Pipeline – Customer Churn | Build production-ready pipeline to predict customer churn | Telco Customer Churn | scikit-learn Pipeline, GridSearchCV, joblib | Completed | ~80–82% accuracy; F1 ~0.58–0.64 |
| 5 | Auto Tagging Support Tickets Using LLM | Zero-shot & few-shot tagging of support tickets | Customer Support Tickets | Groq API, Llama-3.1, prompt engineering | Completed | Zero-shot: 17.0%, Few-shot: [5.0]% – few-shot clearly better |

- Security note: Real API key removed before upload (dummy key used) in the task 5.

Feel free to explore the notebooks! ⭐ the repo if useful.
