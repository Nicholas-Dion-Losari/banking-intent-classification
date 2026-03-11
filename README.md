# 🏦 Classifying Banking Intent from Customer Queries

**Objective:** To predict customer intent from real-world banking queries by comparing the performance and training efficiency of a baseline Multi-Layer Perceptron (MLP) against a fine-tuned Large Language Model (RoBERTa using LoRA).

## 🗂️ Project Structure
* `banking_classification_BERT.ipynb`: The main Jupyter Notebook containing the end-to-end AI workflow.
* `datasets/`: Contains the `banking77` train and test CSV files.
* `requirements.txt`: Python dependencies required to reproduce this environment.

## 🛠️ Tools & Technologies
* **Deep Learning Framework:** PyTorch
* **Transformers:** Hugging Face `transformers`, `peft` (LoRA)
* **Data Processing:** Pandas, Scikit-learn
* **Visualization:** Matplotlib, Seaborn

## 🚀 Methodology (CRISP-DM)
1. **Business Understanding:** Automating customer service routing to reduce response times.
2. **Data Understanding & Preparation:** Exploring the 77-category dataset and tokenizing text.
3. **Modeling:** Training a TF-IDF Baseline MLP and fine-tuning `roberta-base`.
4. **Evaluation:** Comparing models based on F1-Score, Precision, Recall, and computational efficiency.

*Project results and evaluation metrics will be updated here as the models are trained.*
