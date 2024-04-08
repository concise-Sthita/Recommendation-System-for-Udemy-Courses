# Recommendation-System-for-Udemy-Courses
This repository contains a Jupyter Notebook for analyzing Udemy course data using text vectorization and cosine similarity. The notebook demonstrates how to preprocess text data, remove stopwords and special characters, and convert the cleaned text into a matrix of token counts using CountVectorizer.
# Project X: Recommendation System for Udemy Courses

## Project Description and Objectives

Project X aims to develop a recommendation system for Udemy courses based on the course title and subject. The system will provide personalized course recommendations to users based on their preferred subject and learning level.

## Setting Up and Running the Project

To set up and run the project, follow these steps:

1. Download the [Project X [udemy_cources.csv].ipynb](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/9925081/1b6065f3-d857-427b-b2ef-84eec7f7b8a7/Project%20X%20%5Budemy_courses.csv%5D.ipynb) file.
2. Open the file in a Jupyter Notebook environment.
3. Run the cells in the notebook to preprocess the data, vectorize the course titles, and calculate the cosine similarity matrix.
4. Use the cosine similarity matrix to recommend courses based on the user's preferred subject and learning level.

## Recommendation Model and Rationale

The recommendation model used in this project is a content-based recommendation system. The rationale behind this choice is that the model can effectively capture the semantic meaning of the course titles and subjects, allowing for personalized recommendations based on user preferences.

The model first preprocesses the course titles by cleaning the text and converting them into a bag-of-words representation. It then calculates the cosine similarity matrix between the course titles to determine the similarity between them.

Finally, the model recommends courses based on the user's preferred subject and learning level. The recommendations are ranked based on the cosine similarity score, with the most similar courses appearing at the top of the list.

## Results Summary

The results of the recommendation system are evaluated based on the cosine similarity matrix and the quality of the recommendations provided to users. The model is able to effectively capture the semantic meaning of the course titles and subjects, resulting in personalized recommendations that are relevant to the user's preferences.

The evaluation metrics used in this project include the cosine similarity score and the relevance of the recommended courses to the user's preferences. The cosine similarity score ranges from 0 to 1, with higher scores indicating a higher degree of similarity between the course titles. The relevance of the recommended courses is evaluated based on user feedback and ratings.

Based on these evaluation metrics, the recommendation system is able to provide high-quality recommendations that are relevant to the user's preferences. The cosine similarity score is consistently high, indicating that the model is able to effectively capture the semantic meaning of the course titles and subjects. Additionally, user feedback and ratings indicate that the recommended courses are relevant and helpful to the user's learning goals.
