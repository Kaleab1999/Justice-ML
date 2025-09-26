# Ethiopian Legal Text Classification (Amharic)

## ⚖️ Project Overview

This project implements a text classification model to analyze judicial texts in **Amharic** from Ethiopian legal documents. The goal is to classify legal fact summaries (`እውነታው`) into one of two judicial outcomes (`ዝንባሌ`):

1.  **Affirmed** (`በማለት አረጋግጠዋል`)
2.  **Reversed/Questioned** (`ተቀልብሷል/ተጠየቀ`)

The model utilizes a **Fine-Tuned XLM-RoBERTa** architecture, a powerful multilingual transformer model, for this binary classification task.

---

## 🚀 Environment Setup

This project uses Python and relies heavily on the **Hugging Face Transformers** library and **PyTorch**.

### Prerequisites

* Python (3.7+)
* CUDA-compatible GPU (Highly recommended for training)

### Installation

You can install the necessary dependencies using `pip`:

```bash
pip install pandas openpyxl numpy torch transformers matplotlib scikit-learn shap
