# solution-engineer-technical-test

##Assignment Customer Services

Inside the Kensu_Data file, you will find a set of all our fictive customers, identified with:

-	Their Company
-	Their first_name
-	Their last_name
-	Their email
-	Their gender
-	Their Phone
-	Their City
-	Their Country
-	Their Payment_Method: the preferred payment method of the customer


###SAS 

####Task

Using the Kensu_Data file, prepare a SAS script where you answer to those questions:

-	How many customers are located in Belgium?
-	How many male customers are located in Italy?
-	How many different payment methods are used by or customers in China?
-	What’s the most popular payment method used by our customers in China?
-	What’s the percentage of missing email addresses (in % compared to the total amount of customers)?
- 	Which country has the highest rate of missing values for the company name?

###Python

####Task

At Kensu, adaptability is a key skill. We would like you to rewrite the previous script in a completely new environment: PySpark.

You will have to:
-	Create an environment using PySpark (Python 3 and Spark 2.2.0 minimum)
-	Create a Jupyter notebook
-	Use PySpark to answer the same questions as in the SAS script. 
	Hint: Use PySpark SQL 

###Delivery

We expect from you that you create a new branch in our public github repository, call it with your name, and create a folder with an export of your SAS code and a Jupyter notebook for PySpark.
