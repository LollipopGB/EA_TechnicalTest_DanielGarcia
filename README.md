The reasoning and decision making of the process is explained through the notebooks. The sequence to read them is the following:

## Exploratory Analysis
It explains the dataset and contains some basic outcomes from the documents that helps to take design decisions to achieve Tasks 1 and 2. It also generates a dataset preprocessed for Task 2.

## MUSE Word Embeddings - Task 1
It is a colab notebook to generate the embeddings with a Multilingual Universal Sentence Encoder. It was run in Colab to facilitate the setup installation and the requirements, for example, a library that uses MUSE can only be used in Linux.

## Text Classification MUSE - Task 1
Train a ML classifier, in specific a Logistic Regression, to classify the documents in categories. It is done with the MUSE embeddings. Some basic metrics to understand the performance of the model are calculated such as Accuracy, recall, confusion matric etc.

## MBERT Word Embeddings - Task 1
It is a colab notebook to generate the embeddings with a Multilingual BERT model. It was run in Colab to facilitate the setup installation and the requirements. Easier access and configuration with Tensorflow Hub.

## Text Classification MBERT - Task 1
Train a ML classifier, in specific a Logistic Regression, to classify the documents in categories. It is done with the MBERT embeddings. Some basic metrics to understand the performance of the model are calculated such as Accuracy, recall, confusion matric etc.

## Topic Modelling - Task 2
Train 3 different models, select the best one, extract the topics of the documents per language and visualize the results.

Some of the graphs are not saved in the notebooks because they are user interactive. There are saved plots in the folder "plots" to show them.

All the generated datasets are not upload here because of size limits.
