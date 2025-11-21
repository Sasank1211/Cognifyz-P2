# Cognifyz-P2
🍽️ Restaurant Recommendation System

A machine learning–based Restaurant Recommendation System that recommends restaurants to users based on their preferences such as cuisine type, price range, ratings, and other restaurant attributes.
This project uses content-based filtering and user-preference matching to generate personalized recommendations.

📌 Project Overview

The Restaurant Recommendation System helps users discover restaurants that match their preferences by analyzing restaurant features such as:

Cuisine type

Price range

Aggregate rating

Online delivery availability

Location

Popularity / votes

Using machine learning and similarity metrics, the system suggests restaurants most similar to what the user likes or searches for.

🎯 Key Features

✔ Recommends restaurants based on cuisine, price, and rating
✔ Content-based filtering using cosine similarity
✔ Preprocessed and cleaned restaurant dataset
✔ User input–based recommendation function
✔ Rating threshold filters (e.g., show only restaurants > 3.5)
✔ Easy-to-use Python implementation
✔ Extendable to hybrid (content + collaborative) systems

🧠 Technologies Used

Python

Pandas (data handling)

Scikit-Learn (encoding + similarity computation)

NumPy

Matplotlib / Seaborn (optional for visualization)

Jupyter Notebook / Google Colab

🚀 How It Works

Dataset is preprocessed (missing values handled, categorical encoding applied).

Important features are selected:

Cuisines

Price range

Rating

Location

Similarity matrix is computed using cosine similarity.

User provides preferences such as:

"Indian" cuisine,

Price range = 2,

Min rating = 3.5

System returns the top recommended restaurants matching the criteria.
