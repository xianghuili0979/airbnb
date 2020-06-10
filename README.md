# airbnb
Nowadays, with the development of internet, it is an increasing number of companies would like to do business and customers would like to purchase product online. It is common that customers leave their comment online that recommend this product or not. And individual customers would like to check product review of existing user to make purchase decision.  Therefore, by analysing consumer options towards their product, the thesis of this paper is that help companies understand customers’ reviews and improve their business. 
In order to demonstrate this proposition, this paper will separate into three parts. The first section is exploratory data analysis that plot the graph of related variable to understand the customer behaviour after cleaning and reformatting training and test data set. 
The second section is to build and evaluate a benchmark model based on ‘Review text’ by applying the Bag-Of-Words method. According to the analysis of the benchmark model's evaluation result, which leads to next section: improve the model. 
The third section is to focus on improving the model to predict a better result. The first step to improve the model is to add new features based on analysing correlated factors with customers' 'Recommend' willingness. .In model validation, we use the GridSearchCV function to find the best estimators for the model. Then we retain the new model and use cross validation to evaluate the performance of the model. After doing features engineering and applying the best parameters into the model, we find that the performance is better than the benchmark model. Then we use the predicted variable coefficients of the “Recommended” to plot the graph. The elder people are more likely to recommend products with other, and jackets are the most popular type. If the rating is 5.0, then the product is more likely to be recommended to others.

In conclusion, by applying the IT tool (Python) to analyse the customers’ data, guided by the business knowledge and objectives, this project digs deep insights into customers' buying experience, discuss the factors that would affect their buying behaviour, and most importantly, building and improving a predictive model to understand what affects a customer's recommend willingness. This project helps the company to understand their customers and make better decisions that will improve their business.
Based on our analysis, we have identified several influential factors to analyse customers recommend willingness, such as rating_accuracy, negative word counts, and rating_excellent. These correlated features are generated via our improving model, to gain more accurate and deeper insights to understand customers' buying experiences. Also, the improving model has achieved a higher F1 score of 0.961721 compared with the benchmark model of 0.931538. In general, the improving model provides a more efficient method for the company to predict customers recommend willingness, thereby drawing insight from it.

For suggestions, company can pay more attention to fashion style more closely to customers who are above 30 years old as they are the main customer group. As for type, company should review the pants product to find out why customers dissatisfied with this type most. In terms of departments, the intimate department performed the worst. From the word cloud, we can also find out that customers are not happy are mainly because some products run too large, the fabric quality is bad. Company can try to discuses these issues with suppliers or change to better suppliers.

Combine with the analysis is given in the report, for the company's further actions, they should target to understand the potential and importance of the correlated factors with customers' buying decisions, paying attention to influential factors of customers recommend decisions, and most importantly, take actions on how to improve customers' buying experience to make a long-term sustainable business.