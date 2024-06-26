# PGA Tour Advanced Analytics
This project endeavors to revolutionize PGA Tour predictions by combining traditional machine learning approaches with cutting-edge in-context learning techniques, utilizing tools like ChatGPT's Advanced Data Analysis, Claude, and Microsoft Copilot. Moving beyond conventional analytics, the project aims to accurately predict tournament outcomes, demonstrating the advanced capabilities of large language models in transforming sports analytics.

## Important Links
Final Project Writeup: https://github.com/vanderbilt-data-science/pga-tour-advanced-analytics/blob/main/Final%20Project%20Writeup.pdf

Final In-Context Learning Prompts: https://github.com/vanderbilt-data-science/pga-tour-advanced-analytics/blob/main/Final%20In-Context%20Learning%20Prompts.pdf

Project Board: https://github.com/orgs/vanderbilt-data-science/projects/63/views/1

Issues: https://github.com/vanderbilt-data-science/pga-tour-advanced-analytics/issues

## Project PI/Project Team 

Zach Printz, zachary.h.printz@vanderbilt.edu, printzzh, PI

## Project Proposal  

### Description of Problem/Opportunity
Predicting outcomes in professional golf, particularly on the PGA Tour, is a formidable challenge. The sport is characterized by significant week-to-week variability and a myriad of external factors that uniquely affect each player, making the task of accurately forecasting the winner of any given tournament exceptionally difficult. While predictive analysis in golf has been extensively explored, it has yet to be mastered. New technological developments with regards to large language models open up new avenues for advanced data analysis. Traditional predictive models have been successful but often fall short in deciphering the complex patterns and nuances inherent in golf data. This presents a unique opportunity to apply more sophisticated and modern techniques, such as in-context learning, to not only enhance prediction accuracy but also to test these methods against established machine learning approaches. The project aims to explore these cutting-edge methodologies, assessing their potential to redefine predictive analytics in golf and potentially influence the future of sports analytics.

### Proposed Solution/Approach
For this project, I propose a two-pronged approach to analyze data from the PGA Tour, with an emphasis on exploring both traditional machine learning models and innovative in-context learning techniques.

   1. Traditional Machine Learning Analysis: Initially, the project will utilize data directly sourced from the PGA Tour website, focusing on strokes gained and other relevant performance metrics. This phase will involve the application of established machine learning methods such as linear regression, random forest, gradient boosting, and others. The aim is to establish a baseline predictive model by leveraging these traditional approaches.
   2. In-Context Learning Analysis: Subsequent to the traditional model, the project will shift focus to explore the capabilities of in-context learning. This approach will involve utilizing a suite of large language model tools, including ChatGPT Advanced Data Analysis, Claude, and Microsoft Copilot, each offering unique capabilities in processing PGA Tour data. This type of model has the potential to be a strong, emerging data analysis tool, so long as the large language model can immediately learn from examples. Due to the vast amount of data involved, this project may require the use of a large context window model. The overarching goal is to critically assess whether this modern, multi-tool large language model approach can surpass traditional methods, not only in prediction accuracy but also in the depth and relevance of insights generated.

Throughout the project, the  capabilities of large language models will play a crucial role in autonomously determining the most effective analysis techniques, adapting to the nuances of the PGA Tour data. This flexible and dynamic model selection is aimed at enhancing the overall accuracy of predictions and pushing the boundaries of what is possible in sports analytics. The ultimate objective is to compare the effectiveness of these two distinct methodologies in predicting PGA Tour outcomes, potentially paving the way for a new era in predictive analytics within the realm of professional golf.


### Project Outline and Timeline
Data Collection and Pre-Processing (1/8 - 1/14): Collect data from the PGA Tour website for the 2023 season. Tasks include cleaning, structuring, and preparing the data, with a focus on addressing missing values, outliers, and data normalization.

Initial Model Selection (1/15 - 1/21): Introduce the cleaned data to large language models like ChatGPT Advanced Data Analysis. This phase is dedicated to determining the best traditional machine learning method based on large language model recommendations.

Model Refinement and Finalization (1/22 - 1/28): Refine and optimize the chosen model. This involves parameter adjustments and feature experimentation to enhance predictive accuracy.

In-Context Learning Setup (1/29 - 2/11): Begin setting up the in-context learning model. This includes configuring tools like Claude for PGA Tour data analysis and calibrating the model to handle the specific complexities of the dataset.

In-Context Learning Implementation and Adjustment (2/12 - 3/10): Implement the in-context learning model, with ongoing adjustments and refinements. This period is vital for testing and fine-tuning the model based on initial outputs and performance.

Comparative Analysis and Prediction (3/11 - 3/31): Use both the traditional and in-context learning models to predict outcomes of the first 15 PGA Tour events of the 2024 season. This phase focuses on running and comparing the models side by side.

Validation and Assessment (4/1 - 4/14): Assess the effectiveness of both models by comparing their predictions with actual PGA Tour outcomes, analyzing accuracy, and model strengths.

Project Finalization and Documentation (4/15 - 4/22): Conclude the project by consolidating all findings. Finalize the models based on validation feedback, and document the project's insights, learnings, and recommendations.

## Goals of Project 

   1. High Accuracy in Traditional Model Predictions: Achieve a high level of predictive accuracy using traditional machine learning methods. This goal is centered on effectively forecasting player finishes in PGA Tour events using established data analysis techniques.
   2. High Accuracy in In-Context Learning Model Predictions: Attain similar or superior predictive accuracy with the in-context learning model. This emphasizes exploring the potential of modern large language model methodologies in sports predictions.
   3. Comparative Analysis for Broad Methodological Insights: Determine which method, traditional machine learning or in-context learning, is more effective for predictive analysis in golf, with an eye towards the wider applicability of these findings. The goal is not only to identify the superior approach for golf but also to provide insights that could be generalized to other sports or domains where predictive analytics play a key role.
   4. Demonstration of Large Langugage Model Capabilities: Illustrate the capabilities of various large language models such as ChatGPT Advanced Data Analysis, Claude, and Microsoft Copilot in handling complex sports analytics tasks. This aims to highlight the adaptability and efficiency of large langugage models in providing deep, actionable insights in the field of sports analytics.


## Project Metrics 

The project will use Normalized Discounted Cumulative Gain (NDCG) to evaluate the performance of the models. This metric was chosen due to NDCG's ability to measure the entirety of a predicted tournament's leaderboard, while placing an emphasis on the top positions, which are the most important. The NDCG score is calculated based on the entire predicted leaderboard compared to the actual results. Higher scores indicate better performance, especially at the top of the leaderboard.

### Traditional Machine Learning Approach:

   1. Accuracy in Predicting the Tournament Leaderboard:
   
         A: Model achieves an NDCG score of 0.75 or above 10/15 times or more.

         B: Model achieves an NDCG score of 0.75 or above 7/15 times or more.

         C: Model achieves an NDCG score of 0.75 or above 4/15 times or more.

         D: Model achieves an NDCG score of 0.75 or above 1/15 times or more.

         F: Model never achieves an NDCG score of 0.75 or above.

### In-Context Learning Approach:

   1. Accuracy in Predicting the Tournament Leaderboard:
   
         A: Model achieves an NDCG score of 0.75 or above 10/15 times or more.

         B: Model achieves an NDCG score of 0.75 or above 7/15 times or more.

         C: Model achieves an NDCG score of 0.75 or above 4/15 times or more.

         D: Model achieves an NDCG score of 0.75 or above 1/15 times or more.

         F: Model never achieves an NDCG score of 0.75 or above.

