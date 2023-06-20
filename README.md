# Amazon-review-Pyspark
The objective of this project is to analyze customer reviews and convert them into numerical representations for further analysis. 
The infrastructure used for this analysis is an AWS multinode system, which provides the necessary computational power to handle 
-large-scale data processing.

To prepare the data for analysis, we will drop any null values present in the dataset to ensure data integrity. 
Additionally, we will create meaningful columns that capture important aspects of the customer reviews, 
such as sentiment or key topics discussed.

For the modeling phase, we will explore two different approaches. 
The first approach involves using count vectorization, a technique that converts text data into numerical representations by 
-counting the occurrences of words or phrases. We will then apply logistic regression, a popular classification algorithm, 
to train a model based on the count vectorized data.

The second approach utilizes term frequency-inverse document frequency (TF-IDF) transformation, 
which gives more weight to rare words that are unique to specific documents. Again, 
logistic regression will be applied to the TF-IDF transformed data to build a classification model.

After evaluating the models, we will compare their performance in terms of both accuracy and speed. 
The results indicate that the TF-IDF and logistic regression approach outperforms the count vectorization method, 
achieving an impressive area under the curve (AUC) score of 92.7% and an accuracy of 89.8%.

In summary, through the implementation of TF-IDF and logistic regression on customer review data, 
we were able to effectively convert text into numerical representations and build a powerful predictive model. 
The high AUC score and accuracy demonstrate the efficacy of this approach, making it an optimal choice for this project.
