# DATA_ANALYST_Wrangle_and_Analyze_data

### by Jérôme d'Harveng

## Dataset
>Using different Python libraries, data was gathered from WeRateDogs. First, through tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comments about the dogs. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent."

>Missing data as for example retweet_count and favourite count, were extracted based on the tweet_id coming from the tweet archive, through the Twitter API. And finally, we could use predictions concerning the dogbreed, based on one of the available pictures.

## Summary of findings
> After Gathering, Assessing and Cleaning the data some analysis was done on the cleaned master data_frame with tweet info from WeRateDogs:
>- For the studied population, the main source is from far the iPhone
>- Some univariate exploration was done on retweet_count and after on the length of the text (from the tweets)
>- The distribution of the retweet_count seems right skewed, and was then also best represented with a logarithmic scale. Allowing to observe a Normal kind of distribution
>- The distribution of the length of the text messages seems left skewed. And 75% of the tweets are longer than 105 characters.
>- Some Bivariate exploration was made too, first tweet_length vs retweet_count and the favorite_count. After applying a linear regression model, and analysing the correlation coefficients, statistically speaking no linear relation was found between tweet_length and retweet_count. But for the other pair, a pretty strong linear relation was found.
