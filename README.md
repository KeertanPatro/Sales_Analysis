# Sales_Analysis

We have a Sales transactions data of a retail store this dataset consists of 125000 entries and three columns customer_id, transaction date, transaction amount.
In addition to this dataset we also have another dataset which tells us about customer's response to those purchase. Our objective for this project is to identify customer behavioriol insights, customer segementation, sales patterns and time seriers analysis of the sales. I firt cleaned the data checked for missing values and duplicates values and made treatmeent accordingly. I tranformed the data mainly the date variable to data time format and extracted various components such as month, year from it. After cleaning the data i found the insights from it.  

### Insights  
1) The first Insight is about the customers, there are **6889** unique customers.They have made multiple transactions over the years.


![img1](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/cd73e194-602f-432c-b986-4bd335f4f45c)    
from the above Plot we see the customer with highest number of transactions and customer with highest number of sales.  

2) Now let us look into transaction amount
![img2](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/2082fbb7-7547-40ea-b6e2-2f8e19b71793)

The tranasaction amount distribution is a steady distribution.  

3) Now let us look into transaction distribution for different years.

![img3](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/b30d4276-98cd-4e4a-8336-93fc3cffcae6)   

We see that there are lot of transaction made in year year 2012, 2013,2014, but the transactions are less in year 2015 and 2011.  

4) Now let us look into top customers transaction patterns


![img4](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/cf60f0ce-07cd-4f09-9507-c673748d4d3b)  

In this plot we see the transaction amount for top customers we see that customer with customer_id CS4424	has highest transaction amount, followed by CS4320.  

5) Now let us look into relation between total transaction to total sales
![img5](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/1a9cd8ac-e20e-4efc-9606-e5354b2024f4)

From the above plot we see that that relation between total transaction and total count have a linear relationship.  

### Customer Segmentation 

We need to segment our customers based on their transactions for that we will use KMeans Clustering. To find optimal clusters we will use silhoutte score.
After doing the Kmeans clustering we found the optimal number of clusters found are 4.  

![img6](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/361abaf0-97b6-4f22-adb3-f9b9b5110ba7)  
The above plot shows the distribution of points with segement labelling after cluster formation.  

### Churn Analysis  

We have response dataset which tells about the response of the customer about the store. let us look into customer response , 0 means that customer has not responded while 1 means that the customer has responded.  

![img7](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/50637cce-8d6c-4a7f-a29f-ae2a7aae1b35)    


### Time Series Analysis  
Now let us look into sales patterns with respect to time.  

![img8](https://github.com/KeertanPatro/Sales_Analysis/assets/122021282/a316a898-ece9-4847-828b-4d4069d81714)  

The sales have been steady but there has been sudden decline in sales.  


















