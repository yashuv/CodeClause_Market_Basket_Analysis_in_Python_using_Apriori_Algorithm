# CodeClause_Market_Basket_Analysis_in_Python_using_Apriori_Algorithm

This is the second project I completed as a part of my Data Science internship at **CodeClause**.

In this project, I accomplished the following:

## 1. Definition of Task (What is Market Basket Analysis?)
*Market basket analysis* is a technique for identifying relationships between items in large datasets of customer transactions. It is a valuable tool for data mining and machine learning, and is widely used in retail and e-commerce to identify which items are frequently purchased together in a transaction, with the goal of improving sales and customer loyalty.

## 2. Importing necessary libraries
Importing library in a Python script allows you to use the functions, classes, and other objects defined in those libraries in your code and makes it easier to accomplish tasks.

For example, you might import the numpy library to use its array manipulation and numerical computing functions, or you might import the pandas library to use its data manipulation and analysis tools.

## 3. EDA
It is a valuable tool for understanding and gaining insights from data. It can also be used to generate ideas for further research or to communicate findings to others.and is an important step in the data science process.

for eg: data summary and visualization

## 4. Apriori Algorithm
Market basket analysis is typically implemented using `association rule learning`, which is a technique for discovering interesting relationships between variables in a dataset. One of the most popular algorithms for association rule learning is the `Apriori algorithm`, which is used to identify frequent item sets and generate association rules. These rules are evaluated using measures such as support, confidence, and lift, which are used to determine the strength of the association between items.

For example, consider a dataset of customer purchases from a grocery store. An association rule might be "If a customer buys bread, they are likely to also buy butter."

The `Evaluation metric` used to evaluate the strength of the association between items are: 

* **Support**: It is a measure of the frequency of an itemset in the dataset. Mathematically, it is calculated as follows:

$$support(I) = \frac{number\ of\ transactions\ containing\ itemset\ I}{total\ number\ of\ transactions}$$


* **Confidence**: It tells us how often the items a and b occur given that a is bought. It is a measure of the reliability of an association rule. Mathematically, it is calculated as follows:

$$confidence(X \rightarrow Y) = \frac{support(X \cup Y)}{support(X)}$$

* **Lift**: It is a measure of the strength of an association rule. Mathematically, it is calculated as follows:

$$lift(X \rightarrow Y) = \frac{confidence(X \rightarrow Y)}{support(Y)}$$

where X and Y are the *antecedent* and *consequent* of the rule, respectively.

## 5. Make Recommendation on Items
To recommend products to a customer based on their previous purchases, you can use the association rules generated by the Apriori algorithm to identify the items that are frequently purchased together with a given item.

---
Thank you and Happy learning!