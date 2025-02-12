# Aerofit_Business_Case_Study
Aerofit Business Case Study - Exploratory Data Analayis to derive insights, trends and patterns.

## Objective
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.
## Important Links
- [Dataset](https://github.com/shyammanikandan/Aerofit_Business_Case_Study/blob/main/aerofit_treadmill.csv)
- [Jupyter Notebooks](https://github.com/shyammanikandan/Aerofit_Business_Case_Study/blob/main/Aerofit%20Case%20Study.ipynb)
- [Project Report](https://github.com/shyammanikandan/Aerofit_Business_Case_Study/blob/main/Final%20Report.pdf)
## About Data
The company collected the data on individuals who purchased a treadmill from the AeroFit stores during three months.The data is available in a single csv file

**Product Portfolio**

- The KP281 is an entry-level treadmill that sells for USD 1,500.

- The KP481 is for mid-level runners that sell for USD 1,750.

- The KP781 treadmill is having advanced features that sell for USD 2,500.

### Dataset features
| Feature                      | Description |
| -----------                  | ----------- |
| Product	| Product Purchased: KP281, KP481, or KP781|
|Age|	 	Age of buyer in years |
|Gender|	 	Gender of buyer|
|Education	|Education of buyer in years|
|Marital Status	| 	MaritalStatus of buyer|
|Usage	| The average number of times the buyer plans to use the treadmill each week|
|Income	| Annual income of the buyer (in $)|
|Fitness	| Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape|
|Miles	|The average number of miles the buyer expects to walk/run each week|

## Concepts

- Feature Engineering
  - Created new feature fitness category based on self fitness rating
- Data Visualization using Matplotlib and Seaborn
- Correlation
- Descriptive Statistics
- Probability
- Customer Profiling based on various factors

## Customer Profiling

**KP281 - Entry Level Treadmill - $1500 : 80 Customers**
- Suitable for Low Income Category Individuals.
- Both Male and Female equally prefer this type.
- Low and Medium Fit customers also prefer this type of treadmill. 

**KP481 - Middle Level Treadmill - $1750 : 60 Customers**
- Suitable for Low and Medium Income Category Individuals.
- Male customers are more in this type of treadmill than female customers.
- Low and Medium Fit customers also prefer this type of treadmill.
  
**KP781 - High Level Treadmill - $2500 : 40 Customers**
- Suitable for High Income Category Individuals.
- Male customers prefer this type of treadmill.
- High Fit customers prefer this type of treadmill.

## Recommendations

- KP 281 is the favourite product for customers closely followed by KP481.
- As the income of the customers increase, the price of treadmills also increasewhich means, high earning customers prefer the treadmill with advanced features.
- Fitness rating of female customers is very low when compared to the male customers. 
- Customers who cover more miles tend to prefer the advanced treadmill KP781.
- Huge difference between male and female in buying the higher end treadmill with 90% of KP781 customers being male.

