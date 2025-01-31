# Contraceptive-Method-used-by-Women Using Decision Tree
Leveraging decision tree modeling to uncover the most influential factors that contribute to the choice of contraceptive methods among women
![image](https://github.com/user-attachments/assets/31721378-58c6-49e7-9de7-7263adca85d8)
# Introduction
Contraception plays a vital role in family planning and women's reproductive health. The choice of contraceptive method is a critical decision for women and plays a significant role in family planning, reproductive health, and overall well-being, influenced by various factors such as age, marital status, education, and cultural beliefs. Understanding the factors that contribute to a woman's choice of contraceptive method is essential for healthcare professionals, policymakers, and researchers to provide better family planning services and support. The primary objective of this study is to classify the contraceptive method used by women based on their demographic and socio-economic status. In essence, we aim to answer the pivotal question: What are the key determinants that influence a woman's choice of contraceptive method? By employing sophisticated analytical techniques, we intend to unearth insights that can assist healthcare providers and researchers in making informed decisions and optimizing pregnancy care strategies.
Contraception is a global concern, but its significance varies across different countries and cultures. In some parts of the world, access to contraception is limited, leading to unintended pregnancies and potentially adverse health outcomes. In others, the choice of contraceptive method is a matter of personal preference, influenced by various socio-demographic factors, cultural norms, and healthcare accessibility.
# World Health Organization
According to the World Health Organization (WHO), approximately 214 million women of reproductive age in developing countries who wish to avoid pregnancy are not using a modern contraceptive method. Additionally, each year, there are an estimated 74 million unintended pregnancies, many of which result from inadequate access to contraception or insufficient information about available methods.
# Understand the Data
The dataset for this was selected from the module’s recommended datasets list.  It is a subset of the 1987 National Indonesia Contraceptive Prevalence Survey. The samples are married women who were either not pregnant or do not know if they were at the time of the interview. Here are the Definitions of the columns of the data.
# Exploratory Analysis
Using the ‘str’ function, it was observed that the variables in the dataset consist of integers. The summary function was used to obtain the minimum and maximum, as well as measures of central tendency (mean, median) and spread (1st and 3rd quartiles) for each of these variables.
An attempt was made to create a new binary variable for the wife's age and number of children i.e., ‘WifeAge’ and ‘NumChildren’ based on the condition of the wife's age being greater than 25 and the number of children being greater than 4. The frequency table for this new variable to count the occurrences of "Yes" and "No" values is shown below.
# Variable Analysis
42.7% of women do not use a contraceptive method, 22.6% use a long-term contraceptive method, and 34.7% use a short-term contraceptive method.
![image](https://github.com/user-attachments/assets/e331f9e3-7432-459d-958e-30937a85ea17)
Older women do not seem to be using contraceptives. Also, women with more children tend to use long-term contraceptives.
![image](https://github.com/user-attachments/assets/f6d6f3f8-307c-4011-b7e4-a18f822cded6)
![image](https://github.com/user-attachments/assets/bfb90f17-0f90-4e69-83be-6f747e937409)
# Decision Tree Algorithm
One of the widely used techniques in data mining is systems that create classifiers. In data mining, classification algorithms can handle a vast volume of information. It can be used to make assumptions regarding categorical class names, to classify knowledge based on training sets and class labels, and to classify newly obtainable data. Classification algorithms in machine learning contain several algorithms, one of which is the decision tree algorithm.
![image](https://github.com/user-attachments/assets/1ceac64e-a1ca-4ce3-a2a9-e204fd371385)
# Model Fitting
The dataset was divided into training and test sets using R code, after which we performed the decision tree model and evaluated the confusion matrix with model methods such as sensitivity, specificity, positive prediction value, negative prediction value, and prevalence of the data.
![image](https://github.com/user-attachments/assets/6de21ed9-dce0-4ae9-8aef-8e2fcaae1b03)
# Conclusion
As we see, the accuracy of the decision tree is 43%, and the classification error is 57%. So, we can conjecture that using a decision tree wouldn’t build a good model as we expect, though reliable. It was deduced that the wife's age and education are the most important determinants of contraceptive methods used by women.
# Limitations of the Study
•	A limited number of variables in the data: This may result in a loss of valuable information that could have contributed to a more comprehensive understanding of the study.
•	The values of the attribute named Media Exposure are mostly “Good”, so we cannot estimate whether this attribute works or not. 
•	It is hard to explain the details of each attribute because there is no reference to this dissertation. Because of that, we may have some misunderstandings about attributes.
# Recommendation
•	There should be increased efforts to ensure adequate keeping of information or updating of the database of contraceptive methods used by women for future analysis.
•	Efforts should be made to increase awareness and proper documentation of other factors that may affect pregnancy.
# Thank You
