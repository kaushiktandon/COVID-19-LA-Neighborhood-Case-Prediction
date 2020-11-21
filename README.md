# COVID-19-LA-Neighborhood-Case-Prediction

CSCI 499: AI for Sustainable Development Final Project
Jackie Dong, Katherine Sing, Kaushik Tandon

# Abstract
As the COVID-19 pandemic continues, it is necessary to predict the number of positive cases a community might expect in order to create and employ the most effective prevention strategies. Previous positive cases, mobility data, and demographics of a given neighborhood may play a significant role in the number of cases that occur in that neighborhood. We explore different regression models for predicting the spread of COVID-19 among Los Angeles neighborhoods in a given month. We combine dynamic COVID-19 cases data with static features such as census data, employment statistics, and nursing home data to build a more complete picture of how the virus spreads and to predict the number of cases in the next month. We find an increase in model accuracy when using static and dynamic features rather than solely dynamic features. We experiment with different training window size splits and find higher accuracies with larger window sizes.