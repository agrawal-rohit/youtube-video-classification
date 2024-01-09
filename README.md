# Youtube Video Classification Analysis

## Overview
This project explores the application of various text classification techniques to categorize YouTube videos based on their titles and descriptions. We investigate methods like Naive Bayes, Support Vector Machines (SVM), AdaBoost, and Long Short-Term Memory (LSTM) networks.

Detailed methodology and insights can be found in [this Medium article](https://towardsdatascience.com/analyzing-text-classification-techniques-on-youtube-data-7af578449f58).

## Categories
The analysis focuses on classifying videos among:
- Travel Blogs
- Science and Technology
- Food
- Manufacturing
- History
- Art and Music

## Data Collection
Data was sourced using the **YouTube API(v3)**, targeting videos from the above categories. The collected metadata is compiled in 'Collected_data_raw.csv'.

## Methodology
- **Data Preprocessing:** Standardizing and cleaning text data for model input.
- **Model Training:** Implementing and tuning different classification models.
- **Evaluation Metrics:** Using appropriate metrics to assess model performance.

## Performance Analysis

We present a comparative analysis of each model's performance, highlighting strengths and areas for improvement. Visualizations included in the README illustrate the effectiveness of each technique.

![Naive Bayes](https://user-images.githubusercontent.com/29514438/57171835-0a344d80-6e36-11e9-9a25-ba1a42791ba0.png)

![Support Vector Machine](https://user-images.githubusercontent.com/29514438/57171839-220bd180-6e36-11e9-9720-148582303bbd.png)

![1_shYMumLw6hchAks1RHzC4w](https://user-images.githubusercontent.com/29514438/57171847-364fce80-6e36-11e9-9bd6-087bf4b6e01e.png)

![1_7Ps1tyjPpfvgtLCn26i6tw](https://user-images.githubusercontent.com/29514438/57171849-410a6380-6e36-11e9-800f-387f31e8b10f.png)

## Results and Model Ranking

Our analysis yielded a clear ranking of classifiers based on their performance:
1. **LSTM (Long Short-Term Memory):** Demonstrated exceptional capability in handling Natural Language Processing tasks, outperforming other models due to its advanced structure capable of learning long-term dependencies.
2. **SVM (Support Vector Machine):** Showed robust performance with good feature interaction learning, though not as effective as LSTM.
3. **Naive Bayes:** Performed moderately, limited by its assumption of feature independence.
4. **AdaBoost:** The least effective, possibly due to suboptimal hyperparameter settings in the default model.

This ranking highlights the strengths of deep learning approaches like LSTM in text classification tasks.
