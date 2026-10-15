# Aimal Khan

Data Engineer and Machine Learning Engineer based in Pakistan, focused on building data pipelines, weak supervision systems, and applied ML models.

[LinkedIn](https://www.linkedin.com/in/aimalkhann/) · [Email](mailto:4imalkhann@gmail.com) · [GitHub](https://github.com/aimal-khan)

---

## About

I work on machine learning systems and backend data infrastructure. My recent work centers on weak supervision from clinical text, streaming data warehouse ingestion, and model compression for low-latency inference.

Primary areas of work:
- Data engineering: streaming ETL pipelines, star schema modeling, stream-disk join algorithms, and relational database design in PostgreSQL and MySQL.
- Machine learning: multi-label medical imaging, NLP pipelines, time-series forecasting, and intrusion detection.
- Model optimization: ONNX export, INT8 quantization, and concurrent processing in Python.

---

## Featured Projects

| Project | Description | Stack | Highlights |
|:---|:---|:---|:---|
| [KneeWS](https://github.com/aimal-khan/KneeWS) | Multi-label knee abnormality detection from MRI scans using weak labels extracted from multilingual radiology reports. | PyTorch, EfficientNet-B0, NLP, Python | Calibrates noisy text labels using hierarchical empirical Bayes shrinkage. Scored 0.664 Kaggle public AUC across 12 abnormalities using 58 gold-standard studies. |
| [retail-data-warehouse-design](https://github.com/aimal-khan/retail-data-warehouse-design) | Near-real-time retail data warehouse implementing the HybridJoin algorithm for stream-disk ETL into a star schema. | Python, MySQL, SQL, Threading | Ingests streaming transaction logs using producer-consumer threads with bounded memory buffers. |
| [e-commerce-rag-engine](https://github.com/aimal-khan/e-commerce-rag-engine) | From-scratch PyTorch implementation of a multi-task transformer encoder and causal RAG decoder for review analysis. | PyTorch, NumPy, Python | Native self-attention, custom tokenization, and cosine retrieval without third-party transformer packages. |
| [MultiSocial++](https://github.com/aimal-khan/MultiSocial-Plus-Plus) | Multilingual AI-generated text detector evaluated across 18 languages, optimized for low-latency inference. | PyTorch, ONNX Runtime, Optimum, Python | 1.93x inference speedup and 75% model size reduction (1,112 MB to 279 MB) via INT8 quantization with 0.76 macro-F1. |
| [deep-learning-nids](https://github.com/aimal-khan/deep-learning-nids) | Network intrusion detection system implementing M-CNET and gradient boosted trees on security logs. | XGBoost, Scikit-learn, Python | Achieved 91% accuracy and 93.08% F1-score on the UNSW-NB15 benchmark after reducing feature dimensions by 55%. |
| [energy-demand-forecasting-ml](https://github.com/aimal-khan/energy-demand-forecasting-ml) | Electricity load forecasting pipeline evaluating gradient boosting and recurrent models on hourly consumption data. | Python, Scikit-learn, Pandas, React | Gradient boosting model reached 4.8% MAPE compared to the 8.2% baseline. |
| [relational-db-design-case-study](https://github.com/aimal-khan/relational-db-design-case-study) | Normalized 3NF relational schema for multi-vendor order fulfillment, inventory management, and transaction auditing. | PostgreSQL, SQL | Production-style DDL with foreign key integrity, index optimization, and analytical reporting queries. |

---

## Technical Skills

- Languages: Python, SQL (PostgreSQL, MySQL), Bash
- Data & Storage: PostgreSQL, MySQL, Pandas, NumPy, Star Schema Design, 3NF Normalization
- Machine Learning: PyTorch, Scikit-learn, XGBoost, ONNX Runtime, Time-Series Forecasting
- Tools: Git, Docker, Linux, Jupyter

---

## Contact

- Email: 4imalkhann@gmail.com
- LinkedIn: [linkedin.com/in/aimalkhann](https://www.linkedin.com/in/aimalkhann/)
- Location: Pakistan (Open to remote and on-site roles globally)
