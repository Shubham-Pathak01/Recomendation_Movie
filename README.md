# Movie Recommendation System

This project is a **content-based and collaborative movie recommendation system** built in Python using Jupyter Notebook. It allows users to find movies similar to a given movie based on user ratings.

---

## **Features**

- Reads movie ratings from a CSV file.
- Creates a **user-item rating matrix**.
- Uses **cosine similarity** to find similar movies.
- Recommends top N movies that are most similar to a selected movie.

---

## **Technologies Used**

- Python 3.14
- Pandas
- NumPy
- Scikit-learn (`NearestNeighbors`)
- SciPy (`csr_matrix`)
- Matplotlib & Seaborn (for visualizations)

---

## **Files in the Project**

- `recomendation.ipynb` – The main Jupyter Notebook containing the code and examples.
- `ratings.csv` – Dataset containing user ratings for movies.
  
**Ratings CSV structure:**

| userId | movieId | title                   | rating |
|--------|---------|------------------------|--------|
| 1      | 8       | Fight Club             | 3.7    |
| 1      | 1       | The Shawshank Redemption | 4.6  |
| 1      | 24      | The Departed           | 4.3    |
