# BigData Crypto Project

## Data location in Google Storage (private)

**Tweets 16M Location:** 

`gs://bigdata-general/tweets.csv`

**Cleaned  Tweets without Null values  (* goes from 0 to 16):**
 `gs://bigdata-general/clean/clean_tweets_part_*.csv`

**(Read part 16 with read_csv(engine='python'... other props))**

**Historical Bitcoin Price up to March 2021 :**  

`gs://bigdata-general/bictoin_historical_price.csv`

## Resources

[Bitcoin Historical Data]( https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory): `kaggle datasets download -d sudalairajkumar/cryptocurrencypricehistory`

[16M Bitcoin Tweets](https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329): `kaggle datasets download -d alaix14/bitcoin-tweets-20160101-to-20190329`

