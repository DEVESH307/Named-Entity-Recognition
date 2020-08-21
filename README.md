# Named Entity Recognition using LSTMs with Keras 

## Welcome!
Welcome to **Named Entity Recognition using LSTMs with Keras**.

### What are Named Entities?
Named entities are sets of elements that are important to understanding text. Some common entities come from parts of speech (like nouns, verbs, adjectives, etc). Nouns in particular are essential in understanding the subtle details in a  sentence. Thus, we look more into nouns than other parts of speech when working with named entity recognition, which will be explained below.

### Named Entity Recognition Explained

In [Natural language processing](https://deepai.org/machine-learning-glossary-and-terms/natural-language-processing), Named Entity Recognition (NER) is a process where a sentence or a chunk of text is parsed through to find entities that can be put under categories like names, organizations, locations, quantities, monetary values, percentages, etc. Traditional NER algorithms included only names, places, and organizations. However, they can now be dynamically trained to extract more than just the previously mentioned entities. NER is a simple but effective approach to reduce searching a state space by directing the algorithm to weigh the sentences more if a chunk of entities are found.

### Example of under the hood NER
![](https://images.deepai.org/glossary-terms/named-entity-recognition-2986500.jpg)

## Project Objectives
In this course, we are going to focus on two learning objectives:

1. Build and train a bi-directional LSTM with Keras
2. Solve the Named Entity Recognition (NER) problem with LSTMs

By the end of this course, you will be able to build and train a bidirectional LSTM neural network model to recognize named entities in text data.

## Project Structure
The hands on project on **Named Entity Recognition using LSTMs with Keras** is divided into following tasks:

### Task 1: Project Overview and Import Modules
- Introduction to the data and and overview of the project.
- Introduction to the Rhyme interface.
- Import essential modules and helper functions from [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), and [Keras](https://www.tensorflow.org/guide/keras).
### Task 2: Load and Explore the NER Dataset
- Load the [NER dataset](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus#ner_dataset.csv) using pandas.
### Task 3: Retrieve Sentences and Corresponding Tags
### Task 4: Define Mappings between Sentences and Tags
### Task 5: Padding Input Sentences and Creating Train/Test Splits
### Task 6: Building and Compile a Bidirectional LSTM Model
### Task 7: Train the Model
### Task 8: Evaluate Named Entity Recognition Model

