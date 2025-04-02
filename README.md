# SOEN471 (Big Data Analytics) Assignment 2: Smartcart Recommender System & Pattern Mining for E-Commerce Analytics

## Project Description

This project implements and evaluates two techniques for e-commerce analytics using a simulated dataset:

1.  **User-Based Collaborative Filtering:** Recommends products to users based on the purchasing behavior and ratings of similar users, using Cosine Similarity.
2.  **Association Rule Mining:** Discovers frequent itemsets and association rules using the Apriori algorithm.

The goal is to generate personalized recommendations, identify purchasing patterns, visualize insights, and evaluate the implemented systems.

## File Structure
- **SOEN471_Assignment_2.ipynb** Jupyter Notebook containing all the Python code for analysis
- **ecommerce_user_data.csv** 742 rows of user-product interaction data (UserID, ProductID, Rating, Timestamp, Category)
- **product_details.csv** 100 rows of product metadata (ProductID, ProductName, Category)
- **README.md** This file

## Dependencies & Setup

1.  **Clone the repository or download the project files into your python environment.**
2.  **Install dependencies:**
    ```
    pandas
    scikit-learn
    mlxtend
    seaborn
    matplotlib
    jupyter
    ```
3.  **Place Datasets:** Ensure the `ecommerce_user_data.csv` and `product_details.csv` files are located in the correct directory.
4.  **Open and Run the Notebook:** ```jupyter notebook SOEN471_Assignment_2.ipynb```


## Outputs

1.  **Console Output:**
    * Top-5 product recommendations for each user.
    * Evaluation metrics (Precision@K, Recall@K, Mean Average Precision).
    * Frequent itemsets and generated association rules (support, confidence, lift).
2.  **Visualizations:**
    * User similarity heatmap.
    * Bar chart of top frequent itemsets.

## Team Members 

* Tristan Lafleur
* Zaid Minhas
* Marc Frennette-Laurent
* Nicholas Cook
---
