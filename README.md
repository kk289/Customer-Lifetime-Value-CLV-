# Customer-Lifetime-Value-CLV

## Recommending Items to Users

Collaborative Filtering is a popular technique that is used for coming up with User-Item recommendations. 

We will use the list of which users bought which items and build an affinity score between items. When a customers buys an item, we use this affinity score to recommend other items to the customer

The source data set ("rating.csv") contains in each row a User ID and an Item ID. This is the list of users and the items they bought, one line at a time.

## Group Customer Support Problems

We are going to group customer support problems into problem groups based on their attributes. Then we will analyze the groups to see similarities and differences.

## Discovering customer attrition patterns

We analyze customer attrition data to discover patterns. These will help us dive deeper into those patterns and do root cause analysis of why they are happening. We will use association rules mining algorithm for this purpose.

If apyori is not working on Jupyter Notebook, try this out
```
# Install a pip package in the current Jupyter kernel
import sys
!{sys.executable} -m pip install apyori
```

We now use the apriori algorithm to build association rules. We then extract the results and populate a data frame for future use.

The apriori provides the LHS for multiple combinations of the items. We capture the counts along with confidence and lift in this example.

