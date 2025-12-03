# Zomato Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on a Zomato restaurants dataset.  
The goal is to understand how different factors like **location, cuisine, price range, ratings, and services (online delivery, table booking, etc.)** impact restaurant performance.

---

## 📂 Project Structure

```text
Zomato-Exploratory-Data-Analysis/
├── Zomato EDA.ipynb      # Main Jupyter Notebook with full analysis
├── zomato.csv            # Zomato dataset used for EDA
├── Country-Code.xlsx     # Country code mapping for the dataset
└── README.md             # Project documentation
````

---

## 🎯 Objectives

* Clean and preprocess the Zomato dataset.
* Understand the distribution of restaurants across **countries, cities, and cuisines**.
* Analyze **ratings, votes, and price range** patterns.
* Study the impact of:

  * Online delivery
  * Table booking availability
* Identify **top cuisines and locations** based on ratings and restaurant count.
* Generate meaningful visual insights using Python libraries.

---

## 🧾 Dataset Description

The project uses the `zomato.csv` dataset along with `Country-Code.xlsx` for mapping country codes to country names.

Typical columns in the dataset include (may vary slightly):

* `Restaurant Name`
* `Country Code`
* `City`
* `Cuisines`
* `Price range`
* `Aggregate rating`
* `Rating text`
* `Votes`
* `Has Table booking`
* `Has Online delivery`
* `Is delivering now`

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Environment:** Jupyter Notebook (`Zomato EDA.ipynb`)

**Libraries used:**

* `pandas` – data loading, cleaning, manipulation
* `numpy` – numerical operations
* `matplotlib` – basic visualizations
* `seaborn` – advanced and attractive statistical plots

*(Import statements are available inside the notebook.)*

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/karthikeyagandepalli/Zomato-Exploratory-Data-Analysis.git
   cd Zomato-Exploratory-Data-Analysis
   ```

2. **Create and activate a virtual environment** (optional but recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate      # On macOS / Linux
   venv\Scripts\activate         # On Windows
   ```

3. **Install the required libraries**

   ```bash
   pip install -r requirements.txt
   ```

   > If `requirements.txt` is not available, install manually:
   >
   > ```bash
   > pip install pandas numpy matplotlib seaborn jupyter
   > ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

5. **Open the analysis notebook**

   * In the Jupyter interface, open: **`Zomato EDA.ipynb`**
   * Run the cells in order to reproduce the analysis and visualizations.

---

## 📊 Analysis Overview

The notebook covers:

1. **Data Loading**

   * Importing `zomato.csv` and `Country-Code.xlsx`
   * Merging country codes with main dataset (if applicable)

2. **Data Cleaning**

   * Handling missing values
   * Dropping irrelevant columns (if any)
   * Fixing data types
   * Removing duplicates

3. **Univariate Analysis**

   * Distribution of ratings
   * Price range categories
   * Most common cuisines
   * Restaurant count by country and city

4. **Bivariate & Multivariate Analysis**

   * Relationship between **price range and ratings**
   * Impact of **online delivery** on ratings
   * Impact of **table booking** on ratings/votes
   * Top cuisines in terms of ratings and popularity

5. **Visualizations**

   * Bar plots, count plots, box plots, histograms, etc.
   * Heatmaps (if applicable) to visualize correlations

---

## 🔍 Key Questions Explored

Some of the business/analysis questions this project tries to answer:

* Which **countries and cities** have the most Zomato-listed restaurants?
* What are the **most popular cuisines**?
* Do restaurants with **online delivery** or **table booking** tend to have higher ratings?
* What **price ranges** are most common and how do ratings vary across them?
* Which cuisines or locations have **top-rated restaurants**?

---

## 📌 Future Improvements

Potential enhancements:

* Build interactive dashboards using **Plotly** or **Streamlit**.
* Add **machine learning models** to predict restaurant ratings.
* Perform **sentiment analysis** if review text data is available.
* Compare Zomato data with other food platforms (Swiggy, UberEats etc.) if datasets are available.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome.

* Feel free to **fork** the repo and open a **pull request**.
* If you spot any bug or want a new feature, please open an **issue**.

---

## 👤 Author

**Karthikeya Gandepalli**

* GitHub: [@karthikeyagandepalli](https://github.com/karthikeyagandepalli)

---

⭐ If you find this project helpful, consider giving it a **star** on GitHub!

```


