# Predict_News_Authenticity___Deep_Learning_Project
## Project Description
In this project, we plan to build a model to identify whether a piece of news is fake or real for the news industry, such as the New York Times. The News company can utilize this tool to quickly identify the reliability of the news sources before releasing them to the public. 

This model could greatly reduce fact-checking hours and improve working efficiency. Moreover, it will help the company reduce man-hour cost and build a higher brand reputation by providing more accurate content.

## Model Description
In our dataset, each piece of news is constructed with title, text (the content of the news) and whether it’s fake or true. Thus, there are three possible ways to build our model:
- Use only title to predict authenticity
- Use only text to predict authenticity
- Use both title and text to predict authenticity

## Conclusions, Discussions, and Recommendations
Based on the results of three models, the model using both title and text got the highest accuracy. 

However, combining title and text as our model input occupies large space memory and lowers the running speed, which is time and money consuming. Thus, we would recommend the website to apply our first model, using only title to predict the authenticity. Although the “test & title” model has the highest accuracy (99.34%), the accuracy of the title model (96.8%) was not far from it. With smaller input size, this model runs much faster, and does not need too much space memory. It’s a much more cost-effective choice for the company.
