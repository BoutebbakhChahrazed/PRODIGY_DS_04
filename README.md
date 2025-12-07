# Twitter Sentiment Analysis (Prodigy_DS_04)

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Twitter sentiment dataset. The goal is to understand public sentiment patterns regarding various entities (brands, games, and topics) by visualizing the distribution of Positive, Negative, Neutral, and Irrelevant tweets.

This notebook was developed as part of the **Prodigy InfoTech Data Science Internship (Task DS-04)**.

## Features
- **Data Loading**: Automatically handles local or remote dataset loading.
- **Data Cleaning**:
  - Removes rows with missing tweet content.
  - Eliminates duplicate entries to ensure analysis accuracy.
- **Visualization**:
  - **Sentiment Distribution**: Bar chart showing the frequency of each sentiment type.
  - **Entity-Specific Analysis**: Breakdown of sentiment for the top 10 most mentioned brands/topics (e.g., Borderlands).
  - **Proportions**: Pie chart visualizing the percentage share of each sentiment category.

## Dependencies
Ensure you have the following Python libraries installed:
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using pip:
pip install pandas matplotlib seaborn

## How to Run
1. **Download the Notebook**: Save `prodigy-ds-04.ipynb` to your local machine.
2. **Dataset**:
   - The notebook attempts to load `twitter_training.csv` from a local directory.
   - **Fallback**: If the file is not found locally, it automatically downloads the dataset from a public GitHub repository mirror.
3. **Execute**: Open the notebook in Jupyter Lab, Jupyter Notebook, or VS Code and run all cells sequentially.

## Key Visualizations
The analysis generates the following insights:

1. **Total Sentiment Distribution**:
   A global view of how many tweets fall into each sentiment category.

2. **Sentiment by Top 10 Entities**:
   A clustered bar chart that reveals how specific brands or topics (like video games or tech companies) are perceived by the public.

3. **Sentiment Proportions**:
   A pie chart displaying the exact percentage of Positive vs. Negative vs. Neutral sentiment across the entire dataset.

## File Structure
- `prodigy-ds-04.ipynb`: The main Jupyter Notebook containing the code and analysis.
- `twitter_training.csv`: The input dataset (optional if internet access is available for the remote fallback).
