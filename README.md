🩺 Diabetes Data Validation with TFDV
Welcome to Diabetes Data Validation with TFDV – a hands-on MLOps project designed to help you master the art of data validation for machine learning pipelines. This project leverages TensorFlow Data Validation (TFDV), an open-source library that empowers you to understand, validate, and monitor ML data at scale.

🚀 Project Overview
In this project, you'll work with the Diabetes 130-US hospitals for years 1999-2008 dataset, a rich clinical dataset representing a decade of patient care across 130 US hospitals. Your mission: ensure the data quality, consistency, and reliability required for robust machine learning models.

You'll learn to:

Generate and visualize statistics from real-world clinical data

Infer and evolve data schemas

Detect, visualize, and fix anomalies

Monitor for data drift and skew across different ML pipeline stages

🧰 Features
Automated Data Statistics: Instantly compute and visualize feature statistics for any dataset split.

Schema Inference & Validation: Auto-generate schemas and enforce data consistency across training, evaluation, and serving sets.

Anomaly Detection: Identify missing values, unexpected categories, and feature distribution changes.

Data Drift & Skew Analysis: Compare datasets to catch subtle shifts that could silently degrade model performance.

Slice-Based Insights: Drill down into data slices for granular validation and monitoring.

🏥 Dataset
Source: UCI ML Repository – Diabetes 130-US hospitals

Rows: 10+ years of clinical records

Features: 50+ attributes including demographics, diagnoses, treatments, and outcomes

📖 Workflow
Setup & Imports: Load essential Python and TFDV libraries.

Load & Split Data: Ingest the diabetes dataset, split into training, evaluation, and serving sets.

Generate & Visualize Statistics: Use TFDV to compute and visualize feature distributions.

Infer Data Schema: Automatically infer a schema from the training set.

Detect & Fix Anomalies: Compare evaluation/serving data to the schema, identify issues, and update the schema.

Monitor Drift & Skew: Check for distribution changes between splits.

Slice Analysis: Analyze data quality for specific cohorts or feature slices.

Freeze Schema: Lock down the schema for production deployment.

🧪 Example: What You’ll Detect
Unexpected String Values: E.g., new medical specialties appearing in evaluation data.

Domain Violations: E.g., drug dosage values outside the allowed set.

Missing Columns: E.g., label column dropped in serving data.

Data Drift: E.g., patient age distribution shifts between training and serving.

🛠️ Getting Started
python
# Install dependencies
pip install tensorflow tensorflow-data-validation pandas

# Clone this repo and run the notebook
jupyter notebook C2W1_Assignment.ipynb
📝 Project Structure
C2W1_Assignment.ipynb – Main notebook with step-by-step instructions and code

dataset_diabetes/diabetic_data.csv – The dataset (already included)

README.md – You’re reading it!

🌟 Why TFDV?
“Without data validation, your ML pipeline is only as reliable as your messiest input.”

TFDV brings automation, transparency, and confidence to the data that powers your models.

👩‍⚕️ Who is this for?
ML Engineers and Data Scientists building production ML pipelines

MLOps practitioners seeking robust data validation workflows

Anyone working with healthcare or tabular datasets

🤝 Contributing
Found a bug, or want to add a new validation feature? Pull requests welcome!

Let’s make your ML data healthy, one validation at a time.

Happy validating!

Related
What are some uniq
