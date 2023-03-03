Scope of this project is to analize the open source data of airbnb listings in the city of Berlin, compiled on the 21st December of 2022.

CRISP-DM Process:

1. Business Understanding
- First question: What are the more expensive neighboorhoods in Berlin, accounting number of beds? Ratio?
    Since there are apparently neighboorhoods with rather bigger appartments and some with smaller appartments we look at the ratio of price and number of beds to account for that problem in at least some kind of way.
    neighbourhood_group_cleansed
    price
    beds

- How much are airbnb appartments earing in each neighboorhood over certain timeframes?
    We can predict how much nights are booked by reversing the availability for certain timeframes. Therefore we have to neglect that maybe the host blocked booking for certain timeframes for what ever reason, but thats something we can't filter...
    availability

- Where do people book airbnbs in Berlin? Which neighboorhoods are the most popular ones?
    neighbourhood_group_cleansed

- How much are people willing to spent for their airbnb? Which appartements get booked more often? The cheaper or the more expensive ones?
    price

- Get appartements rented more likely if they have a lot of reviews?
    number_of_reviews
    reviews_per_month


- How do you score a good rating? Are there "must have" features which determine a good review in terms of the appartment?
- How should you beahve as a host to score a good review?
- How well can we predict if a unit gets rented a lot?


2. Data Understanding

3. Prepare Data

4. Model Data

5. Results

6. Deploy


Rrerequisites:
- Unzip airbnb_berlin_data.csv.zip

Notes:
- Some of the data files provided by insideairbnb.com containing the raw data exceed the file size limit of 100mb of github. Therefore the files are processed and stored in seperate files to keep them small enough.

Resources:
- http://insideairbnb.com/get-the-data