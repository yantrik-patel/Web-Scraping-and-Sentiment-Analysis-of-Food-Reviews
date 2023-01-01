# Web Scraping and Sentiment Analysis of Food Reviews
In this project I have done Web Scraping using  
  
## BeautifulSoup  
  
and carried out sentiment analysis using NLP models like  
  
VADER  
ROBERTA  
BERT  
---
I have done this project in two stage.(Both files are uploaded on this repository.)  

### (1) Yelp_8MilePi_Pizza_Review_BERT  
Here I have done webscraping to collect the reviews posted on website for this pizza restaurant and passed these reviews through the BERT model for the sentiment analysis. BERT is the state of the art model pretrained on the big data by Google.  
  
### (2) Amazon_fine_food_review  
I wanted to do sentiment analysis using other models like VADER and ROBERTA and also wanted to use bigger dataset. I have taken the dataset from Kaggle having 5 million records in it. Considering my local machine's computing power I have passed 5000 reviews first through both the models. Following are the few words about the models 

### (a) VADER - Valence Aware Dictionary sEntiment Reasoner  
This model use Bag of Words Approach. Means each word is scored and combined to a total score.  
This model removes stop words like The, And etc.  
But the problem with this model is it doesn't account for the relationship between words.  
  
  
### (b) ROBERTA Pretrained Model  
This model is pre-trained on large corpus of data.  
The transformed model account for the words but also the context related to other words.  
  
  
In the end I have reviewed the odd example like 1 star rated positive reviews and 5 star rated negative reviews.  
  
  
Finally, I have coded The Transformer Pipeline for the quick and easy way to run the sentiment predictions.
