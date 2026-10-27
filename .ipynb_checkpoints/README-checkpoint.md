# SmartCart — Customer Segmentation Using Machine Learning

A customer segmentation project using unsupervised machine learning to analyze customer demographics, spending patterns, and purchasing behavior.

## Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · PCA · K-Means · Agglomerative Clustering

## Project Workflow

- **Data Preprocessing:** Handled missing income values using median imputation and filtered outliers.
- **Feature Engineering:** Created features such as age, customer tenure, total spending, and household characteristics.
- **Feature Preparation:** Applied one-hot encoding and `StandardScaler`.
- **Dimensionality Reduction:** Used PCA to reduce the feature space to three components.
- **Clustering:** Implemented K-Means and Agglomerative Clustering with four clusters.
- **Evaluation:** Explored the Elbow Method and Silhouette Score to investigate suitable cluster counts.
- **Visualization:** Analyzed cluster patterns using plots and summary statistics.

## Results Summary

| Metric | Result |
|---|---|
| Initial dataset | 2,240 records |
| Records after outlier filtering | 2,236 |
| PCA components | 3 |
| Variance explained by PCA | 44.95% |
| Clustering algorithms | K-Means, Agglomerative |
| Clusters used | 4 |

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/SmartCart-Customer-Segmentation.git
cd SmartCart-Customer-Segmentation
```

### 2. Create and Activate a Virtual Environment

**Windows (PowerShell)**

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the Notebook

Ensure `smartcart_customers.csv` is in the project directory, then run:

```bash
jupyter notebook smartCart.ipynb
```

## Dependencies

Create a `requirements.txt` file containing:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
kneed
jupyter
```

## Key Learnings

- Data preprocessing and feature engineering
- Exploratory data analysis
- PCA and dimensionality reduction
- Unsupervised learning and clustering
- Cluster evaluation and visualization

## Limitations

- The three PCA components explain 44.95% of the variance.
- Cluster quality and business usefulness require further validation.

## Author

**Harsh**

- GitHub: [Your GitHub Profile](https://github.com/)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/)