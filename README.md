#Resume Parsing and Matching with Job Descriptions using spaCy

This project focuses on extracting key information (name, education, work experience, skills) from resumes and matching them with job descriptions using spaCy, a powerful NLP library in Python.

Overview

The project consists of two main parts:

	1.	Resume Parsing: A custom Named Entity Recognition (NER) model is trained using spaCy to extract relevant entities from resumes.
	2.	Resume-Job Matching: Extracted entities from resumes are matched against job descriptions to determine the suitability of candidates.

Requirements

Ensure you have the following libraries installed:

	•	spaCy: Used for NLP tasks including tokenization, named entity recognition, etc.
	•	pickle: Used for serializing and deserializing Python objects (for storing and loading trained models and data).
	•	scikit-learn: Useful for various machine learning tasks such as text vectorization and similarity scoring (if needed).
	•	Other standard Python libraries: Like random for shuffling data during training, and spacy.training.example.Example for creating training examples.
