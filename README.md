
# OTT Platform Popularity Prediction and Analysis

This project aims to analyze and predict the popularity of content on OTT platforms, specifically using Netflix data from 2023. The project combines data analysis using Python, visualization using Power BI, and machine learning techniques to build a predictive model for content popularity.

---

## Project Overview

The project includes the following components:
- **Data Analysis:** Exploration and cleaning of Netflix content data.
- **Machine Learning Model:** A prediction model to estimate content popularity based on attributes such as type, genre, release year, and duration.
- **Power BI Dashboard:** An interactive dashboard for visualizing key insights and trends from the dataset.

---

## Folder Structure

```
.
├── data
│   └── netflix_content_2023.csv        # Dataset used for analysis and modeling
├── notebooks
│   └── OTT_Popularity_Prediction.ipynb  # Jupyter Notebook with data processing, EDA, and model building
├── dashboard
│   └── OTT_Platform_Analysis.pbix       # Power BI dashboard file
├── README.md                            # Project documentation (this file)
└── requirements.txt                     # Python libraries required to run the project
```

---

## Dataset

- **Source:** Netflix Content 2023 Dataset
- **File:** `netflix_content_2023.csv`
- **Main Columns:**
    - Title
    - Type (Movie/TV Show)
    - Release Year
    - Duration
    - Genre
    - Rating
    - Popularity Score (if applicable)

---

## Key Steps

### 1. Data Cleaning and Preprocessing
- Handled missing values
- Converted data types
- Feature engineering for genres, duration categories, etc.

### 2. Exploratory Data Analysis (EDA)
- Distribution of content types
- Release year trends
- Popular genres
- Rating distribution

### 3. Predictive Model
- Used machine learning algorithms (e.g., Random Forest, Decision Tree, etc.)
- Target variable: **Popularity Score (or relevant popularity indicator)**
- Features: Type, Genre, Release Year, Duration, etc.
- Model evaluation using metrics like MAE, MSE, R².

### 4. Power BI Dashboard
- Visualized key insights, including:
    - Content distribution by year and type
    - Top genres
    - Rating analysis
    - Trend of content release over time

---

## Requirements

To run the Python analysis and modeling, install the following libraries:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
plotly
jupyterlab
openpyxl
```

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/Netflix-OTT-Popularity-Prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Netflix-OTT-Popularity-Prediction
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Open Jupyter Notebook to run the analysis:

    ```bash
    jupyter lab
    ```

5. Explore the Power BI dashboard using **`OTT_Platform_Analysis.pbix`**.

---

## Results and Insights

- The number of new titles released on Netflix increased steadily from 2015 to 2022.
- Movies outnumber TV shows in the dataset.
- Certain genres like Documentaries, Stand-up Comedy, and International content are particularly popular.
- Duration and release year have a notable impact on predicted popularity.

---

## Author

- **Gitashri Sathyamoorthy**
- **htpps://github.com/GitaSathya/**
- **gitasathya2407@gmail.com**

---

## Acknowledgements

- Netflix dataset sourced from public domain sources.
- Python libraries: pandas, seaborn, scikit-learn, matplotlib, etc.
- Power BI for visual analytics.
