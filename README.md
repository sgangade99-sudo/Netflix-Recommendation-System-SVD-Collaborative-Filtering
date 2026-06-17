# Netflix SVD Recommendation System

## Overview
This project implements a **collaborative filtering** recommendation engine using **Singular Value Decomposition (SVD)** on the [Netflix Prize dataset](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data).  
It preprocesses raw rating data, filters inactive users and movies, trains an SVD model via the `surprise` library, and predicts top-N movie recommendations for a given user.

## Dataset
- **Ratings file**: `combinedNetflixData.txt` – contains movie IDs (as headers) followed by `(CustomerID, Rating)` pairs.
- **Movies file**: `movies.csv` – maps movie IDs to titles and genres.
- Both files are expected to be placed in your Google Drive under the path:  
  `/content/drive/MyDrive/netflix data/`

## Requirements
- Python 3.7+
- `numpy==1.26.4`
- `pandas`
- `matplotlib`, `seaborn`
- `scikit-surprise`
- Google Colab environment (for Drive mounting) – but can be adapted for local use.

Install dependencies:
```bash
pip install numpy==1.26.4 pandas matplotlib seaborn scikit-surprise


