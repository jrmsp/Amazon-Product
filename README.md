# Project Title
Amazon Product DAta AnalysisOne-line description of the project (what it does / what business problem it addresses).

## Team
- Jorge Ramos role: data analyst, presenter
- GitHub repo: https://github.com/jrmsp/Amazon-Product/blob/main/Project2.ipynb

## Dataset
- Source: Kaggle — *Amazon Product Dataset*  
- File included: `data/amazon_product.csv`
- Short description: This dataset contains Amazon product listings (one row per product) with product
  metadata and customer feedback. Key columns include asin, product_title, brand/manufacturer,
  rating (product_star_rating), num_reviews (product_num_ratings), price, review_text, and category.

## Business Questions
List the specific business questions you aim to answer.
1. Which brand is the most popular over the last quarter?
2. Which products are receiving consistently low ratings or high return rates, and what are the top themes in customer complaints?
3. Which produce are the most popular among our customers?

## Folder Structure
├─ data/
│  ├─ amazon_product.csv        # raw dataset (used in this notebook)
│  ├─ raw/                      # optional: original raw files
│  └─ processed/                # optional: cleaned/derived datasets
├─ notebooks/
│  └─ amazon_product_analysis.ipynb   # this notebook (or similar)
├─ src/                         # reusable scripts/modules
│  ├─ data_processing.py
│  ├─ features.py
│  └─ viz.py
├─ figures/                     # saved plots and images
├─ reports/                     # generated reports / markdown / slides
├─ requirements.txt             # Python dependencies
├─ README.md
└─ GitHub
