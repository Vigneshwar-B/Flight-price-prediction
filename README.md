![output](https://user-images.githubusercontent.com/104056311/211298522-27cc33ec-e4e4-4959-824c-3267d9827fd2.png)
With the recent global economic difficulties and tech layoffs, many people have been faced with financial difficulties and every dollar now matters more than ever. Many industries are forced to adjust the prices of their commodities quite rampantly and unpredictably, leaving consumers in dismay. The airline industry is one of the few domains with most sporadic pricing. This makes it very difficult for consumers who want to save money due to their current financial situation. In this project, I used machine learning to help airline customers predict the price of an air ticket within India based on features such as the source of the travel, the destination of the travel, the departure date, the arrival date, the type of airline and the number of stoppages if any. I used 5 different supervised machine learning models to make the prediction of the flight prices. The result of these 5 models are:
●	ExtraTreesRegressor (79%)
●	RandomForestRegressor(80%)
●	CatBoostRegressor(83%)
●	LGBMRegressor (80%)
●	XGBRegressor (82%)

As a final step, after evaluating the performance of all these models, I proceeded with XGBoost which outperformed the other 4 models. In order to make the model more accessible for consumers, I deployed the model via the Heroku cloud platform.
This project is an eye opener and helping Indian citizens to better make decisions was a great achievement. Overall the data analysis and machine learning model building was a great lesson to go through. The data extraction part was the most part that I learnt the most and hope to learn more in further projects.
