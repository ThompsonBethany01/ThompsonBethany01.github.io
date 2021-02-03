---
layout: post
title: 'Telco Churn'
---

For this project, I discovered insights into customer habits that drive churn. Then, I created classification machine learning algorithms to predict if a customer would leave the company. I presented these findings with an emphasis on data storytelling.  


To acquire the data, I connected to the Codeup SQL database using python and a query to join the tables together.  
{% include image.html url="https://github.com/ThompsonBethany01/Telco_Churn" image="projects/proj-5/data.jpg" %}  


The data contained information on previous and current customers' service type, monthly payments, and more. A breakdown of each service by internet, phone, and both is shown below. Not all options were available for each service, as most options were available for internet customers only.  
{% include image.html url="https://github.com/ThompsonBethany01/Telco_Churn" image="projects/proj-5/services.jpg" %}  


The baseline model was the most common churn outcome - the customer does not churn. The final model selected was a Random Forest model, which was four percent more accurate than the baseline. A simplified visual of this model is shown below.  
{% include image.html url="https://github.com/ThompsonBethany01/Telco_Churn" image="projects/proj-5/model.jpg" %}  
