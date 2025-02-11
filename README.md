# Analysing-Students-Mental-Health

# Overview/Introduction

This project explores the impact of studying abroad on the mental health of international students. Using data from a Japanese international university, the analysis focuses on factors such as social connectedness, acculturative stress, and length of stay, and their relationship with depression levels among students. The goal is to provide insights into how these factors influence mental health and to offer recommendations for supporting international students.

# Objectives

- To analyse the mental health trends among international students compared to domestic students.
- To investigate the relationship between social connectedness, acculturative stress, and depression levels.
- To determine if the length of stay in a foreign country affects mental health outcomes.
- To provide actionable recommendations based on the findings.

# Data Source

The data used in this project was collected from a survey conducted by a Japanese international university in 2018. The dataset includes information on student demographics, language proficiency, academic level, length of stay, and mental health scores (PHQ-9 for depression, SGS for social connectedness, and ASISS for acculturative stress).

# Tools Used

- PostgreSQL: For querying and analysing the dataset.
- Google Colab: For running and documenting the analysis in a Jupyter Notebook environment.

# Insights

- International students exhibit higher levels of depression compared to the general population.
- Social connectedness and acculturative stress are significant predictors of depression among international students.
- The length of stay in a foreign country has a notable impact on mental health, with longer stays correlating with higher levels of acculturative stress and depression.

# Key Findings

- Students with shorter stays (1-2 years) tend to have lower depression scores but higher acculturative stress.
- Longer stays (5+ years) are associated with higher depression scores and slightly lower acculturative stress.
- Social connectedness scores are generally lower for students with longer stays, indicating a potential decline in social integration over time.

# Recommendations

- Universities should provide enhanced support systems for international students, particularly those in the early stages of their stay, to help them manage acculturative stress.
- Programs aimed at improving social connectedness, such as peer mentoring and cultural integration activities, should be prioritised.
- Regular mental health check-ups and counselling services should be made available to students, especially those with longer stays, to address rising depression levels.

# How to Use This Repository

- Clone the Repository: Start by cloning this repository to your local machine using git clone.
- Set Up PostgreSQL: Ensure you have PostgreSQL installed and running. Import the provided dataset into your PostgreSQL database.
- Run the Queries: Use the SQL queries provided in the notebook to replicate the analysis. The queries are designed to group data by length of stay and calculate average scores for depression, social connectedness, and acculturative stress.
- Explore the Notebook: Open the Jupyter Notebook (notebook.ipynb) in Google Colab or your local environment to view the analysis and visualisations.
- Contribute: Feel free to fork the repository, make improvements, or extend the analysis. Pull requests are welcome!
