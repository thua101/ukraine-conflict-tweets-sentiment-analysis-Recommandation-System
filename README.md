### Ukraine Conflict Twitter - Sentiment Analysis/Recommandation System/Cross Validation with Popular Classification Techniques (99% ACC)

Data: Tweets monitoring the current ongoing Ukraine-Russia conflict. 

Data source: [Ukraine Conflict Twitter Dataset (10.8M tweets)](https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows/code)

Keywords: 
- text mining
- sentiment analysis
- recommendation system
- cross validation
- classification
- svm, random forest, decision tree, naive bayes, gradient boost, xgboost

**What exactly did I do?**
1. Around 1 million tweets were posted between 17 Mar and 18 Mar about Ukraine Conflict, I converted them into Feather File Format for faster processing speed, and less ram usage.
2. I used certain text mining techniques, including tokenization, sentiment analysis, emoji cleaning and converting, keyword visualization (wordcloud maps), and ordinary exploartion (location, time distributions of those tweets).
3. I also built a recommendation system for recommending 10 most sentimentally alike tweets based on cosine similarity.
4. I applied most popular classifier methods (including SVM, random forest, decision tree, naive bayes, gradient boost and xgboost) to build predictive models that predict the sentiment of the tweets, and SVM model provides the best accuracy (99%).
