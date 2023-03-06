### Table of contents

1. [Additional requirements](#requirments)
2. [Project Motivation](#motivation)
3. [Projectfiles Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Additional requirements <a name="installation"></a>

There are no specific requirements or installations necessary to compile and run the projectfiles. If you run the code with the standard Anaconda distribution and Python 3 there should be no errors.

### Project Motivation <a name="motivation"></a>
For me, living in Berlin and interested in data, I was curios about some airbnb stats about my city. For my brief analysis I tackled the dataset, available [here](http://insideairbnb.com/get-the-data/)(downloaded 01.03.2023), asking following questions:

1. Which neighborhoods are the most popular for tourists visiting Berlin?
2. Which neighborhoods are there most expensive to book an apartment and which are the more affordable ones?
3. Which neighborhood generates the most revenue over one year? (Calculated with the current booking data)

### Project(-file) Descriptions <a name="files"></a>

### Results<a name="results"></a>
All findings and conclusions are listed and discussed in this [Medium article](). The code and all files necessary are available on my [Github](https://github.com/Daniel-Hutcheson/airbnb_berlin).

### Licensing, Authors, Acknowledgements<a name="licensing"></a>
There is no licensing for the code in this repository, anyone can use it however they want. Following entities/authors I want to give credit for supplying the necessary data, a rough blueprint for this project and somehow inspiration:
- Inside Airbnb for supplying datasets on airbnb listings for several cities -> [Link](http://insideairbnb.com/)
- Josh Bernhard and his project analyzing a stackoverflow dataset -> [Github-Link](https://github.com/jjrunner/stackoverflow/blob/master/README.md?plain=1) & [Medium-Link](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711)




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
