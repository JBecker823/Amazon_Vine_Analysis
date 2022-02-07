# Amazon_Vine_Analysis

Overview of the Analysis

Various natural language processing skills were explored to prepare a customer review analysis for a client interested in digital video games. 

Topics Explored 

1.	Define big data and describe the challenges associated with it. 
2.	Define Hadoop and name the main elements of its ecosystem.
3.	Explain how MapReduce processes data. 
4.	Define Spark and explain how it processes data. 
5.	Describe how NLP collects and analyzes text data. 
6.	Explain how to use AWS Simple Storage and relational databases for basic cloud storage. 
7.	Complete an analysis of an Amazon customer review. 

Results:

How many Vine reviews and non-Vine reviews were there? 
There were 145,431 reviews. Only reviews with 20 or more votes were considered for the rest of the analysis leaving 3,342 reviews. Helpful votes were defined as being 50% or greater than the total votes narrowing the list to 1,685 reviews. 
How many Vine reviews were 5 stars? How many non-vine reviews were 5 stars? 
There were 631 5-star unpaid Vine reviews. When divided by zero, the code would result in a zero-division error. Resulting in zero 5-star reviews. 
What percentage of the Vine reviews were 5 stars? What percentage of non-Wine reviews were 5 stars? 
The percentage of unpaid, 5-star Vine reviews resulted in 37.4%, while the percentage of paid, 5-star Vine reviews would be 0%.

Summary: 

Due to the sample size constriction to a degree that was impossible to compare paid and unpaid Vine reviews, the analysis is biased towards Vine reviews. Another indicator is comparing 37% of unpaid, 5-star Vine reviews to 0% paid Vine reviews. This also made the unpaid Vine biased. 
The starting criteria of 20 likes or the 50% helpful criteria may have been too high, this made the data set too small. Adjustments to the criteria is a first step to reconsidering using the data set. 
