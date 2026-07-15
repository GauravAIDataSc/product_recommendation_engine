# Product Recommendation System

A machine learning-based recommendation system that suggests products based on users' past ratings and preferences. This project explores multiple recommendation techniques, including Popularity-Based Recommendation, User-Based Collaborative Filtering, and Matrix Factorization (SVD), while following a complete machine learning workflow from data preprocessing to model evaluation.

## Dataset

This project uses the **Amazon Electronics Ratings Dataset**, which contains user-product interactions collected from Amazon product reviews.

Due to GitHub's file size limitations, the dataset is **not included** in this repository. You can download it from the links below.

### Download Dataset

- **Kaggle:**  
  https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation

- **UCSD Amazon Review Dataset:**  
  https://jmcauley.ucsd.edu/data/amazon/

After downloading the dataset, place the CSV file inside the `data/` folder before running the notebook.

## Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Popularity-Based Recommendation
- User-Based Collaborative Filtering
- Matrix Factorization (SVD)
- Model Evaluation (RMSE & MAE)

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```
Product-Recommendation-System/
│── product_recommendation_engine.ipynb
│── requirements.txt
│── README.md
│── data/
└── images/
```

## How to Run

```bash
git clone https://github.com/your-username/Product-Recommendation-System.git

cd Product-Recommendation-System

pip install -r requirements.txt

jupyter notebook
```

## Future Improvements

- Hybrid Recommendation System
- Content-Based Filtering
- Precision@K & Recall@K
