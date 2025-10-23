# Masking_Specific_Entity_Using_NER
This project demonstrates how to use Named Entity Recognition (NER) to identify specific entities, particularly persons, within conversational text. The primary goal is to then mask or replace these identified entities with a placeholder to hide sensitive or specific information


# Technology/Programming Stack:

* **Python** — Core programming language used throughout the notebook.
* **pandas** — For data manipulation and creating DataFrames.
* **re** — For regular expressions to extract dialogue lines.
* **spaCy** — For initial Named Entity Recognition (NER) and tokenization.
* **transformers** — Provides access to pre-trained models like BERT and tools for fine-tuning.
* **torch (PyTorch)** — Deep learning framework used for building and training the NER model.
* **scikit-learn (sklearn)** — For splitting the dataset into training, validation, and testing sets.

# 🤖 Machine Learning Models Used

* **BERT (dslim/bert-base-NER)** — Pre-trained transformer model fine-tuned for the **Named Entity Recognition (NER)** token classification task.
* **spaCy `en_core_web_sm`** — Lightweight NLP model used for **initial entity extraction** and preprocessing.

# Test sample
<img width="1301" height="62" alt="image" src="https://github.com/user-attachments/assets/9d3e8d5f-3f7c-46a0-9cac-e96c41e4b569" />

# Masked 
<img width="1448" height="66" alt="image" src="https://github.com/user-attachments/assets/30e81fc7-d1ff-4cfd-995d-336ca28cde07" />





