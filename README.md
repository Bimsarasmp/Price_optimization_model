This project aims to optimize pricing strategies for diverse product categories using historical sales
data. By identifying patterns, trends, and key factors influencing pricing and demand, we will
develop a pricing optimization model. The model will empower our client to make informed
decisions, maximizing revenue and profitability while staying competitive in the market. The
deliverables include a data analysis report, a functional pricing optimization model, and
comprehensive documentation for seamless implementation.
![image](https://github.com/Bimsarasmp/Price_optimization_model/assets/139919035/4e4334c6-5099-41ee-b25f-076a24786a6d)
Dataset: https://www.kaggle.com/datasets/suddharshan/retail-price-optimization
Our price optimization project aimed to develop an effective model to predict the 'unit_price_log'
and optimize prices for enhanced profitability. After conducting a comprehensive analysis, we have
gathered essential insights to inform our pricing strategies. Below are the key findings from our
study:
1. Competitor Price Analysis:
The Interquartile Range (IQR) for competitor 1 and competitor 3 prices is slightly smaller than that
of the company's unit_price and freight_price. Additionally, both competitor 1 and competitor 3
prices show a slight left skewness. These observations suggest that competitor prices may play a
significant role in shaping our pricing decisions, and we must carefully analyze our pricing
strategies relative to competitors to remain competitive in the market.
2. Monthly Sales by Category:
Our analysis of the heat map of monthly sales by category revealed interesting patterns. In
November, the highest sales were observed in the 'Garden_tools' category, while in February,
'Computer_accessories' recorded the highest sales. In May, the 'Watches_gifts' category dominated
in terms of monthly sales. Understanding the seasonal variations in product categories can help us
develop targeted pricing strategies to capitalize on high-demand periods.
3. Product Score Analysis:
A box plot comparing our product's score distribution with that of competitors (1 and 2) showed
that our product scores range from 3.5 to 4.5. Meanwhile, both competitors 1 and 2 exhibit a
smaller Interquartile Range (IQR) ranging from 4.0 to 4.5. This finding highlights an area for
improvement, as enhancing our product scores might positively influence pricing strategies and
customer perception.
4. Gradient Boosting Regressor Performance:
Our implementation of the Gradient Boosting Regressor model has yielded highly promising
results. The model achieved low Mean Squared Error (MSE) values of 0.0088 for both test and
training datasets. Additionally, the R-squared (R2) values were close to 0.98 for both evaluations,
indicating that the model effectively captures a large portion of the variance in the 'unit_price_log'
values. The Mean Absolute Percentage Error (MAPE) values were relatively low, around 6.88%,
suggesting that the model's predictions have a small average percentage error.
5. Feature Importance:
The feature importance analysis of the Gradient Boosting Regressor highlighted several crucial
features. 'Product_weight' was the most influential feature, followed by 'competitor 1 price' and
'total_price'. Understanding the significance of these features allows us to focus on their respective
impacts and make informed pricing decisions.
