# Starbucks Challenge

## Contents
1. [Overview](#overview)
2. [Project Structure](#projectStructure)
3. [Instructions](#instructions)
3. [Acknowledgment](#acknowledgment)

<a name="overview"></a>
### Overview
This project is the capstone for Udacity's Data Science Nanodegree.  This project aims to build a supervised learning model that predicts whether a customer will be influenced by a BOGO, or discount offers. The methodology of this project is as follows:
1. Evaluate three supervised learning models to predict whether a customer will be influenced by an offer or not. The evaluation will be based on the accuracy and f-score results. The three models are:
    a. Decision Trees
    b. Forests
    c. Ada Boost
2. Evaluate whether a subset of the data can be used to train the above models. As this might be useful when the data size grows in the future.
3. Fine-tune the best of the above models to find better parameters that will improve the accuracy and f-score results.
4. Highlight and discuss the most important features that are used by the chosen model

<a name="projectStructure"></a>
### Project Structure
- `Starbucks_Capstone_notebook.ipynb.ipynb` - Main notebook for analysis
- `Starbucks_Capstone_notebook.html` - An HTML version of the notebook.
- `data` - A folder that contains the datasets
  * `portfolio.json` - containing offer ids and meta data about each offer (duration, type, etc.)
  * `profile.json` - demographic data for each customer
  * `transcript.json` - records for transactions, offers received, offers viewed, and offers completed
- `visuals.py` - A visualization library
- `workspace_utils.py` - A library to prevent notebooks from timing-out

<a name="instructions"></a>
### Instructions:
* Python 3.6+ is required to run the notebook

<a name="acknowledgment"></a>
### Acknowledgment
I would like to thank **Starbucks** for providing the dataset for this project through **Udacity**.
