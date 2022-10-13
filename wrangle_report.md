# Data Wrangling Report
### Data Quality isssues
#### Visual Assessment
- df_api table - missing *in_reply_to_status_id* values
- df_archive table - does not seem to contain data for dog stage
- df_archive table - missing *retweeted_status_id* values 
- df_img_pred table - *p1* values start with varying cases(upper and lower)
- df_img_pred table - *p2* values start with varying cases(upper and lower)
#### Programmatic Assessment
- df_archive table - *timestamp* is a string instead of a datatime object
- df_api table - *possibly_sensitive_appealable* does not contain any data 
 



### Data Tidiness Issues
#### Visual Assessment 
- df_api and df_archive both have ratings and tweet url in the full text column 
- df_api table - we have the same data in two columns *id* and *id_str*