# Sentence Transformer and Multi-Task Learning Model

## Overview

This repository contains the implementation of a **Sentence Transformer** and its extension into a **Multi-Task Learning Model**. The tasks include:

- **Task A**: Sentence classification.
- **Task B**: An additional NLP task (e.g., Named Entity Recognition or Sentiment Analysis).

The code is written in Python using the Hugging Face `transformers` library and executed in a Jupyter Notebook.

## Repository Contents

- **Sentence_Transformer_MultiTask.ipynb**: Jupyter Notebook with the implementation and discussion responses.
- **requirements.txt**: List of dependencies required to run the notebook.

## How to Run the Notebook

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/sentence-transformer-multitask.git

2. Install the dependencies:

 ```bash
 pip install -r requirements.txt

3. Open the Jupyter Notebook: You can open the notebook locally or upload it to Google Colab:
- To run locally:
```bash
jupyter notebook Sentence_Transformer_MultiTask.ipynb

- To run in Google Colab:
- Open Google Colab (https://colab.research.google.com/).
- Upload the notebook file and execute it.

## Discussion Responses
At the end of the notebook, I have included answers to discussion questions related to:
- When to freeze parts of the model during training.
- When to use a multi-task model vs. separate models.
- How to handle imbalanced data between tasks.

## Dependencies
All required libraries are listed in requirements.txt. This includes the following major packages:

- torch for PyTorch
- transformers for working with pre-trained transformer models
- jupyter for running the notebook

## Contact
If you have any questions, feel free to reach out to me at ygadade34@gmail.com
