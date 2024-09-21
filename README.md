# ScoreWell

## Overview

The **ScoreWell** is a Python-based web application built using the **Streamlit** framework. This app allows students to track their performance across multiple subjects by adding quizzes, tests, and projects, while comparing their own scores to the class average and competitor marks. The application also offers various analytical insights and visualizations such as student vs. competitor comparisons and subject-wise performance analysis.

## Key Features

- **Add Subjects**: Allows users to create and manage multiple subjects.
- **Add Evaluation Types**: For each subject, users can define tests or projects and input relevant scores.
- **Competitor Tracking**: Users can add competitor profiles and input their scores to compare performance in each evaluation.
- **Class Average Comparison**: Compare personal performance to class averages for better insights.
- **Dashboard**: View a detailed dashboard with visual comparisons, performance trends, and distribution of evaluation weightage.

## How to Use

1. **Add Subjects**: Start by adding the subjects for which you want to track scores.
2. **Add Evaluations**: After adding a subject, define tests or projects for that subject, and input relevant details like your score, class average, etc.
3. **Add Competitors**: You can add competitor profiles and input their scores for comparison.
4. **Dashboard**: Access the dashboard for visual analysis of your performance vs. competitors and the class average.
5. **Save Data**: All data is stored locally in `student_scores.xlsx` for performance tracking and `competitors.xlsx` for competitor profiles.

## Visualizations

The dashboard provides the following visualizations:

- **User vs Competitors Bar Chart**: Compares your scores to those of competitors across different tests and projects.
- **Weightage Distribution Pie Chart**: Shows the weightage of each test/project within a subject.
- **User vs Class Average Line Graph**: Compares your marks to the class average across evaluations.

## Dependencies

- Python 3.7+
- Streamlit
- Pandas
- Openpyxl
- Plotly
