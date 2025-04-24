# Banknote Authentication using K-means Clustering

A simple machine learning project that uses K-Means Clustering to detect potential counterfeit banknotes based on their statistical properties. This project demonstrates unsupervised learning using real-world data and visualises the clustering process.

## Project Structure

- **`data/`**: Contains the dataset used for analysis and prediction.
- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`README.md`**: Project overview and usage instructions.

---

## Features

- Load and explore a dataset of banknotes
- Preprocess data for clustering
- Apply K-Means Clustering to group genuine and counterfeit bills
- Visualise the clusters using Matplotlib and Seaborn
- Evaluate clustering results using inertia and silhouette score

## Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/nurulashraf/kmeans-counterfeit-bills.git
    cd kmeans-counterfeit-bills
    ```

2. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn scipy
    ```

3. Place your dataset (`fake_bills.csv`) in the `data` folder.

4. Open the notebook:
    ```bash
    jupyter notebook kmeans_counterfeit_bills.ipynb
    ```

5. Run the cells and explore the analysis.

---

## License

This project is licensed under the [MIT License](LICENSE).
