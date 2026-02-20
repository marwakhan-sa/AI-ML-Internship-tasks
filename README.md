# AI/ML Internship Tasks – DevelopersHub Corporation

This repository contains all the tasks I completed during the **AI/ML Engineering Internship** at DevelopersHub Corporation.

It includes the initial (basic) tasks from Phase 1 and the current **advanced phase** (Phase 2), where I am working on production-level ML techniques.

##  About the Internship
- Focus: From basic data exploration and simple models → advanced pipelines, transformers, LLMs, multimodal learning, and conversational AI.
- Technologies used so far: pandas, seaborn, matplotlib, scikit-learn, joblib  
- Goal: Build strong, real-world ML engineering skills and a solid portfolio.

##  Project Structure
- **phase-1-basic/** → Initial assigned tasks
- **phase-2-advanced/** → Advanced internship tasks

##  Completed Tasks

### Phase 1 – Basic Tasks

| Task # | Name                              | Objective                                                                 | Dataset                  | Model/Tool                  | Key Results / Learnings                              | Notebook Link |
|--------|-----------------------------------|---------------------------------------------------------------------------|--------------------------|-----------------------------|------------------------------------------------------|---------------|
| 1      | Iris Dataset Exploration          | Load, inspect, and visualize the Iris dataset to understand patterns     | Iris (seaborn)           | pandas, seaborn, matplotlib | Scatter plots, histograms, box plots; petal features best separate species | [Task1_Iris_Exploration.ipynb](phase-1-basic/Task1_Iris_Exploration/Task1_Iris_Exploration.ipynb) |
| 2      | Short-Term Stock Price Prediction | Predict next day's closing price using historical data                    | Apple (AAPL) stock       | Linear Regression           | Predicted vs actual time-series plot; captures general trend | [Task2_Stock_Prediction.ipynb](phase-1-basic/Task2_Stock_Prediction/Task2_Stock_Prediction.ipynb) |
| 6      | House Price Prediction            | Predict house prices based on property features                           | California Housing       | Linear Regression           | Real vs predicted prices plot; reasonable performance (MAE/RMSE reported) | [Task6_House_Price_Prediction.ipynb](phase-1-basic/Task6_House_Price_Prediction/Task6_House_Price_Prediction.ipynb) |

### Phase 2 – Advanced Tasks (DevelopersHub Advanced Internship)

| Task # | Name                                      | Objective                                                                 | Dataset / Approach                  | Technologies Used                          | Status     | Key Results / Notes                                      | Folder / Notebook |
|--------|-------------------------------------------|---------------------------------------------------------------------------|-------------------------------------|--------------------------------------------|------------|----------------------------------------------------------|-------------------|
| 1      | News Topic Classifier Using BERT          | Fine-tune BERT to classify news headlines into topics                     | AG News                             | Hugging Face Transformers, Gradio/Streamlit | Not started | —                                                        | phase-2-advanced/task1-news-classifier/ (planned) |
| 2      | End-to-End ML Pipeline – Customer Churn   | Build production-ready pipeline to predict customer churn                 | Telco Customer Churn                | scikit-learn Pipeline, GridSearchCV, joblib | **Completed** | ~80–82% accuracy; F1 ~0.58–0.64; full preprocessing, tuning, model export | [phase-2-advanced/task2-churn-pipeline/churn_prediction_pipeline.ipynb]() |
| 3      | Multimodal Housing Price Prediction       | Predict prices using tabular data + house images                          | Housing + images                    | CNNs + tabular fusion                      | Not started | —                                                        | —                 |
| 4      | Context-Aware Chatbot (RAG/LangChain)     | Build conversational bot with memory and external knowledge retrieval     | Custom corpus                       | LangChain, vector store, Streamlit         | Not started | —                                                        | —                 |
| 5      | Auto Tagging Support Tickets Using LLM    | Automatically tag support tickets with LLM (zero/few-shot + fine-tuning)  | Support tickets dataset             | Prompt engineering, LLM                    | Not started | —                                                        | phase-2-advanced/task5-llm-tagging/ (planned) |

**Task 2 – Detailed Highlights**  
- Objective: Create a reusable, production-ready ML pipeline for predicting customer churn  
- Full workflow: data cleaning → preprocessing (numerical scaling + categorical one-hot encoding) → model training (Logistic Regression & Random Forest) → hyperparameter tuning with GridSearchCV → model saving with joblib  
- Handles real-world issues: class imbalance, mixed data types, missing values  
- Saved model file: `churn_pipeline.pkl` (can be loaded to make predictions on new data)  
- First advanced task completed

## Progress & Goals
- Finished Phase 1 basics  
- Phase 2 in progress: 1/5 advanced tasks completed.  
- Next: Likely Task 5 (LLM-based ticket tagging)

Feel free to explore the notebooks! ⭐ the repo if you find it useful.
