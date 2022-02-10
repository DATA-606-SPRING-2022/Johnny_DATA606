# Johnny_DATA606
UMBC Data606 Data Science Masters Captone


# Johnny_Data606 draft proposal

## What is your issue of interest (provide sufficient background information)?
Stock price is entirely governed by 2 factors: What the owner wants to sell it for, and what the buyer is willing to pay for it.  Many factors influence their decisions.  Price prediction based on sentiment analysis of social media, google search terms, and new articles over time.  
## Why is this issue important to you and/or to others?
Stock market price prediction can be lucrative if it can be done effectively and reliably.  $90B of stock is traded on a daily basis in the U.S.  Establishing machine learning methods to trade stock, establish stop loss predictions, and getting in on market movements can be important skills a data scientist can support.   
## What questions do you have in mind and would like to answer?
I’m very interested in the semantics of stock advise expressed by authors and people in their social media posts.  What is the intent of any particular post?  Sentiment is easier to quantify, but what is the sentiment about?  What was the intent of the post?  Was it informational, directive, or influencing?  What is the spectrum of intent expressed in these corpuses? How successful would predictions be if intent, and semantic modeling were included along with sentiment?

## How do sellers and buyers make decisions to buy or sell, and how can their behaviors and external influencers be examined, inferred, forecasted, and modeled?  
Investor behavior can be witnessed as communication occurs.  Capture of social media posts for topic modeling and sentiment can provide indicators of public sentiment and explain market pressures at play in price setting in the market.  Modeling the relationship of media publications semantics, intent, and sentiment to stock prices as “influencers” can be analyzed to determine the level of influence on investor decision making.  As a predictive data source these can be evaluated using convolutional methods, reducing or removing data elements to improve the effectiveness of price predictions. Many of the price prediction github projects look to be overfit.  If there are influencers at play that are guiding investor behaviors, machine learning could be leveraged to gather and filter the available data sources to produce reliable stock price predictions.  

## Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?
Stock price data is available from many sources.  Yahoo Finance provides an api where historical stock data is available.  Social media platforms provide access to social media posts.  Twitter and Reddit are lucrative in the scale and scope of available data sets. Google provides a wealth of search opportunities to find news sources.  Top level domains can be explored to discover the availability of news article sources.  

## What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?
The unit of analysis will be stock price predictions of several high-volume stocks.  Some preliminary stocks will be stocks that have risen in value over the course of the last 10 years.  AAPL, TSLA, AMZN, ALPHABET, etc.  

## What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?
Semantic weights, topic modeling, sentiment analysis.  Intent modeling of stock influencers to determine the polarity and magnitude of influence being expressed.  Is the influencer bullish or bearish?  In sentiment analysis there is a concept of polarity.  Positive or negative.  Magnitude, subjectivity, and sarcasm can be modeled.  How can semantic intent of bullish and bearish influence be modeled on publications to create a bull/bear polarity and magnitude score?
## What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
Semantic modeling using word vector distance calculations among influence terms.  Clustering of topics and articles, cosine distance calculations of document similarity and sentiment scores can be established to establish consensus or disorder in publications to infer strength or weakness of influence being exerted.  This can be evaluated in contrast to consumer confident indexes. Various predictive models associated with time series data sets will be used to determine which models are successful.  

## How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
Model performance will be evaluated using independent models compared using their price predictions against actual prices.  Having several predictive models run against the same corpus sources can evaluate the predictive power of the model as well as the predictive nature of the source corpus.  Electing winners or combining, filtering, or aggregating predictive models could be used to leverage strengths and mitigate weaknesses in predictive models to produce higher performance4. 
## What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc)?
It is perhaps naive to assume that models created in this project will net a stable and reliable stock prediction methodology that does not require actual domain knowledge of the forces that drive stock prices.  However the methodology of evaluating investor behaviors and influencers is useful in many domains.  
