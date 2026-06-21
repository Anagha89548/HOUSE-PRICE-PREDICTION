# 🏠House Price Prediction
This project focuses on predicting house prices using machine learning techniques based on various property features such as area, number of bedrooms, bathrooms, furnishing status, and location-related attributes. The dataset was first explored to understand its structure, check for missing values, and identify important variables affecting house prices. Categorical variables such as main road access, guestroom availability, basement presence, air conditioning, and furnishing status were converted into numerical form using encoding techniques to make the data suitable for machine learning models.

During exploratory data analysis, it was observed that area is the most significant factor influencing house prices, followed by features such as bathrooms, air conditioning, parking availability, and preferred location. Surprisingly, the number of bedrooms had a weaker impact on price compared to other features, indicating that size and amenities are more important than just room count. The correlation heatmap further confirmed that house price has a strong positive relationship with area and moderate relationships with several comfort-related features.

Two machine learning models were used for prediction: Linear Regression and Random Forest Regression. Linear Regression provided a basic understanding of relationships but showed higher error due to its assumption of linearity. In contrast, Random Forest Regression performed better by capturing complex, non-linear relationships between features. Evaluation metrics such as MAE, RMSE, and R² score showed that Random Forest had lower error and higher accuracy, making it a more reliable model for this dataset.

Visualization techniques such as scatter plots, histograms, and correlation heatmaps helped in understanding data distribution and relationships between variables. The actual vs predicted price graph showed that Random Forest predictions were closer to actual values compared to Linear Regression.

### House Price Distribution Analysis
<img width="841" height="547" alt="chart1" src="https://github.com/user-attachments/assets/68cb8a7b-4fdc-4473-8734-651a46f8e49a" />


The house price distribution chart shows that most properties are concentrated in the low to mid-price range, while a smaller number of houses have very high prices. This creates a right-skewed distribution, indicating the presence of expensive properties that act as outliers. The concentration of houses in the lower price range suggests that affordable and mid-range homes are more common in the dataset. The high-priced outliers are likely influenced by factors such as larger area, better location, more bathrooms, parking facilities, and premium amenities. This distribution highlights that house prices are not evenly spread and are affected by multiple property characteristics. Understanding this pattern is important for building accurate prediction models and identifying factors that contribute to higher property values.

### Correlation Patterns of House Features and Price Outcomes
<img width="1116" height="889" alt="chart2" src="https://github.com/user-attachments/assets/fa384549-327a-4028-85f3-d01a98d9e9a1" />


The correlation heatmap reveals the strength and direction of relationships between house price and other features. Notably, the house price shows a strong positive correlation with area, meaning larger properties tend to command higher prices. Bathrooms and air conditioning also exhibit moderate positive correlations, indicating that additional amenities increase value. Interestingly, the number of bedrooms has a weaker correlation, suggesting that total size and comfort features matter more than bedroom count alone. Overall, the heatmap highlights which features have the greatest influence on price and helps prioritize them in predictive modeling, ensuring we focus on the most impactful variables.
### Analysis of Actual vs. Predicted House Prices
<img width="691" height="547" alt="chart3" src="https://github.com/user-attachments/assets/94e5e91f-3883-4ae5-a9d3-25dec9dc3df1" />

The actual versus predicted house price chart illustrates how well our model predicts the real market values. Each point represents a property, with its actual price on the vertical axis and the predicted price on the horizontal axis. Ideally, points should cluster around the diagonal line, indicating accurate predictions. We see that most data points are close to this line, suggesting good performance. However, a few outliers are observed, especially at the higher price range, where the model underestimates or overestimates some values. This suggests that while the model is generally effective, some complex or extreme cases may require further refinement.

Overall, the chart demonstrates that the model has successfully captured the relationship between property features and house prices. The close alignment of most points with the diagonal line indicates that the predictions are reliable for the majority of properties. The presence of a few prediction errors may be due to factors not included in the dataset or unique property characteristics. Despite these variations, the model provides a strong foundation for house price prediction and can support real estate decision-making with a reasonable level of accuracy.

### Analysis of Price vs. Area Correlation
<img width="691" height="547" alt="chart4" src="https://github.com/user-attachments/assets/d21d4382-5412-4288-ab2b-ea82148e5e02" />

The Price vs. Area scatter plot shows a clear positive relationship between property area and house price. As the area of a house increases, its price generally tends to increase as well. Most of the data points follow an upward trend, indicating that larger properties are usually more expensive. However, some houses with similar areas have different prices, suggesting that other factors such as location, number of bathrooms, parking facilities, air conditioning, and furnishing status also influence house value. A few outliers can be observed where properties are priced significantly higher or lower than expected for their size. Overall, the scatter plot confirms that area is one of the strongest predictors of house price and plays a major role in determining property value.


In conclusion, this project demonstrates that house prices are influenced by multiple factors, with area and amenities playing the most important role. Machine learning models, especially Random Forest, provide more accurate and practical predictions compared to traditional methods. This approach can help real estate businesses make better pricing decisions, avoid errors, and improve customer satisfaction.
