# Netflix Data Miner

## Overview
This data mining project focuses on extracting valuable insights from the Netflix dataset.
The project is divided into three main phases: 
- Preprocessing
- Extracting Frequent Patterns
- Clustering and Classification

### Phase 1: Preprocessing
In this phase, the raw data is transformed into a structured format, and various preprocessing steps are applied:

- Handling missing values.
- Identifying and removing outliers for numerical data.
- Performing data reduction.
- Converting numerical data to categorical.
- Applying stemming, lemmatizing, and stopword removal for textual data, using libraries such as NLTK.

Additionally, statistical comparisons between the number of films directed by each director and the average number of films per director is conducted.

### Phase 2: Extracting Frequent Patterns
In this phase, specified patterns to extract frequent patterns are utilized from the cleaned dataset using libraries like mlxtend. The focus is on extracting patterns between directors, cast, and genres.

### Phase 3: Classification & Clustering
BERT embeddings is used to convert the cleaned data into vectors.
The subsequent step involves applying clustering algorithms to the vectorized data. In this phase, clustering based on the "listed_in" label is performed. The goal is to predict the genre label for test data based on the movie descriptions.


## Dataset

This dataset is a table containing a list of all the movies and TV shows available on Netflix, along with details such as actors, directors, ratings, release year, duration, and more.
Dataset is provided in dataset directory


## Code Files

This repository includes both Jupyter Notebook and Python script files:

- **`DM_project2_netflix.ipynb`:**
  - Jupyter Notebook file containing the main implementation.

- **`dm_project2_netflix.py`:**
  - Python script file with the same functionality as the Jupyter Notebook.


