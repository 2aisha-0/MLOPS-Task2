# MLOps Task 2 - From Tables to Notebooks

## Project Goal

The goal of this project is to build a machine learning model that predicts whether an order will be delivered late.

The prediction is based on information available about an order.

## Notebook Workflow

The project is divided into six notebooks:

1. Read and Join the Tables
2. Create the Labels
3. Train / Validation / Test Split
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Train, Tune, and Evaluate

The workflow is:

Read & Join → Label → Split → EDA → Feature Engineering → Train & Evaluate

## Project Structure

* `notebooks/` - Jupyter notebooks
* `data/` - project data
* `artifacts/` - outputs from the notebooks
* `src/` - Python source code
* `Dockerfile` - Docker environment
* `requirements.txt` - Python packages
* `.gitignore` - files that should not be tracked by Git

## Main Problem

Given information available about an order, predict whether its delivery will be late.

## Expected Output

The final output is a trained machine learning model and a summary of its evaluation results.
