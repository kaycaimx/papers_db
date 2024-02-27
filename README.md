# SQLite Python Program

NEU CS5200 Spring 2024 - Group Project 1

Group members: Mengxian Cai, Siyi Ling, Yunxi Li, Zixiang Hu

## Overview

This is a simple Python program that interacts with SQLite using Jupyter Notebook. The program simulates a paper management system for a hypothetical conference. It provides a dummy database file (papers.db) and an interface implemented by Jupyter Notebook where the user can set the score threshold for paper acceptance, view the numbers of accepted/rejected/undecided papers in each research area, and some other interactions with the database.

## Prerequisites

Before running the program, make sure you have the following installed:

- Python
- Jupyter Notebook
- SQLite
- Numpy
- Matplotlib.pyplot

## Contents Overview

- ER_model.pdf: The ER-model visualized of the papers database
- statements.txt: The text file containing all CREATE TABLE statements and triggers, with the set of INSERT statements to populate data
- papers.db: The SQLite database file used in the Jupyter Notebook
- papers_db.ipynb: The Jupyter Notebook file containing the program to connect to the database and do queries

### Database Details

- **File Name**: `papers.db`
- **Path**: the database should be saved within the same directory as the papers_db.ipynb file

### Using the Sample Database

1. Ensure that you have the necessary prerequisites installed.

2. Ensure that the `papers_db.ipynb` file and the `papers.db` file are in the same directory.

3. Open the `papers_db.ipynb` notebook in Jupyter Notebook or upload it to Google Colab (in the latter case, ensure that you also upload `papers.db` to runtime Files).

4. Follow the instructions and run code blocks of the notebook to connect to the database and explore various SQLite operations.
