## Quality Issues

#### Twitter Archives
  > 1. invalid names such as `None and a` needs to be fixed
  > 2. Some columns (_rtweets & ids_) contain null values and are not really needed
  > 3. Columns on dog types such as contain mostly NUll values
  > 4. required values in source columns comes with other unecessary details
  > 5. expanded urls column not needed. The only useful information needed from it (tweet id) is already availabele
       in a separate column
  > 6. all retweets columns (_retweeted_status_id,retweeted_status_user_id,retweeted_status_timestamp_) not
      required
  > 7. convert columns to appropriate data types
#### Image Predictions
  > 8. The string values in p1, p2, and p3 coluumns _breed predictions_ by the neural network are not in uniform format
  > 9. Convert columns to appropraite data types
#### Json Tweets
  > 10. The column id_str should be dropped as it is not needed. We can easily convert the column id to string if needs
       be
  > 11. Inappropraite name for column `created_at`
  > 12. Inappropraite format value of source column just as in Twitter Archives
  > 13. uneeded columns: (_retweeted_status,quoted_status_id,quoted_status_id_str,quoted_status, 
                          possibly_sensitive,possibly_sensitive_appealabl_)
  > 14. Convert columns to appropriate data type
  
  

## Tidiness

#### Twitter Archives
 >1. Put the dog breed types in one column
  

#### Img prediction
  
  
#### Json Tweets


## Analysis & Visualizations
  >1. Analyse proportion of correct predictions
  >2. Correlations 