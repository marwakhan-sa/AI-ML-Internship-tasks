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

| Task # | Name                              | Objective                                                                 | Dataset                  | Model/Tool                  | Key Results / Learnings                              |
|--------|-----------------------------------|---------------------------------------------------------------------------|--------------------------|-----------------------------|------------------------------------------------------|
| 1      | Iris Dataset Exploration          | Load, inspect, visualize Iris dataset                                     | Iris (seaborn)           | pandas, seaborn, matplotlib | Petal features best separate species                 |
| 2      | Short-Term Stock Price Prediction | Predict next day's closing price                                          | Apple (AAPL) stock       | Linear Regression           | Captures general trend (hard to predict stocks)      |
| 6      | House Price Prediction            | Predict house prices based on features                                    | California Housing       | Linear Regression           | Reasonable performance (MAE/RMSE reported)           |

### Phase 2 – Advanced Tasks

| Task # | Name                                      | Objective                                                                 | Dataset                  | Technologies Used                          | Status     | Key Results / Notes                                      |
|--------|-------------------------------------------|---------------------------------------------------------------------------|--------------------------|--------------------------------------------|------------|----------------------------------------------------------|
| 1      | News Topic Classifier Using BERT          | Fine-tune DistilBERT to classify news into 4 topics                       | AG News                  | Hugging Face Transformers, Gradio          | Completed  | ~89% accuracy on test set (1 epoch, 8k subset)           |
| 2      | End-to-End ML Pipeline – Customer Churn   | Build production-ready pipeline to predict customer churn                 | Telco Customer Churn     | scikit-learn Pipeline, GridSearchCV, joblib | Completed  | ~80–82% accuracy; F1 ~0.58–0.64                          |

**Task 1 – News Topic Classifier – Detailed Highlights**  
- Model: `distilbert-base-uncased` (lighter & faster than bert-base)  
- Workflow: Data download → text combine → tokenization → fine-tuning with Trainer → Gradio demo  
- Training: 1 epoch on 8,000-sample subset (Colab GPU)  
- Evaluation: Accuracy ~89%, good balance of speed and performance  
- Deployment: Live Gradio interface (temporary Colab link; permanent deployment recommended via Hugging Face Spaces)  
- Notebook: phase-2-advanced/task1-news-classifier/Task1-News-Topic-Classifier-DistilBERT.ipynb  
- Saved model: `./fine_tuned_distilbert_agnews`

**Task 2 – End-to-End ML Pipeline – Highlights**  
- Full pipeline: cleaning → preprocessing → Logistic Regression + Random Forest → tuning → joblib export  
- Notebook: phase-2-advanced/task2-churn-pipeline/churn_prediction_pipeline.ipynb  
- Saved model: `churn_pipeline.pkl`

## Progress & Goals
- Phase 1 completed  
- Phase 2: 2/5 advanced tasks done  

Feel free to explore the notebooks! ⭐ the repo if useful.

Made by **Marwa**  
