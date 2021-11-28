# ToppingTheCharts

This project studies the factors affecting the popularity of Google Play mobile applications using clustering and classification techniques, to find out the differences between popular and non-popular apps. We defined the popularity of a mobile application using a score calculated with equal weightage of two factors, namely a mobile application’s rating and its number of installations.  

We employed two datasets consisting of web-scraped data of Google Playstore apps and their user reviews from Kaggle (https://www.kaggle.com/lava18/google-play-store-apps) to analyse the popularity of 816 android mobile applications in terms of (1) the quantitative statistics and objective figures and (2) the qualitative factors drawn from user reviews. 

To the datasets, we performed various Exploratory Data Analysis (EDA) procedures, including but not limited to data cleaning, feature engineering, and a 80-20 train-test split of the data. The codes for this section are located in the EDA file. 

A range of 13 classification models, including Decision Tree, Naive Bayes, AdaBoost, and more, were trained and applied to the quantitative figures, and the feature importances of each model are obtained using SHapley Additive exPlanations (SHAP). From the classification results, we grouped the models into three tiers based on their f1 scores to compare their performances, and identified the top 3 feature importances across the models. The RQ1 file contains the complete codes of all the classification models we implemented. 

On the other hand, Natural Language Processing (NLP) techniques such as Latent Dirichlet Allocation (LDA) and sentiment analysis, as well as unsupervised learning algorithms such as K-means clustering, are applied on positive, negative and neutral user reviews, and the resulting topics are manually analysed to determine the most differentiating factors that contribute to mobile application popularity. The RQ2 file contains the complete codes of all the NLP analysis we implemented.

In terms of quantitative factors, we found that category saturation, the number of user reviews, and the category of the mobile application are the top 3 most differentiating factors that most strongly predict mobile app popularity; whereas in qualitative factors, popular applications tend to receive more specific praises, while non-popular applications tend to receive more specific complaints.
