#  airbnb prices prediction
Introduction
Airbnb is a large marketplace where hosts can put their spare real estate on, and rent to guests in a
short term. The pricing strategy of the accommodation depends on the host. However, unlike the hotel
business, these hosts lack the domain knowledge and professional management strategy in the
hospitality industry. (Gibbs, C. et al., 2018) If there is a pricing recommendation tool, the host can
have a better understanding about the possible prices they can offer.
This report collected the information of 1000 real estate the host on Airbnb provides in the great
Sydney area. Those information includes review scores, requirements, location and house conditions
data. After handling and analysing those data, the main idea is to use these data to build the best
models in order to estimate the price. In the process of trying different models, the relationship
between the price and the information can be seen and presented in the report. Eventually, the
stacking model performed at a lowest RMSE of 52.49.

Analysis and conclusions

Exploratory analysis of data shed some light on the relevance of some features and price. The overall
price in the dataset is right skewed that indicates the hosts need to compete with more hosts if they set
their price lower. The most expensive 100 accommodations are located along the coast and the most
affordable 100 ones are mainly located in the less popular area to the tourist. The rating review is
average higher when the accommodations have more bedrooms, or are allowed to accommodate more
guests by the host. Although these findings are presented in the model, they still can also be taken into
consideration on the hosts’ pricing and management strategy.
As for the methodology, the stacking model is the final model chosen by this report since it generates
the lowest RMSE, providing the most accurate predictions amongst all other operated models,
although it may suffer from high computational costs, it is still regarded as the best model. The Root
Mean Square Error (i.e. RMSE) is our primary consideration when making this decision. The figure
for the stacking algorithm is 52.4, which can be regarded as reasonable to do the forecast on the
offering prices.
However, there are also two unavoidable limitations that restrict the effectiveness of the model and
the results, therefore making the model and results less convincing. During the data processing phase,
the original training dataset contains only 1000 observations, the same as the figure for the test set. A
small number of observations provide less space to do the model fitting and have a higher probability
to produce biased predictions, but cross validation strategy has been used to reduce that impact. The
other problem occurred after handling missing data, some null values were replaced by modes,
medians, means or text information and so forth. No matter what type of data was filled there, there 
was no way to be aware of the real ideas behind them, instead, they are just some subjective
assumptions that can produce errors.
