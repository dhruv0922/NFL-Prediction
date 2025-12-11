# NFL-Prediction

NFL Game Outcome Prediction (2014–2024)

This project uses basic NFL game statistics to predict whether a team will win or lose a game. It uses three simple machine learning models:

Decision Tree

Naive Bayes

Logistic Regression

All data comes from the NFLVerse play-by-play dataset.
The project runs entirely in Google Colab.

What This Project Does:

Loads NFL play-by-play data from 2014–2024

Converts the data into game-level stats (yards, turnovers, third-down rate, etc.)

Trains three machine learning models

Compares their accuracy and probability estimates

Shows feature importance and accuracy charts

The goal is to see how well simple football stats can predict game outcomes.

How to Run the Project
1. Download the Data

Go to the NFLVerse GitHub page:

https://github.com/nflverse/nflverse-data

Download the following files:

play_by_play_2014.parquet  
play_by_play_2015.parquet  
...
play_by_play_2024.parquet


Put all these files in a folder and upload them to Google Colab (or mount Google Drive).

2. Open the Google Colab Notebook

Open the notebook the same way you would open any .ipynb file.

3. Run All Cells

Once the data files are available:

Run the notebook from top to bottom

The notebook will:

Load the data

Build the game-level dataset

Train the models

Show results and graphs

No extra setup is required.

Project Files

NFL_Game_Prediction.ipynb — Main notebook

README.md — This file

feature importance figures — Images created by the notebook

Requirements

All required packages come pre-installed in Google Colab:

pandas

numpy

scikit-learn

matplotlib

No manual installation is needed.
