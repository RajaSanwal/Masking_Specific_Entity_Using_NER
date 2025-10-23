# Masking_Specific_Entity_Using_NER
This project demonstrates how to use Named Entity Recognition (NER) to identify specific entities, particularly persons, within conversational text. The primary goal is to then mask or replace these identified entities with a placeholder to hide sensitive or specific information


# Technology/Programming Stack:

Python: The core programming language used throughout the notebook.
pandas: Used for data manipulation and creating DataFrames.
re: Used for regular expressions to extract dialogue lines.
spaCy: Used for initial Named Entity Recognition and tokenization.
transformers: Provides access to pre-trained models like BERT and tools for fine-tuning.
torch: The deep learning framework used for building and training the NER model.
sklearn: Used for splitting the dataset into training, validation, and testing sets.
