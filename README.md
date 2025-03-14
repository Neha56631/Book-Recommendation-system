# 📚 Book Recommendation System

## Overview
This project is a Book Recommendation System that suggests books to users based on their preferences and past ratings. The system utilizes collaborative filtering and content-based filtering techniques to provide personalized recommendations.

## 📊 Datasets
The project uses three different datasets:
1. **Books.csv**: Contains information about the books such as book author, publisher, book title, year of publication, image links, and unique Book ID (ISBN Number).
2. **Ratings.csv**: Contains information about ratings given by users for the books. It includes user ID, ISBN number, and book rating (scale between 1-10).
3. **Users.csv**: Contains information about users such as their location, age, and user ID.

## 🌟 Features
- **Collaborative Filtering**: Recommends books based on the ratings and preferences of similar users.
- **Content-Based Filtering**: Recommends books based on the similarity of book attributes such as author, publisher, and genre.
- **Hybrid Approach**: Combines both collaborative and content-based filtering to improve recommendation accuracy.
- **Streamlit Web App**: Provides an interactive web interface for users to get book recommendations.
- **Data Visualization**: Uses Matplotlib and Seaborn for visualizing data insights.

## 🛠️ Installation
To run this project, you need to have Python installed along with the required libraries listed in the `requirements.txt` file.

You can install the required libraries using the following command:
```bash
pip install -r [requirements.txt](http://_vscodecontentref_/0)