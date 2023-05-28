# Practice for 5511 RNN 
### Natural Language Processing with Disaster Tweets


*May 2023*


### **Problem Statement**

The main objective of this project is to develop a RNN model that can classify which Tweets are about real disasters and which ones are not. 



### **Data Source:**

https://www.kaggle.com/competitions/nlp-getting-started/data


The data set includes 7613 Tweets for training, each text has a label of 0 or 1 in 'train.csv', and also 3263 test Tweets to be labeled.




### **Methodology**

To classify test text with the right label, we will use rnn. After implementing this approach, we will upload the label of test Tweets to kaggle to see the accuracy.

By completing this project, we hope to enhance our knowledge of RNN and its applicability in real-world scenarios.


### **Detail steps** 


**1. Exploratory Data Analysis (EDA)** 

Firstly we will explore and visualize the data to understand the structure and distribution of the data.  

**2. Model Training & Evaluation**

Next, we will build rnn with training data set and check the performance on test dataset. 
We need sequential model to process sequence of text data. 
Architectures with LSTM and GRU will be tried.

**3. Conclusions**

Finally, we will summarize the results and see what can be improved in the future. 
