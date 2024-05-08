# AerofitCaseStudy

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range
including machines such as treadmills, exercise bikes, gym equipment, and fitness
accessories to cater to the needs of all categories of people.

## Business Problem

The market research team at AeroFit wants to identify the characteristics of the target
audience for each type of treadmill offered by the company, to provide a better
recommendation of the treadmills to the new customers. The team decides to investigate
whether there are differences across the product with respect to customer characteristics.

1. Perform descriptive analytics to create a customer profile for each AeroFit treadmill
   product by developing appropriate tables and charts.
2. For each AeroFit treadmill product, construct two-way contingency tables and compute
   all conditional and marginal probabilities along with their insights/impact on the
   business.

## Dataset

The company collected the data on individuals who purchased a treadmill from the AeroFit
stores during the prior three months. The dataset has the following features:

**Dataset link:** [AerofitCaseStudyData](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/125/original/aerofit_treadmill.csv?1639992749)

## Product Portfolio:

The KP281 is an entry-level treadmill that sells for $1,500.
The KP481 is for mid-level runners that sell for $1,750.

The KP781 treadmill is having advanced features that sell for $2,500.

## What good looks like?

1. Import the dataset and do usual data analysis steps like checking the structure &
   characteristics of the dataset
2. Detect Outliers (using boxplot, “describe” method by checking the difference between
   mean and median)
3. Check if features like marital status, age have any effect on the product purchased (using
   countplot, histplots, boxplots etc)
4. Representing the marginal probability like - what percent of customers have purchased
   KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
5. Check correlation among different factors using heat maps or pair plots.
6. With all the above steps you can answer questions like: What is the probability of a
   male customer buying a KP781 treadmill?
7. Customer Profiling - Categorization of users.
8. Probability- marginal, conditional probability.
9. Some recommendations and actionable insights, based on the inferences.
   Later on, we will see more ways to do “customer segmentation”, but this case study in itself
   is relevant in some real-world scenarios.
