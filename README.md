# 📚 Book Analysis Project
## Overview

This project analyzes a dataset of books to explore trends in authors, reviews, ratings, and popularity. The analysis uses Python libraries such as pandas, matplotlib, seaborn, Plotly, and WordCloud to generate insights and visualizations.

## 🗂 Dataset

Source: [https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019]
  
Columns include:

- Name – Book title

- Author – Name of the author

- Reviews – Number of reviews for the book

- User Rating – Average rating given by users

- Price – Price of the book


## 🔬 Key Analyses

- Top Authors by Number of Books

- Groups authors and counts how many books each has published.

- Visualized using bar charts.

- Top Authors by Average Reviews

- Finds authors whose books have the highest average number of reviews.

- Visualized using Plotly bar charts.

- Interactive Scatter Plots

- Compares User Rating vs Reviews.

- Highlights popular authors and books.

- Word Cloud of Authors

- Visualizes the most frequent authors in the dataset.

- Word size corresponds to frequency.

- Customizable colors using colormaps or color functions.

## 📊 Libraries Used

pandas – Data manipulation and cleaning

numpy – Numerical operations

matplotlib & seaborn – Static visualizations

plotly – Interactive visualizations

wordcloud – Generate word clouds

## 🛠 How to Run

Clone or download the repository:

git clone https://github.com/yourusername/Book-Analysis.git


Open the Jupyter Notebook (.ipynb) or Colab file.

Make sure all required libraries are installed:

pip install pandas numpy matplotlib seaborn plotly wordcloud


Load the dataset (books.csv or your dataset file).

Run the notebook cells to reproduce the analysis and visualizations.

## 📈 Insights

Authors with the most books are not necessarily the ones with the highest reviews.

Some authors dominate in both quantity and quality (highly reviewed).

Word cloud highlights the most frequently occurring authors in the dataset.

Interactive plots help identify outliers and trends in ratings vs reviews.

## 🔧 Future Improvements

Include price vs ratings analysis.

Add genre-based analysis for more detailed insights.

Deploy interactive dashboards using Plotly Dash or Streamlit.

## 📄 License

This project is open-source and free to use for educational purposes.
