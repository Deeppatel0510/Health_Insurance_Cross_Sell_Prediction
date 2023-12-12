# Health_Insurance_Cross_Sell_Prediction

Project Type - Supervised(Classification)

Contribution - Team

Team Member 1 - Gautam Patil

Team Member 2 - Deep Patel

# Project Summary -

The project involves collecting customer data, such as gender, age, driving license status, vehicle information, and more. After preprocessing the data , performing the Exploratory Data Analysis and extracting relevant features, machine learning algorithms like logistic regression, decision tree, random forest, gradient boosting, and xgboost can be used to predict health insurance cross-selling. We can use GridSearchCv or RandomizedSearchCV for hyperparameter tuning; whereas HalvingRandomSearchCV method can be employed for hyperparameter tuning, striking a balance between computation time and model performance. The project's aim is to provide valuable insights to insurance companies, enabling them to target potential customers more effectively, allocate resources efficiently, and optimize their business strategies for the insurance market.

# Problem Statement

Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

# Conclusion

--> According to the EDA, just 46710 of our 381109 consumers are interested in purchasing a vehicle insurance policy, which means that the firm must put in a lot of effort to increase sales of their vehicle insurance.



--> The Middle Age Group (29-57) members are more likely to be interested in buying vehicle insurance, hence this middle age group is where the majority of the company's target customers come from.



--> Those who have not prior insurance have a very high vehicle damage count, while those who have prior insurance have a very low vehicle damage count. For this reason, the firm focuses more on individuals who have vehicle damage but no insurance.



--> The majority of vehicle damage occurs in the middle age bracket (29-57) and is followed by the younger age bracket (20-28), which increases the likelihood that customers in these age brackets will get vehicle insurance.



--> The majority of individuals who own new vehicles already have insurance, whereas the majority of people who own vehicles that are between one and two years old do not. For this reason, the firm focused on customers whose vehicles were at least that old.



--> Through EDA, we discovered that the firm can more focus on  Region B as it have less count of previously insured people, leading the corporation to put more agents in this area.



--> we found that customers between the ages of 20 and 28 have more prior insurance.Those who are older and those in the middle age range (ages 29 to 57) had lower insurance coverage, correspondingly.



--> For identifying if a buyer would be interested in vehicle insurance or not, we used machine learning algorithms. Therefore, we used models, such as gradient boosting, decision tree, kNN, random forest, and xgboost classifiers. Overall, the XGboost Classifier model achieved 93% accuracy, making it the best model for this issue.
