# Health-Insurance-Cross-Sell-Prediction

Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

Objectives : 
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

### Business Question
Question 1: Find which features has high contribution
Vehicle_Damage, Previosly_Insurance, Age, and Vehicle Age

Question 2: Find the best model to predict the Response of Vehicle Insurance
The best analytical model to predict the response of Vehicle Insurance is Random Forest with F1 Score 0,80.
Hyperparameter tuning in random forest increase the F1 Score to 0,82.

Question 3: Find the factors that make customers buy vehicle insurance
Customers who have uninsured and damaged vehicles are more interested in buying insurance
When the vehicle is 1-2 years, the customer will insure it. Meanwhile, vehicles that are > 2 years definitely insured.
The older the customer, the less interested they are in insuring their vehicle.
![image](https://user-images.githubusercontent.com/109024702/199867053-2a24a280-5d24-4645-93d5-645d9f88f260.png)
