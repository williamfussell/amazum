# AMASUM
---
**AMASUM** is a protype of an innovative tool designed to tackle the challenge of analyzing and summarizing vast amounts of customer reviews on e-commerce platforms. Utilizing state-of-the-art open source solutions, it transforms extensive customer feedback into clear, actionable insights for businesses and consumers. 

This project is backed by the ethos of creating individual proprietary AI language models for businesses, emphasizing data democratization, privacy, and efficient ROI. AMASUM is not just a solution for today's e-commerce analytics but a step towards personalized AI tools for diverse business needs, marking a stride in digital innovation and commerce.


## Getting Started
---
The notebooks in this repo can be used with other customer review style datasets of course, but there will need to be some re-processing if you do so. For best results you can use the link below that contains the appropriate data to follow along in this notebook.
https://www.kaggle.com/datasets/williamfussell/amasum-data/data

**AMASUM**, at its core is built from fine-tuning **Llama 2(Meta AI’s open source state-of-the-art LLM)**
You will need to set up a huggingface account and request access from **META AI** for use of the Llama2 Model.
Follow these links to do so:
https://huggingface.co/
https://ai.meta.com/resources/models-and-libraries/llama-downloads/

### Prerequisites
Please use the **requirements.txt when creating the environment for the following **Notebooks**:
- **baseline_summary_1.ipynb**
- **final_dataset_eda_processing.ipynb**
- **model_evaluation.ipynb**
- **reference_summary_generator.py**

Please use the **colab_requirements.txt when creating the environment for the following **Notebooks**:
- **amasum_positive_model.ipynb**
- **amasum_negative_model.ipynb**
- **amasum_app.ipynb**

## Guide to AMASUM Code
---
Complete the notebooks in this order for best results:

- **final_dataset_eda_processing.ipynb**
- **reference_summary_generator.py**
- **baseline_summary_1.ipynb**

These were made in google colab with a **NVIDIA A100 GPU**:
- **amasum_positive_model.ipynb**
- **amasum_negative_model.ipynb**
- **model_evaluation.ipynb**
- **amasum_app.ipynb**

If you want to expand the datasets, use larger models, or create larger batch sizes and token lengths I would recommend moving to a more scalable cloud solution like **AWS** or **GCP**.

## Citations
The data **AMASUM** is built on comes form the courtesy of the following researchers at UCSD:

Justifying recommendations using distantly-labeled reviews and fined-grained aspects:

Jianmo Ni, Jiacheng Li, Julian McAuley
Empirical Methods in Natural Language Processing (EMNLP), 2019





