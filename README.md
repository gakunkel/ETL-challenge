# ETL-challenge
Extracting, Transforming, and Loading data into a database

  This project will entail extraction of cryptocurrency data and news headlines from two APIs. The cryptocurrency data, provided by Coingecko API, will include market volume and exchange rate in relation to several currencies around the world (dating back 30 days). Headlines containing Bitcoin, provided by NewsAPI, will be subjected to NLTK sentiment analysis to analyze trends in price and volume action in relation to media sentiment.
  
  Transform: Transformations required for this database will include filtering JSON data and joining tables. The request data itself is fairly clean.
  
  Load: This data will be loaded into SQL, a relational database. Multiple tables (at least one per cryptocurrency) will be created and primary keys and foreign keys will consist of the name of the coin or the date.
