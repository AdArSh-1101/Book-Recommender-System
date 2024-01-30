# Book Recommender System

This project implements a Book Recommender System using Flask, which includes both a popularity-based recommender and a collaborative filtering-based recommender.

## Project Structure

- **app.py**: This file contains the Flask application code responsible for handling routes and rendering templates.
- **templates**: This directory contains HTML templates for different pages of the web application.
  - **index.html**: Home page template displaying popular books.
  - **recommend.html**: Recommendation page template where users can input a book title to get recommendations.
  - **contact.html**: Contact page template.
- **static**: This directory contains static files such as CSS stylesheets and images.
- **popular.pkl**: Pickled file containing data for popular books.
- **pt.pkl**: Pickled file containing the pivot table for collaborative filtering.
- **books.pkl**: Pickled file containing book data.
- **similarity_scores.pkl**: Pickled file containing similarity scores for collaborative filtering.
- **Untitled.ipynb**: Jupyter notebook containing code used to generate the pickled files.

## Setup and Installation

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`
4. Access the application in your web browser at `http://localhost:5000`

## Usage

- **Home Page**: Displays a list of popular books with their details such as title, author, image, number of ratings, and average rating.
- **Recommend Page**: Allows users to input a book title and get recommendations based on collaborative filtering.
- **Contact Page**: Provides contact information for the project.

## Data Sources

- **books.csv**: Contains information about books such as ISBN, title, author, publication year, and publisher.
- **users.csv**: Contains information about users such as user ID, location, and age.
- **ratings.csv**: Contains user ratings for books.

## Algorithms Used

- **Popularity-Based Recommender**: Recommends books based on popularity and average ratings.
- **Collaborative Filtering**: Recommends books based on user-item interactions using cosine similarity.

## Tools Used

- **Flask**: Python web framework used for building the web application.
- **Pandas**: Python library used for data manipulation and analysis.
- **Bootstrap**: Frontend framework used for designing responsive and mobile-first websites.
- **Jupyter Notebook**: Interactive computing environment used for data exploration and model building.

Feel free to reach out for any questions or feedback!
