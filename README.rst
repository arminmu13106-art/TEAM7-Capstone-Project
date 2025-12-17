README MEMEME MEOW🐱
=======================================
## Project Overview

This project builds an end-to-end pipeline that automatically classifies a LinkedIn profile into:
1) a professional domain, and
2) a seniority level,
based on textual information from the profile.

## Pipeline

1. Data exploration and understanding of LinkedIn profile texts  
2. Text cleaning and preprocessing  
3. Feature engineering and representation learning  
4. Rule-based baseline for interpretability  
5. Embedding-based models for improved performance  
6. Model training and evaluation  


📄 FINAL_REPORT.pdf          

📄 README.md                 

📄 requirements.txt 

📂 notebooks/                # Jupyter笔记本（主要工作区）

📘 1_data_exploration.ipynb

📘 2_data_preprocessing.ipynb

📘 3_feature_engineering.ipynb

📘 4_rule_based_baseline.ipynb
# The rule-based baseline provides an interpretable reference point and helps assess the added value of more complex models.

📘 5_embedding_approach.ipynb

📘 6_model_training.ipynb

📘 7_final_evaluation.ipynb
        
    📂 src/                      # Python源代码（可重用的函数）

        📄 __init__.py

        📄 data_loader.py       # 加载数据的功能

        📄 text_cleaner.py      # 清洗文本的功能

        📄 feature_extractor.py # 提取特征的功能

        📄 model_utils.py       # 模型训练和评估工具


    📂 config/                   # 配置文件

        📄 labels.yaml          # 职业领域和资历的标签定义

    📂 data/                     # 数据文件夹（可能需要.gitignore）

        📂 raw/                 # 原始数据

        📂 processed/           # 处理后的数据

        📂 external/            # 外部数据（如SNAPADDY测试数据）


    📂 models/                   # 保存训练好的模型

        📄 domain_classifier.pkl

        📄 seniority_predictor.pkl


    📂 reports/                  # 生成的报告和图表

        📄 confusion_matrix.png

        📄 feature_importance.png

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/
