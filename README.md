# Sentiment-Analysis-of-Amazon-Reviews
In this project I have done sentiment analysis of Amazon Food Reviews.  
---
I have used two models for the sentiment analysis  

### (1) VADER - Valence Aware Dictionary sEntiment Reasoner  
This model use Bag of Words Approach. Means each word is scored and combined to a total score.  
This model removes stop words like The, And etc.  
But the problem with this model is it doesn't account for the relationship between words.  
  
  
### (2) ROBERTA Pretrained Model  
This model is pre-trained on large corpus of data.  
The transformed model account for the words but also the context related to other words.  

---
After this I have reviewed the odd example like 1 star rated positive review and 5 star rated negative review.  
  
  
Finally, I have coded The Transformed Pipeline for the quick and easy way to run the sentiment predictions.
