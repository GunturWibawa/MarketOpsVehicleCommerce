# MarketOpsVehicleCommerce

The project assigned to me during the twelfth sprint involves Numeric Methods.

Throughout this sprint, I dived into numerical methods on its key principles such as gradient descent, gradient ascent, and neural networks.

# **Project Insight**

Rusty Bargain, a used cars seller company, is in the midst of developing an application to engage new buyers. Within this application, users can ensure the market price of various vehicles. I have access to a comprehensive set of historical data encompassing specifications, versions, and pricing of vehicles. My objective is to formulate a model that accurately determines the value of a car. Rusty Bargain's areas of interest include:

1. The precision of predictions;
2. The efficiency of the model in rendering predictions;
3. The time needed to train the model.

Upon a further analysis, it can be concluded that models which employed the gradient boost method (such as LightGBM) furnish superior predictions, as evidenced by the result of RMSE values. When evaluated with respect to prediction accuracy, LightGBM stands out as the preeminent model, trailed by Random Forest, Decision Tree, and finally LinearRegression. Nonetheless, LightGBM demands the most extensive processing time compared to the others, so if judged on all-encompassing performance, the hierarchy of models is LightGBM, Random Forest, Decision Tree, with Linear Regression at the bottom.

Drawing from the comprehensive analysis conducted, my advice to Rusty Bargain would be to adopt a gradient boosting model like XGBoost, LightGBM, or CatBoost for the development of their car price prediction model.

However, we can consider the model's processing time is essential for the overall user experience. Users anticipate an application that is not only fast but also responsive. Although LightGBM might offer the pinnacle of accuracy, its long processing time could ended in a slow application, thereby reducing the user experience.

Consequently, Rusty Bargain may wish to consider models with faster processing time, such as LightGBM or CatBoost, to guarantee a satisfying user experience. These models have demonstrated commendable accuracy coupled with faster processing time, which can translate into a more agile application that aligns with user expectations.
