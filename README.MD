# Resume Screening & Candidate Ranking System

## Project Overview

This project is a Machine Learning and Natural Language Processing (NLP) based Resume Screening and Candidate Ranking System. The goal of this project is to automate the resume screening process, classify resumes into different job categories, rank candidates based on job requirements, and identify skill gaps.

The dataset contains 2484 resumes belonging to 24 different job categories. The resume text was cleaned and preprocessed by removing unwanted characters, special symbols, and extra spaces. The cleaned text was then converted into numerical features using TF-IDF Vectorization.

For resume classification, a Linear Support Vector Machine (Linear SVM) model was trained using a train-test split approach. The model achieved an accuracy of approximately **73%**, showing a significant improvement over baseline models. Model performance was evaluated using accuracy score, classification report, and confusion matrix.

To make the system more practical for recruitment, a candidate ranking module was implemented using Cosine Similarity. A job description containing required skills was compared with resumes, and candidates were ranked according to their similarity scores.

Additionally, a Skill Gap Analysis feature was developed to identify missing skills by comparing required skills with candidate skills. Visualizations such as bar charts and confusion matrices were generated to better understand model performance and ranking results.

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* NumPy
* Matplotlib
* NLP Techniques
* TF-IDF Vectorization
* Linear SVM

## Features

* Resume Text Cleaning & Preprocessing
* TF-IDF Feature Extraction
* Resume Classification using Linear SVM
* Candidate Ranking using Cosine Similarity
* Skill Gap Analysis
* Accuracy Evaluation
* Confusion Matrix Visualization

## Results

* Successfully classified resumes into 24 job categories.
* Achieved **73% accuracy** using Linear SVM.
* Ranked candidates based on job description relevance.
* Identified missing skills through skill gap analysis.
* Generated visual insights using charts and confusion matrix.

## Conclusion

This project demonstrates the use of Machine Learning and NLP in automating resume screening, candidate ranking, and skill evaluation. The system can assist recruiters in reducing manual effort and improving the candidate selection process.
