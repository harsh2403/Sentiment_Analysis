# Sentiment Analysis


#### In this project, I have used **Amazon Product Reviews** data to predict the rating of a given product based on the review given to it by a user. The dataset comprises of only the Indian Brand Products, this will also help us get more insights on how is the Indian Product Market doing among the customers and whether the **Vocal for Local** drive sustain and satisfy the needs of consumer with local products.

## Project Structure

|-- Data
|      |
|      |- reviews.csv            - Raw data
|      |- clean.csv              - Data is removed of NAN, missing and duplicate values.
|      |- Test-Train             - This contains train/test split of clean.csv data.
|      |- Test-Train(CommonWords)- Train/Test split with stop & common words removed.
|      |- Test-Train(Stemmed)    - Train/Test split with stop & stemmed words removed.
|      |- Test-Train(Stopped)    - Train/Test split with stop words removed.
|      |- file.txt               - List of common words in the reviews.
|
|-- Notebooks
|      |
|      |- Combined.ipynb - Testing purpose notebook.
|      |- DataWrangling.ipynb
|      |- ExploratoryDataAnalysis.ipynb
|      |- PreProcessing and Training.ipynb
|      |- Modeling.ipynb
|
|
|-- Reports
|      |
|      |- FinalReport.pdf
