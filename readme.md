## Twitter Sentiment Analysis
This notebook is going to answer this question via analyzing tweets with implementing various machine learning algorithms

**“What can public opinion on Twitter tell us about the Canadian political landscape in 2019?"**


## Hw NLP analytics based on tweets is useful for political parties during election campaigns ?

 

*   NLP can help of analyze how each party has been influenced on people's
*   opinition by analyzing sentement of the tweet. It give us a good reflection of public views on each parties and it can be considered as the voice of general public
*   Each parties can benefit a social media team to make meaningful reactions to general people view and tweets, and change the result to thier benefits with creatign relevent content and hashtags that are capable of getting viral and directing public's doubts or offenses

## Data
In this project, two sets of data are used.

1. sentiment_analysis.csv contains tweets that have had their sentiments already analyzed and recorded as binary values 0 (negative) and 1 (positive).
2. Canadian_elections_2019.csv, contains a list of tweets regarding the 2019 Canadian elections.

## Analysis Steps
The analysis include following steps:
1. Data cleaning
   - Lematization
   - Removing stop words
   - Deemojize
2. Exploratory data analysis
3. Model preparation ( Logistic Regression, KNN Classifier , SVM , Decision Tree, Random Forest , XGBoost ) 
4. Model implementation
5. Tunning the best model

## Distribution of 2019 tweets 
![Distribution](https://github.com/mmaryam2020/Tweet-Sentiment-Analysis/blob/735510e7226a39e4c78678de8eecefafb85bc0e7/Images/Distribution%20of%202019%20tweets%20based%20on%20parties%20and%20thier%20sentiment.png)

## Insights from EDA
There are words that are totally representive of positive and negetive sentiments in both clouds.Especially as we don't delete emojies and substitude them with words, wee see that they also apear in the wordcloud like cry face, or smiling face, which is obviously relevent to negetive and positive emotions in consequense. 

![Word Clouds](https://github.com/mmaryam2020/Tweet-Sentiment-Analysis/blob/d5527d8c91a675b5305a9b0098c95bbc4b008bfd/Images/PosetiveWordCloud.png)

**Words Frequency**

![Words Frequency](https://github.com/mmaryam2020/Tweet-Sentiment-Analysis/blob/bb99ccca682bd1e36b2b444aa0ac42bf0185aaa0/Images/WordFrequency.png)

## Comparing different model results
![Word Clouds](https://github.com/mmaryam2020/Tweet-Sentiment-Analysis/blob/638fff858493cb5a88af1bba0a7f3d5ea9813253/Images/ModelsResults.JPG)
