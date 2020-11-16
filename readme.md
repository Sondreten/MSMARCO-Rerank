# MS MARCO Group Project Team-013

Here you will find our implementation for the MS MARCO re-ranking 2020 task. This project was part of our evaluation and project work in DAT640-1 20H Information Retrieval and Text Mining. This implementation are using a feature based traditional machine learning approach to this problem.
This was a group project, created by Sondre Tennø, Einar Langholm, Anthony Ibeme.

## Dataset

To run this code, you will need to download all neccessary datasets from the official MS MARCO website: https://microsoft.github.io/msmarco/

and from the github: https://github.com/microsoft/MSMARCO-Document-Ranking

## Code

All of our code in this project are in one single jupyter notebook file, 'MSmarco_013.ipynb'.
Going through each section as they were implemented, download libraries, indexing, gathering trainingdata, gathering dev and test sets, evaluation, baseline, advanced model.

## Before running the code

Before you run the code, you have to set 'index = False' to 'index = True' in the elasticsearch indexing cell.

Also, you need to be sure you have downloaded all the dataset files from MS MARCO, specifically:

queries.doctrain.tsv  
queries.docdev.tsv  
msmarco-doctrain-qrels.tsv  
msmarco-doctrain-top100.tsv  
msmarco-doctrain-queries.tsv  
msmarco-docs.tsv  
msmarco-docdev-queries.tsv  
msmarco-docdev-qrels.tsv  
msmarco-docdev-top100.tsv  

## Environment

Your environment is expected to be an Anaconda base environment with Python version 3.6+.
You must have elasticsearch library installed with version 7.9.1+ and have a local instance of it running on your machine.

## Paper

To contemplate the code, we have written a paper regarding our implementation of our re-ranking models. What approaches we have chosen and why we did certain things.
The paper can be found in this github repository as 'Team_013.pdf'.