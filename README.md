# Smartphone-sales-dataset
Analyzing and deriving insights from sales of smartphones across the globe.
The dataset contains information about top-rated smartphones on Amazon for the year 2021. Here are the columns present in the dataset:

Smartphone: Name and specifications of the smartphone.
Rating: Customer rating, formatted as 'X.X out of 5 stars'.
Reviews count: The number of reviews for the smartphone.
Offer price: The price at which the smartphone is offered.
Actual price: The original price of the smartphone.
Saving: The amount saved and the percentage discount.
Delivery: Information about the delivery.
Status of stock & more offers: Additional information about the stock status and offers, if any.
To derive insights and relationships from this dataset, we can consider several analyses:

Rating Analysis: Understand the distribution of ratings and identify the highest and lowest-rated smartphones.
Price Analysis: Compare offer prices and actual prices, and analyze the discounts provided.
Popularity Analysis: Based on the number of reviews, determine the most and least popular smartphones.
Correlation Analysis: Explore correlations between variables like rating, price, and the number of reviews.
Before proceeding, we need to clean and preprocess the data, especially converting ratings, review counts, and prices to numerical formats for analysis.
I then proceeded with these analyses:
Rating Analysis: We'll look at the distribution of ratings and identify the highest and lowest-rated smartphones.
Price Analysis: We'll compare the offer and actual prices, and analyze the extent of discounts provided.
Popularity Analysis: Based on the number of reviews, we'll determine the most and least popular smartphones.
Correlation Analysis: We'll explore any correlations between variables like rating, price, and the number of reviews.
Rating Analysis
The distribution of ratings shows the following:

The majority of smartphones have ratings between 4.0 and 4.6.
The average rating across all smartphones is approximately 4.35.
The ratings are relatively consistent, with a standard deviation of about 0.33, indicating that most smartphones have similar ratings.
There are some smartphones with perfect ratings of 5.0, though they are fewer in number.
Price Analysis
Offer Price vs Actual Price:

The scatterplot shows a positive correlation between offer and actual prices. This suggests that higher-priced smartphones also tend to have higher offer prices.
There are some outliers where the offer price is significantly lower than the actual price, indicating substantial discounts.
Distribution of Savings Percentage:

The histogram of savings percentage indicates that most discounts fall within the range of 10% to 30%.
There are some instances of very high discounts (up to 80%), but these are less common.
Summary Statistics:
Offer Price: Ranges from a minimum of ₹50 to a maximum of ₹180,890, with a mean of approximately ₹24,496.
Actual Price: Ranges from ₹299 to ₹184,800, with a mean of around ₹27,783.
Savings Percentage: Varies from 1% to 80%, with an average discount of approximately 20%.
Next, I will proceed with the Popularity Analysis, based on the number of reviews, to determine the most and least popular smartphones. ​​

Popularity Analysis
Based on the number of reviews, we can gauge the popularity of the smartphones. Here are the findings:

Most Popular Smartphones:
Samsung Galaxy M31 (Ocean Blue, 8GB RAM, 128GB Storage) - 243,715 reviews, Rating: 4.3
Samsung Galaxy M31 (Space Black, 8GB RAM, 128GB Storage) - 243,715 reviews, Rating: 4.3
Samsung Galaxy M21 2021 Edition (Arctic Blue, 6GB RAM, 128GB Storage) - 170,469 reviews, Rating: 4.2
Samsung Galaxy M21 2021 Edition (Charcoal Black, 4GB RAM, 64GB Storage) - 170,469 reviews, Rating: 4.2
Samsung Galaxy M21 2021 Edition (Arctic Blue, 4GB RAM, 64GB Storage) - 170,469 reviews, Rating: 4.2
Least Popular Smartphones:
MOTOROLA G40 Fusion (Frosted Champagne, 128 GB) (6 GB RAM) - 1 review, Rating: 5.0
DIZO Star 300 Black - 1 review, Rating: 5.0
Micromax X389 (Black+Grey) - 1 review, Rating: 5.0
Lava A3 Dark Blue/Grey - 1 review, Rating: 4.0
Nillkin Case for Apple iPhone 12 / iPhone 12 Pro CamShield Silky Silicone - 1 review, Rating: 5.0
These results suggest that certain models, particularly those from Samsung, are significantly more popular in terms of review counts. This could indicate a higher sales volume or a greater level of customer engagement.
Correlation Analysis
The correlation matrix provides insights into how different variables in the dataset are related to each other:

Rating:

Positively correlated with Offer Price (0.15) and Actual Price (0.13), suggesting slightly higher-rated products might be priced higher.
Positive correlation with Saving Percentage (0.18), indicating that products with higher discounts might have slightly higher ratings.
Negative correlation with Reviews Count (-0.13), suggesting that more popular products (in terms of reviews) might have slightly lower ratings.
Reviews Count:

Negatively correlated with Rating (-0.13), Offer Price (-0.05), and Actual Price (-0.04). This suggests that more expensive and highly-rated products tend to have fewer reviews.
Negative correlation with Saving Percentage (-0.15), indicating that products with higher discounts tend to have fewer reviews.
Offer Price and Actual Price:

Very strongly correlated with each other (0.99), as expected.
Both have a negative correlation with Saving Percentage, suggesting that higher-priced products may have lower percentage discounts.
Saving Percentage:

Negatively correlated with Offer Price (-0.36) and Actual Price (-0.30), meaning that higher-priced products might offer lower percentage discounts.
Positive correlation with Rating (0.18), indicating products with higher discounts could have slightly higher ratings.
These correlations help in understanding the underlying dynamics of the dataset, revealing how different aspects like pricing, popularity (reviews), and customer satisfaction (ratings) interact with each other.
