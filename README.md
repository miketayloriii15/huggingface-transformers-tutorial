# Hugging Face Transformers Tutorial

This repository contains a hands-on tutorial exploring [Hugging Face Transformers](https://huggingface.co/transformers/) for natural language processing (NLP) tasks. The notebook walks through installing dependencies, loading pretrained models, fine-tuning, and saving models locally.

## Contents
- `huggingface_transformers.ipynb` – Jupyter Notebook with step-by-step code and notes
- Example code for:
  - Installing and importing Hugging Face Transformers
  - Using pretrained models and tokenizers
  - Fine-tuning models on sample data
  - Saving and loading models
- Notes and explanations from my Data Analyst Bootcamp project

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/huggingface-transformers-tutorial.git
cd huggingface-transformers-tutorial

2. Create a Conda environment
conda env create -f environment.yml
conda activate llms_course_env


If you don’t want to use Conda, you can install dependencies with pip:

pip install transformers datasets torch jupyter

3. Launch Jupyter Lab / Notebook
jupyter lab


Open huggingface_transformers.ipynb to run the examples.

Requirements

Python 3.8+

Transformers

Datasets

PyTorch

Notes

Model weights are not included in this repo.

Add large files like saved models or checkpoints to .gitignore. Example:

my_saved_models/

License

This project is open source and available under the MIT License
.


---

👉 Want me to also create a matching **`environment.yml`** file for Conda, so people can spin up your notebook in one step?
