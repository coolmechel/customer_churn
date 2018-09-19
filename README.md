# customer_churn
SaaS consultant Lincoln Murphy opined that the average businesses sees 13% annual revenue churn, whilst the best businesses see negative churn. The Harvard school Review had also written that preventing customer churn by as little as 5% can improve profitability by as much as 95%. Customer loyalty is a top priority for any serious brands, marketing managers and businesses. It is much easier and less stressful to keep an existing customer than to gain a new one. It is also easier to prevent a customer from leaving than to convince them to comeback. Understanding how to keep the customer satisfied to make repeat purchase and bring in referrals and also preventing them from churning is a critical metric to any serious marketing team.
How do we know if a customer would leave? What are the necessary actions we need to take to prevent them from leaving? And the ones that had left, what can we learn from those behaviors moving forward? How about staying ahead of the competition by developing a model that can help you identify the customers with high tendency of churn and helping you become more proactive by keeping them satisfied.
In this article, we will be using a Telco customer churn dataset from Kaggle and see what we can learn by applying DataScience analysis and machine learning algorithms.
## ABOUT THE DATASET
Ever wondered why a customer after some times and despite all the incentives from marketing decides to stop using your product or services? Customer churn or customer attrition simply means that a customer has stopped using your products or services. And if you have a good history on the customer’s journey collected overtime, you will most certainly have strong signals pointing to the reason why they’ve made that decision.
Columns of the data
- CustomerID = Customer ID
- Gender Customer = gender (female, male)
- SeniorCitizen = Whether the customer is a senior citizen or not (1, 0)
- Partner = Whether the customer has a partner or not (Yes, No)
- Dependents = Whether the customer has dependents or not (Yes, No)
- Tenure = Number of months the customer has stayed with the company
- PhoneService = Whether the customer has a phone service or not (Yes, No)
- MultipleLines = Whether the customer has multiple lines or not (Yes, No, No phone service)
- InternetService = Customer’s internet service provider (DSL, Fiber optic, No)
- OnlineSecurity = Whether the customer has online security or not (Yes, No, No internet service)
- OnlineBackup = Whether the customer has online backup or not (Yes, No, No internet service)
- DeviceProtection = Whether the customer has device protection or not (Yes, No, No internet service)
- TechSupport = Whether the customer has tech support or not (Yes, No, No internet service)
- StreamingTV = Whether the customer has streaming TV or not (Yes, No, No internet service)
- StreamingMovies = Whether the customer has streaming movies or not (Yes, No, No internet service)
- Contract = The contract term of the customer (Month-to-month, One year, Two year)
- PaperlessBilling = Whether the customer has paperless billing or not (Yes, No)
- PaymentMethod = The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- MonthlyCharges = The amount charged to the customer monthly
- TotalCharges = The total amount charged to the customer
- Churn = Whether the customer churned or not (Yes or No)
## PREDICTING CUSTOMER CHURN
Depending on the business or services you run, building a standard metrics for a holistic view of your customer’s experience is important to learning how to prevent customer churn, and combining these with operational data such as card usage or purchasing power and repeat visits to identify the main drivers of churn and applying machine learning algorithms like deep learning, classifiers, neural networks and others to make predictions and better prepare you against churn before it becomes too late.
By applying Support Vector Classifier algorithms on the dataset to better understand the following:
- Drivers of customer churn
- These drivers of churn can be applied in identifying at risk customers
- Define a base threshold for taking actions based on the predictions in identifying churn
- All these can be integrated into a system and set on automation to create tickets and suggest actions for follow up.
## TACKLING CUSTOMER CHURN
Having a model that can help you in identifying if a customer will churn is an important process towards reducing churn tendency. So, what benefits can we get from the model? You can implement this model in real time by integrating it within your data pipeline and adding features that will enable it create alerts and tickets for customers in various states of dissatisfaction with your products or services.
You can be proactive by setting a target which requires all tickets for customers with 70% likelihood to churn to be resolved within 48 hours. You can also set churn threshold triggers for specific customers with low scores from experience surveys.
Conclusively, it is much easier and less stressful to keep an existing customer than to gain a new one. It is also easier to prevent a customer from leaving than to convince them to comeback. Why go through the stress when you can develop this model with your team of data scientist and build pipelines to set it on automation. Reducing customer churn impacts your company’s revenue positively and also reduces acquisition costs. Start leveraging the power in AI and ML for growing your businesses and services by helping you understand the drivers of churn behaviors and save some weeks of tedious analysis.

