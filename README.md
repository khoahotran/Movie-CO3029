# 20th Century Film Data Analysis

This project analyzes the TMDB (The Movie Database) dataset, focusing on film trends throughout the 20th century (1900-1999). The project includes data cleaning, statistical analysis, visualization, and revenue prediction using LSTM models.

## Key Components

- **Data Cleaning & Processing**: Removing duplicates, handling missing values, converting date formats, and filtering movies from the 20th century.
- **Statistical Analysis**: Analyzing film status distribution, ratings, runtime, and other factors.
- **Genre Analysis**: Identifying popular genre trends over time, average runtime, and revenue by genre.
- **Temporal Analysis**: Studying film releases by year and month to identify trends and seasonality.
- **Financial Analysis**: Evaluating budget, revenue, and profit trends over time.
- **Revenue Prediction**: Using LSTM models to predict film revenue for 2000-2020 based on 20th-century data.

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/khoahotran/Movie-CO3029
   ```

2. Download the dataset from [TMDB Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

3. Run the analysis notebook:

## Directory Structure

```
├── images/                         # Generated charts and visualizations
|-- CO3029___Data_Mining.pdf        # Report
├── datamining-tmdb-movie.ipynb     # Notebook
└── README.md                       # This file
```

## Key Findings

- Film production increased significantly over time, especially from the 1970s onward.
- Average film runtime fluctuated but showed a slight upward trend over time.
- Drama and Comedy genres consistently led in quantity, while Adventure and Science Fiction generated higher revenues.
- Film budgets and revenues increased over time, particularly from the 1980s.
- The LSTM model demonstrated good accuracy in predicting film revenues.

## Technologies Used

- Python 3.x
- Pandas, NumPy for data processing
- Matplotlib, Seaborn for visualization
- TensorFlow/Keras for LSTM modeling
- Jupyter Notebooks for interactive analysis

## Author

- Khoa Tran
