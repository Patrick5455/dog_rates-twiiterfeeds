## Quality Issues

#### Twitter Archives
  > 1. invalid names in names column such as `None and a` needs to be fixed
  > 2. Some columns (_retweets & ids_) contain null values and are not really needed
  > 3. Columns on dog stages (_doggy, pupper etc_) contain mostly NUll values
  > 4. source column values not in correct format
  > 5. expanded urls column not needed. The only useful information needed from it (tweet id) is already availabele
       in a separate column
  > 6. all retweets columns (_retweeted_status_id,retweeted_status_user_id,retweeted_status_timestamp_) not
      required
  > 7  Incorrect denominator rating values, values greater than 10 and some quite outrageous
  > 8  Incorrect numerator rating values; we have outrageous values such as 420, 1776
#### Image Predictions
  > 9. The string values in p1, p2, and p3 coluumns _breed predictions_ by the neural network are not in uniform format
  > 10   Unique counts of ids is less than that in archives - missing data
  > 11   columns such as tweet_id are not in thier corect datatype
#### Json Tweets
  > 12. The column id datatype in int instead of string
  > 13. language column values are not meaningful
  

## Tidiness
#### Twitter Archives
 > 1. dog stages in different columns in twitter_archve dta2etimage prediction datasets 
 #### Image Predictions
 > 2. image prediction datasets needs to be joined with twitter archive rather than in separate datasets
   genereally we have 3 separe column datasets rather than one master dataset
 #### Json Tweets
 > 3. multiple id columns in json_tweets data
 > 4. columns like (_truncated 	display_text_range 	entities 	extended_entities 	source 	in_reply_to_status_id_)
       not required in terms of analysis
 > 5. datasets needs to be joined with twitter archive data
## Analysis & Visualizations
  >1. Analyse proportion of correct predictions
  >2. Correlations 