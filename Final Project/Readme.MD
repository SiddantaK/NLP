# Music Genre Prediction Project

This GitHub repository hosts a project aimed at predicting the genre of songs using a range of machine learning models. Additionally, it provides insights into handling alcohol-related issues within the context of the project. Below, you will find a brief overview of the project's objectives, methods, and key findings.

## Project Overview

The primary objective of this project is to develop and evaluate machine learning models for predicting the genre of songs based on their lyrics. The project explores various models, including Support Vector Machines (SVM), logistic regression, and transformer models. The focus extends to analyzing the impact of different time periods on prediction performance.

## Dataset

The project utilizes a comprehensive dataset of song lyrics, encompassing a certain time. The dataset contains around 3.3 million songs after data preprocessing. Different timelines are considered, such as post-2020 and 2010-2017, to investigate potential biases introduced by time-based segmentation.

Download the dataset from the kaggle (https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information), then manage the path and you are good to go.

## Implementation Steps

1. **Data Preprocessing**: The dataset undergoes essential preprocessing steps, including removal of special characters, tokenization, stop words removal, and lemmatization.

2. **Model Implementation**: Various machine learning models are implemented, including SVM, logistic regression, and transformer models. Different timelines are considered to assess model performance across time periods.

3. **Training and Evaluation**: Models are trained using varying sample sizes, ranging from 10% to 100% of the dataset. Performance metrics, such as accuracy, precision, recall, and F1-score, are calculated to evaluate the models.

## Alcohol-Related Considerations

Given the sensitivity of certain themes, such as alcohol-related content in song lyrics, this project addresses potential ethical and social implications:

1. **Ethical Handling**: Lyrics containing explicit references to alcohol or substances are handled responsibly, with a focus on respectful content handling during data preprocessing and analysis.

2. **Transparency**: The project maintains transparency by addressing alcohol-related content as part of the data exploration and analysis process, highlighting its potential impact on model predictions and dataset bias.

## Repository Structure

- `data`: Contains the datasets used in the project.
- `code`: Includes Jupyter notebooks detailing data preprocessing, model implementation, and evaluation.
- `results`: Holds the outcome of model predictions and performance metrics.
- `documentation`: Provides additional documentation, such as the project plan and presentation slides.

## Key Takeaways

This project underscores the importance of understanding model performance in varying contexts and timelines. It serves as a resource for exploring machine learning techniques for genre prediction while acknowledging and addressing sensitive content within the dataset.

For more details, please refer to the provided Jupyter notebooks and documentation within this repository. Your contributions and feedback are highly welcome!
