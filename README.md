# Course Recommendation System

This project implements a Course Recommendation System using datasets from Udemy and Coursera. The goal is to recommend similar courses based on user input by analyzing course titles and leveraging TF-IDF vectorization and cosine similarity.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Visualizations](#visualizations)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we clean and preprocess datasets from Udemy and Coursera, visualize important trends, and build a recommendation engine that suggests similar courses based on user input.

## Datasets

The datasets used for this project are:
- **Udemy Courses**: Contains information about various courses available on Udemy.
- **Coursera Courses**: Contains information about various courses available on Coursera.

Both datasets are available in the `data` folder of this repository.

- [Link to the Udemy dataset](https://raw.githubusercontent.com/kueyram/Course-Recommendation/refs/heads/main/data/udemy_courses.csv)
- [Link to the Coursera dataset](https://raw.githubusercontent.com/kueyram/Course-Recommendation/refs/heads/main/data/coursera_courses.csv)

## Installation

To run this project, you need to have Python installed on your machine. Additionally, you will need to install the required libraries. You can do this using pip:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn streamlit fuzzywuzzy



Usage

1. Clone repository

git clone https://github.com/your_username/Course-Recommendation.git
cd Course-Recommendation


2. Run the Streamlit application

streamlit run app.py

3. Open your web browser and go to http://localhost:8501 to use the Course Recommendation System.



## Features

    Data cleaning and preprocessing of course titles.
    Visualizations to explore course subjects, subscribers, and more.
    A recommendation engine that suggests similar courses based on a user's input.

## Visualizations

The project includes several visualizations that display insights into the dataset, such as:

    Distribution of course subjects.
    Number of subscribers by course level.
    Trends over time for published courses.

## Technologies Used

    Python: Programming language used for data analysis and machine learning.
    Pandas: Library for data manipulation and analysis.
    NumPy: Library for numerical computations.
    Matplotlib & Seaborn: Libraries for data visualization.
    NLTK: Library for natural language processing.
    Scikit-learn: Library for machine learning.
    Streamlit: Framework for building interactive web applications.
    FuzzyWuzzy: Library for fuzzy string matching.


## License

This project is licensed under the MIT License. See the LICENSE file for details


