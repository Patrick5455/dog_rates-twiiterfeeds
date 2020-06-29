## Quality Issues

#### Twitter Archives
  > 1. invalid names such as `None and a` needs to be fixed
  > 2. Some columns (_retweets & ids_) contain null values and are not really needed
  > 3. Columns on dog types such as contain mostly NUll values
  > 4. required values in source columns comes with other unecessary details
  > 5. expanded urls column not needed. The only useful information needed from it (tweet id) is already availabele
       in a separate column
  > 6. all retweets columns (_retweeted_status_id,retweeted_status_user_id,retweeted_status_timestamp_) not
      required
#### Image Predictions
  > 7. The string values in p1, p2, and p3 coluumns _breed predictions_ by the neural network are not in uniform format
#### Json Tweets
  > 8. The column id_str should be dropped as it is not needed. We can easily convert the column id to string if needs
       be
  > 9. other columns aside the main columns as described in the project details viz: _id, tweet_count, vote_count_
        are not needed
#### General
  > 10. some columns in datasets not in appropriate format
  
  

## Tidiness
 > 1. dog breed types in different columns
 > 2. 3 separate column datasets rather than one master dataset

## Analysis & Visualizations
  >1. Analyse proportion of correct predictions
  >2. Correlations 