# ToppingTheCharts

This project studies the factors affecting the popularity of Google Play mobile applications using clustering and classification techniques, to find out the differences between popular and non-popular apps. 

Using the following web-scraped data of Google Playstore apps from Kaggle (https://www.kaggle.com/lava18/google-play-store-apps), we analysed the popularity of 816 android mobile applications in terms of (1) the quantitative statistics and objective figures and (2) the qualitative factors drawn from user reviews. 

In this study, the popularity of a mobile application is defined using a score calculated with equal weightage of a mobile application’s rating and its number of installations. A range of 13 classification models, including Decision Tree, Naive Bayes, AdaBoost, and more, are applied to the quantitative figures, and the feature importances of each model is obtained using SHapley Additive exPlanations (SHAP). 

On the other hand, Natural Language Processing (NLP) techniques such as Latent Dirichlet Allocation (LDA) and sentiment analysis, as well as unsupervised learning algorithms such as K-means clustering, are applied on positive, negative and neutral user reviews, and the resulting topics are manually analysed to determine the most differentiating factors that contribute to mobile application popularity. 

In terms of quantitative factors, it was found that category saturation, the number of user reviews, and the category of the mobile application are the top 3 most differentiating factors; whereas in qualitative factors, popular applications tend to receive more specific praises, while non-popular applications tend to receive more specific complaints.
