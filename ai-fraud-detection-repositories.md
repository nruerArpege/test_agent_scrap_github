# AI-Powered Fraud Detection — Curated GitHub Repositories

A curated reference list of high-quality GitHub repositories focused on AI-powered fraud detection, covering machine learning, deep learning, graph neural networks, real-time streaming, and more. Intended for developers, researchers, and data scientists.

---

## Table of Contents

1. [Credit Card & Transaction Fraud Detection](#1-credit-card--transaction-fraud-detection)
2. [Anomaly Detection for Fraud](#2-anomaly-detection-for-fraud)
3. [Graph Neural Networks (GNN) for Fraud Detection](#3-graph-neural-networks-gnn-for-fraud-detection)
4. [Real-Time Streaming Fraud Detection](#4-real-time-streaming-fraud-detection)
5. [Anti-Money Laundering (AML) Detection](#5-anti-money-laundering-aml-detection)
6. [Insurance & Other Domain Fraud Detection](#6-insurance--other-domain-fraud-detection)
7. [Comprehensive / Multi-Model Frameworks](#7-comprehensive--multi-model-frameworks)

---

## 1. Credit Card & Transaction Fraud Detection

### fraud-detection-handbook
- **URL:** [https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook)
- **Description:** A reproducible, research-grade practical handbook for machine learning applied to credit card fraud detection. Includes a transaction data simulator and covers the full ML pipeline from data preparation to model evaluation.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Pandas
- **Fraud Type:** Credit card fraud, transaction fraud

### ml-fraud-detection
- **URL:** [https://github.com/georgymh/ml-fraud-detection](https://github.com/georgymh/ml-fraud-detection)
- **Description:** Credit card fraud detection using logistic regression, k-means clustering, and deep learning. A well-structured comparative study using the Kaggle credit card fraud dataset.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Keras, TensorFlow
- **Fraud Type:** Credit card fraud

### Transaction-Anomaly-Detection
- **URL:** [https://github.com/KuchikiRenji/Transaction-Anomaly-Detection](https://github.com/KuchikiRenji/Transaction-Anomaly-Detection)
- **Description:** Enterprise-grade fraud and AML detection pipeline combining XGBoost, LightGBM, Autoencoder, LSTM, and Transformer models. Features a real-time API, SHAP-based explainability, BI export, and a Streamlit dashboard. Compatible with the PaySim dataset.
- **Technologies:** Python, XGBoost, LightGBM, LSTM, Transformer, FastAPI, Streamlit, SHAP
- **Fraud Type:** Financial fraud, anti-money laundering, transaction anomaly detection

### online_payment_fraud
- **URL:** [https://github.com/sergio11/online_payment_fraud](https://github.com/sergio11/online_payment_fraud)
- **Description:** A proof-of-concept project for predicting fraudulent financial transactions using deep neural networks. Covers the complete pipeline: EDA, data preprocessing, model training, and evaluation on imbalanced data using SMOTE.
- **Technologies:** Python, Jupyter Notebook, TensorFlow, Keras, SMOTE
- **Fraud Type:** Online payment fraud, financial transaction fraud

### UPI_Fraud_Detection_Using_Machine_Learning
- **URL:** [https://github.com/Skismail57/UPI_Fraud_Detection_Using_Machine_Learning](https://github.com/Skismail57/UPI_Fraud_Detection_Using_Machine_Learning)
- **Description:** Advanced UPI (Unified Payments Interface) fraud detection system using machine learning and deep learning. Includes real-time transaction monitoring, multi-model ensemble detection, and an interactive visualization dashboard.
- **Technologies:** Python, Scikit-learn, Neural Networks, Real-time monitoring
- **Fraud Type:** UPI payment fraud, digital payment fraud

### FinancialFraudDetectionModels
- **URL:** [https://github.com/StrangeCoder1729/FinancialFraudDetectionModels](https://github.com/StrangeCoder1729/FinancialFraudDetectionModels)
- **Description:** Comprehensive evaluation of multiple ML and DL models for financial fraud detection, including Decision Trees, Random Forest, KNN, Logistic Regression, CNNs, and ensemble methods (bagging and boosting).
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, XGBoost, TensorFlow
- **Fraud Type:** Financial fraud, transaction fraud

### financial-fraud-detection (efedemirc)
- **URL:** [https://github.com/efedemirc/financial-fraud-detection](https://github.com/efedemirc/financial-fraud-detection)
- **Description:** AI-powered financial fraud detection system achieving 99.8% ROC-AUC using deep learning, LSTM networks, and NLP techniques on real financial datasets.
- **Technologies:** Python, PyTorch, LSTM, NLP, Deep Learning
- **Fraud Type:** Financial fraud, transaction fraud

### Fraud-Detection-with-Deep-Learning
- **URL:** [https://github.com/higorfct/Fraud-Detection-with-Deep-Learning](https://github.com/higorfct/Fraud-Detection-with-Deep-Learning)
- **Description:** Fraud detection project using neural networks with hyperparameter tuning and model evaluation. Demonstrates best practices for handling imbalanced datasets in a fraud detection context.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Neural Networks, Keras
- **Fraud Type:** Credit card fraud, transaction fraud

### Fraud-Detection-Using-Deep-Learning
- **URL:** [https://github.com/Andreusolad/Fraud-Detection-Using-Deep-Learning](https://github.com/Andreusolad/Fraud-Detection-Using-Deep-Learning)
- **Description:** Comparative study of ML and DL models for detecting fraudulent transactions in a highly imbalanced dataset with millions of rows. The best model is deployed as a web app on Hugging Face using Docker.
- **Technologies:** Python, Jupyter Notebook, Deep Learning, Docker, Hugging Face
- **Fraud Type:** Transaction fraud

### Bank-Fraud-Detection-System-using-Spark-MLlib-Random-Forest-XGBoost
- **URL:** [https://github.com/jeebanjyoti1101/Bank-Fraud-Detection-System-using-Spark-MLlib-Random-Forest-XGBoost-](https://github.com/jeebanjyoti1101/Bank-Fraud-Detection-System-using-Spark-MLlib-Random-Forest-XGBoost-)
- **Description:** Bank fraud detection system using Apache Spark MLlib for large-scale fraud identification at scale. Applies Random Forest and XGBoost on large imbalanced datasets with comprehensive evaluation metrics.
- **Technologies:** Python, Apache Spark, MLlib, Random Forest, XGBoost
- **Fraud Type:** Banking transaction fraud

---

## 2. Anomaly Detection for Fraud

### Credit-Card-Fraud-Detection-Using-Anomaly-Detection
- **URL:** [https://github.com/prathamesh693/Credit-Card-Fraud-Detection-Using-Anomaly-Detection](https://github.com/prathamesh693/Credit-Card-Fraud-Detection-Using-Anomaly-Detection)
- **Description:** Machine learning-based credit card fraud detection using unsupervised anomaly detection algorithms — Isolation Forest and One-Class SVM. Includes data preprocessing, EDA, model training, evaluation, and real-time inference.
- **Technologies:** Python, Scikit-learn, Isolation Forest, One-Class SVM
- **Fraud Type:** Credit card fraud, anomaly detection

### Deep_Learning-Self_Organizing_Map_for_fraud_detection
- **URL:** [https://github.com/mpenam/Deep_Learning-Self_Organizing_Map_for_fraud_detection](https://github.com/mpenam/Deep_Learning-Self_Organizing_Map_for_fraud_detection)
- **Description:** Unsupervised fraud detection using Self-Organizing Maps (SOM) on a credit card customer dataset. Fraud clusters are identified visually in the SOM output, and customer IDs are recovered via reverse Min-Max scaling.
- **Technologies:** Python, Jupyter Notebook, MiniSom, Unsupervised Learning
- **Fraud Type:** Credit card application fraud, anomaly detection

### Hybrid-Deep-Learning
- **URL:** [https://github.com/Vusoni/Hybrid-Deep-Learning](https://github.com/Vusoni/Hybrid-Deep-Learning)
- **Description:** Hybrid fraud detection combining unsupervised Self-Organizing Maps (SOM) to identify potential fraud with a supervised Artificial Neural Network (ANN) for refinement. Outputs ranked fraud probabilities.
- **Technologies:** Python, MiniSom, Keras, ANN, SOM
- **Fraud Type:** Credit card fraud, anomaly detection

---

## 3. Graph Neural Networks (GNN) for Fraud Detection

### DGL-Fraud-Detection
- **URL:** [https://github.com/vivek8031/DGL-Fraud-Detection](https://github.com/vivek8031/DGL-Fraud-Detection)
- **Description:** Financial fraud detection using Graph Neural Networks (GNNs) with the Deep Graph Library (DGL) and Amazon SageMaker. Uses Relational Graph Convolutional Network (R-GCN) models for multi-relational data.
- **Technologies:** Python, Jupyter Notebook, DGL (Deep Graph Library), R-GCN, Amazon SageMaker
- **Fraud Type:** Financial fraud, transaction fraud

### gnn-financial-fraud-detection
- **URL:** [https://github.com/shivkhurana/gnn-financial-fraud-detection](https://github.com/shivkhurana/gnn-financial-fraud-detection)
- **Description:** Financial fraud detection system using GNNs and PyTorch Geometric. Models transaction networks as graphs to identify money laundering rings via GraphSAGE embeddings.
- **Technologies:** Python, PyTorch Geometric, GraphSAGE, Graph Neural Networks
- **Fraud Type:** Financial fraud, money laundering

### transaction-fraud-detection
- **URL:** [https://github.com/Azvier/transaction-fraud-detection](https://github.com/Azvier/transaction-fraud-detection)
- **Description:** End-to-end ML pipeline for financial fraud detection combining extensive feature engineering with LightGBM, MLP, and a Graph Neural Network (GNN). Demonstrates multi-model approach for tabular and graph-structured financial data.
- **Technologies:** Python, Jupyter Notebook, LightGBM, MLP, Graph Neural Networks
- **Fraud Type:** Financial transaction fraud

### Graph-Neural-Network-for-Fraud-Detection
- **URL:** [https://github.com/vinaya3107/Graph-Neural-Network-for-Fraud-Detection](https://github.com/vinaya3107/Graph-Neural-Network-for-Fraud-Detection)
- **Description:** GNN-based fraud detection system using PyTorch Geometric that models financial transactions as a graph. Achieves high recall and ROC-AUC on a real-world Bitcoin transaction dataset.
- **Technologies:** Python, PyTorch Geometric, GNN, Bitcoin dataset
- **Fraud Type:** Cryptocurrency fraud, financial transaction fraud

### financial-fraud-detection-using-gnn
- **URL:** [https://github.com/karthik-0306/financial-fraud-detection-using-gnn](https://github.com/karthik-0306/financial-fraud-detection-using-gnn)
- **Description:** Graph-based fraud detection combining transaction similarity modeling with GNNs to detect rare fraud events under extreme class imbalance. Features time-aware evaluation, ranking-based metrics, and a deployment-ready inference pipeline.
- **Technologies:** Python, Jupyter Notebook, Graph Neural Networks, PyTorch
- **Fraud Type:** Financial fraud, imbalanced class detection

### GNN-Multimodal-Fraud-Detection
- **URL:** [https://github.com/iisratislam/GNN-Multimodal-Fraud-Detection](https://github.com/iisratislam/GNN-Multimodal-Fraud-Detection)
- **Description:** Research project utilizing Graph Neural Networks and multimodal data fusion for robust financial fraud detection with a focus on reducing false positives.
- **Technologies:** Python, Jupyter Notebook, GNN, Multimodal Learning
- **Fraud Type:** Financial fraud

### ChainGuard — Crypto Financial Fraud Detection
- **URL:** [https://github.com/youseihuayu-wonderful/ChainGuard-Crypto-Financial-Fraud-Detection-using-Temporal-Multi-Chain-Graph-Neural-Networks](https://github.com/youseihuayu-wonderful/ChainGuard-Crypto-Financial-Fraud-Detection-using-Temporal-Multi-Chain-Graph-Neural-Networks)
- **Description:** ChainGuard is a novel framework for cross-chain cryptocurrency fraud detection using a Temporal Multi-Chain Graph Neural Network (TM-GNN). It constructs a unified multi-chain transaction graph by modeling bridge operations as heterogeneous inter-chain edges.
- **Technologies:** Python, Temporal GNN, Multi-Chain Graph Modeling
- **Fraud Type:** Cryptocurrency fraud, cross-chain fraud

---

## 4. Real-Time Streaming Fraud Detection

### Financial-Fraud-Detection-Pipeline
- **URL:** [https://github.com/mayurjainf007/Financial-Fraud-Detection-Pipeline](https://github.com/mayurjainf007/Financial-Fraud-Detection-Pipeline)
- **Description:** Real-time credit card fraud detection using Apache Kafka, Spark Streaming, and Flask. Dynamically adapts to schema changes in the input dataset and displays results on a live web dashboard.
- **Technologies:** Python, Apache Kafka, Apache Spark Streaming, Flask
- **Fraud Type:** Credit card fraud, real-time transaction fraud

### fraud-analytics-azure-spark
- **URL:** [https://github.com/Akshay-8989/fraud-analytics-azure-spark](https://github.com/Akshay-8989/fraud-analytics-azure-spark)
- **Description:** End-to-end fraud detection ETL pipeline using Apache Spark, Kafka, and Azure Blob Storage. Combines real-time streaming and batch processing to identify suspicious transactions efficiently.
- **Technologies:** Python, Apache Spark, Apache Kafka, Azure Blob Storage
- **Fraud Type:** Financial transaction fraud

### synapse-lite
- **URL:** [https://github.com/smaranje/synapse-lite](https://github.com/smaranje/synapse-lite)
- **Description:** Modular, enterprise-grade real-time Bitcoin fraud detection system leveraging Apache Spark, Neo4j, Kafka, and Google Gemini LLM. Provides streaming analytics, graph-based fraud detection, and a professional Streamlit dashboard.
- **Technologies:** Python, Apache Spark, Neo4j, Kafka, Google Gemini LLM, Streamlit
- **Fraud Type:** Cryptocurrency fraud, real-time transaction monitoring

### Real-Time-Fraud-Detection (Znullptr)
- **URL:** [https://github.com/Znullptr/Real-Time-Fraud-Detection](https://github.com/Znullptr/Real-Time-Fraud-Detection)
- **Description:** Scalable, real-time fraud detection pipeline using Apache Spark, Kafka, Hudi, and Presto. Processes large-scale transaction data using both stream and batch processing to detect fraudulent activity efficiently.
- **Technologies:** Python, Apache Spark, Kafka, Apache Hudi, Presto
- **Fraud Type:** Financial transaction fraud, real-time anomaly detection

### Real-Time-Fraud-Detection-System (vinayp2219)
- **URL:** [https://github.com/vinayp2219/Real-Time-Fraud-Detection-System](https://github.com/vinayp2219/Real-Time-Fraud-Detection-System)
- **Description:** Real-time e-commerce fraud detection pipeline processing 500+ transactions/second using Apache Kafka, Spark Structured Streaming, an Isolation Forest ML model with a hybrid rule engine, and a live Streamlit dashboard.
- **Technologies:** Python, Apache Kafka, Spark Structured Streaming, Isolation Forest, Streamlit
- **Fraud Type:** E-commerce fraud, real-time transaction anomaly detection

### Real-Time-Fraud-Detection (MaryemElyazghi)
- **URL:** [https://github.com/MaryemElyazghi/Real-Time-Fraud-Detection](https://github.com/MaryemElyazghi/Real-Time-Fraud-Detection)
- **Description:** Real-time fraud detection system implemented in Scala using Apache Spark and Kafka. Leverages Spark Structured Streaming for real-time processing and MLlib for ML-based detection. Supports both local Docker deployment and cloud deployment on Azure.
- **Technologies:** Scala, Apache Spark MLlib, Kafka, Docker, Azure
- **Fraud Type:** Financial transaction fraud

### spark_real_time_fraud_detection
- **URL:** [https://github.com/jonaszszpoton/spark_real_time_fraud_detection](https://github.com/jonaszszpoton/spark_real_time_fraud_detection)
- **Description:** Proof-of-concept real-time fraud detection pipeline using Databricks, Apache Spark, and Confluent Cloud (Kafka). Processes streaming transaction data and identifies fraudulent payments using a Random Forest model.
- **Technologies:** Python, Jupyter Notebook, Databricks, Apache Spark, Confluent Kafka, Random Forest
- **Fraud Type:** Payment fraud, real-time detection

---

## 5. Anti-Money Laundering (AML) Detection

### Fraud-Transaction-Detection-for-Anti-Money-Laundering-Systems
- **URL:** [https://github.com/WiseGeorge/Fraud-Transaction-Detection-for-Anti-Money-Laundering-Systems](https://github.com/WiseGeorge/Fraud-Transaction-Detection-for-Anti-Money-Laundering-Systems)
- **Description:** Novel approach to fraud transaction detection for AML systems using machine learning and AI. Focuses on identifying emerging money laundering patterns, reducing false positives, and improving cybersecurity.
- **Technologies:** Python, Machine Learning, AI
- **Fraud Type:** Money laundering, financial crime

### Real-Time-Anti-Money-Laundering-AML-Detection-System
- **URL:** [https://github.com/alinapradhan/Real-Time-Anti-Money-Laundering-AML-Detection-System](https://github.com/alinapradhan/Real-Time-Anti-Money-Laundering-AML-Detection-System)
- **Description:** Comprehensive real-time AML detection system built with ML and rule-based approaches to identify suspicious financial activities, prevent fraud, and ensure regulatory compliance.
- **Technologies:** Python, Machine Learning, Rule-based Systems
- **Fraud Type:** Money laundering, suspicious financial activity

### AML-Detection-AI
- **URL:** [https://github.com/wahaj840/AML-Detection-AI](https://github.com/wahaj840/AML-Detection-AI)
- **Description:** MSc AI research project enhancing AML compliance using multiple ML and DL models including Random Forest, XGBoost, Temporal Convolutional Networks (TCN), and Attention mechanisms.
- **Technologies:** Python, Jupyter Notebook, Random Forest, XGBoost, TCN, Attention Networks
- **Fraud Type:** Money laundering, financial crime

### aml-fraud-detection-system
- **URL:** [https://github.com/eltonantony/aml-fraud-detection-system](https://github.com/eltonantony/aml-fraud-detection-system)
- **Description:** Anti-Money Laundering detection system using machine learning, served through a FastAPI backend and containerized with Docker. Includes a UI for interactive fraud risk assessment.
- **Technologies:** Python, Jupyter Notebook, FastAPI, Docker, Machine Learning
- **Fraud Type:** Money laundering

### noir-fraud-risk-intelligence
- **URL:** [https://github.com/matheuscassiano07/noir-fraud-risk-intelligence](https://github.com/matheuscassiano07/noir-fraud-risk-intelligence)
- **Description:** End-to-end ML system for AML detection, processing 6M+ financial transactions with 99.8% accuracy using Random Forest. Covers feature engineering, model training, evaluation, and risk scoring.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Random Forest
- **Fraud Type:** Money laundering, financial crime

### Anti-Money-Laundering-Risk-Detection-System
- **URL:** [https://github.com/dineshpawar01/Anti-Money-Laundering-Risk-Detection-System](https://github.com/dineshpawar01/Anti-Money-Laundering-Risk-Detection-System)
- **Description:** Flask-based web application that analyzes financial transactions using machine learning to identify suspicious activities. Assigns risk scores, generates alerts for high-risk transactions, and ensures compliance with regulatory standards.
- **Technologies:** Python, Flask, Machine Learning, Risk Scoring
- **Fraud Type:** Money laundering, regulatory compliance

### AML-Transaction-Monitoring-using-Machine-Learning
- **URL:** [https://github.com/Vickeykarthik/AML-Transaction-Monitoring-using-Machine-Learning](https://github.com/Vickeykarthik/AML-Transaction-Monitoring-using-Machine-Learning)
- **Description:** Practical AML monitoring framework combining supervised classification (with labeled data) and unsupervised anomaly detection (for unlabeled data) to detect potential money laundering activities in financial transactions.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Supervised & Unsupervised Learning
- **Fraud Type:** Money laundering, transaction monitoring

---

## 6. Insurance & Other Domain Fraud Detection

### Insurance-Fraud-Detection (Sakthi2729)
- **URL:** [https://github.com/Sakthi2729/Insurance-Fraud-Detection](https://github.com/Sakthi2729/Insurance-Fraud-Detection)
- **Description:** ML application automating insurance fraud research using XGBoost on structured and unstructured data such as claim history and policy information. Integrates NLP for text analysis to reduce manual review and false positives.
- **Technologies:** Python, XGBoost, NLP, Pandas, NumPy
- **Fraud Type:** Insurance claim fraud

### Insurance-Fraud (FarzanehHaghshenas)
- **URL:** [https://github.com/FarzanehHaghshenas/Insurance-Fraud](https://github.com/FarzanehHaghshenas/Insurance-Fraud)
- **Description:** Deep learning-based insurance fraud detection using an Artificial Neural Network (ANN). Uses k-fold cross-validation to estimate model skill and detect overfitting on insurance claim data.
- **Technologies:** Python, Keras, Scikit-learn, ANN, k-fold cross-validation
- **Fraud Type:** Insurance fraud

### Fraud_Detection (UpamaMukherjee — Auto Insurance)
- **URL:** [https://github.com/UpamaMukherjee/Fraud_Detection](https://github.com/UpamaMukherjee/Fraud_Detection)
- **Description:** Auto insurance fraud detection using structured claim data and NLP-based text analysis. Combines SMOTE, TF-IDF, Random Forest, Decision Tree, and Logistic Regression to improve fraud detection accuracy.
- **Technologies:** Python, Scikit-learn, SMOTE, TF-IDF, Random Forest
- **Fraud Type:** Auto insurance fraud

### online-recruitment-fraud-detection
- **URL:** [https://github.com/lakshmimahitha-0402/online-recruitment-fraud-detection](https://github.com/lakshmimahitha-0402/online-recruitment-fraud-detection)
- **Description:** Python-based system to detect fraudulent job postings using NLP and Deep Learning. Analyzes job advertisement text to identify fake or deceptive employment listings.
- **Technologies:** Python, NLP, Deep Learning
- **Fraud Type:** Recruitment / employment fraud

---

## 7. Comprehensive / Multi-Model Frameworks

### Optimizing-Credit-Card-Fraud-Detection-in-Banking-with-Ensemble-Learning-Techniques
- **URL:** [https://github.com/FaezehAbedi2023/Optimizing-Credit-Card-Fraud-Detection-in-Banking-with-Ensemble-Learning-Techniques](https://github.com/FaezehAbedi2023/Optimizing-Credit-Card-Fraud-Detection-in-Banking-with-Ensemble-Learning-Techniques)
- **Description:** Research project integrating ML and DL (CNN, LSTM) with hyperparameter tuning for credit card fraud detection. Demonstrates improved model adaptability through various ensemble and optimization strategies.
- **Technologies:** Python, Jupyter Notebook, CNN, LSTM, AdaBoost, SVM, Random Forest
- **Fraud Type:** Credit card banking fraud

### Fraud-Detection (tahah02 — Stacking Ensemble)
- **URL:** [https://github.com/tahah02/Fraud-Detection](https://github.com/tahah02/Fraud-Detection)
- **Description:** Banking fraud detection system using a stacking ensemble of XGBoost, Random Forest, and Logistic Regression. Learns a user's 6-month average spending (Behavioral Spending Analysis) to set dynamic thresholds and detect high-deviation suspicious transactions.
- **Technologies:** Python, XGBoost, Random Forest, Logistic Regression, Stacking Ensemble
- **Fraud Type:** Banking transaction fraud, behavioral fraud detection

### FRAUD-DETECTION-ANALYSIS-FOR-BANKS
- **URL:** [https://github.com/ivmng/FRAUD-DETECTION-ANALYSIS-FOR-BANKS](https://github.com/ivmng/FRAUD-DETECTION-ANALYSIS-FOR-BANKS)
- **Description:** Multi-language (R and Python) banking fraud detection project including data cleaning with MICE imputation, class balancing with ROSE, and comparison of multiple models: XGBoost, Random Forest, SVM, and ANN.
- **Technologies:** R, Python, XGBoost, Random Forest, SVM, ANN, MICE, ROSE
- **Fraud Type:** Banking transaction fraud

### Fraud-and-AML-Detection-Project
- **URL:** [https://github.com/Alden-Arduo/Fraud-and-AML-Detection-Project](https://github.com/Alden-Arduo/Fraud-and-AML-Detection-Project)
- **Description:** Hybrid fraud and AML detection pipeline combining supervised ML and unsupervised anomaly detection. Designed to proactively surface suspicious transactions, red flags, and emerging trends for financial institutions.
- **Technologies:** Python, Machine Learning, Anomaly Detection, Scikit-learn
- **Fraud Type:** Financial fraud, anti-money laundering

### Fighting-Money-Laundering-with-Statistics-and-Machine-Learning
- **URL:** [https://github.com/Koorabindu/Fighting-Money-Laundering-with-Statistics-and-Machine-Learning](https://github.com/Koorabindu/Fighting-Money-Laundering-with-Statistics-and-Machine-Learning)
- **Description:** AML system using ML and statistical methods to detect suspicious transactions with high accuracy. Reduced false positives, improved anomaly detection by 35%, and cut manual investigation time by 25%, supporting real-time fraud detection and regulatory compliance.
- **Technologies:** Python, Statistical Analysis, Machine Learning
- **Fraud Type:** Money laundering, banking fraud

---

## Resources & Datasets

Common datasets used across these repositories:

| Dataset | Description | Link |
|---|---|---|
| Kaggle Credit Card Fraud | 284,807 transactions, 492 frauds (0.172%), PCA-anonymized | [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) |
| PaySim | Synthetic financial transaction simulator | [GitHub](https://github.com/EdgarLopezPhD/PaySim) |
| IEEE-CIS Fraud Detection | Real-world transaction data from Vesta Corporation | [Kaggle](https://www.kaggle.com/c/ieee-fraud-detection) |
| Elliptic Bitcoin Dataset | Bitcoin transaction graph with labeled fraud nodes | [Kaggle](https://www.kaggle.com/ellipticco/elliptic-data-set) |

---

*Last updated: April 2026. Repositories are selected based on code quality, documentation, practical applicability, and relevance to AI-powered fraud detection.*
