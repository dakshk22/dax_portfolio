# dax_portfolio
Analytics portfolio


# [Project 1] : COVID 19 DATASET data analysis project

This is the first project i did during my final year in undergraduate.

We have taken a small dataset of Covid - 19 , just for your understaning purpose . You have to work on the original dataset which contains about 19000 rows .
The data used here is till 29 - April - 2020 and has records as on 29 - April - 2020 .
This data is available as a CSV file , downloaded from Kaggle.

the data is sorted in ascending order and the data is free from all the anomalies.

![Screenshot 2022-06-24 142336](https://user-images.githubusercontent.com/97302476/175500706-5ba86c78-d9b0-4893-b8e0-31bc6a4945b7.png)






# [Project 2] : US Road Accident (2016-2021) DATASET data analysis project which is having 4.2 million of data the data is taken from kaggle website.

The project is based on the dataset of number of accident in united states of america in between 2016-2021 in different states of the country and also prediction about the number of accident that can took placed if the precautions are not taken.
the data cleaning and visualisation is done with python libraries.
like pandas ,numpy, matplotlib, seaborn, tensorflow.

![__results___23_0](https://user-images.githubusercontent.com/97302476/175494772-f841790b-0081-4d17-aecc-4798be80f3be.png)





# [Project 3] : Disney + DATASET data analysis project 2019 - 2021

The project is on the data gathered from the disney+ through kaggle to get the insides of how many series as well as movies was released in the platform between 2019-2021 in the platform.

You can see that Disney focuses more on Movies than TV Shows. Maybe because Disney has an audience that prefers movies over TV Shows.
![1 0SBvP2GzQnGRc0ByX-XCeA](https://user-images.githubusercontent.com/97302476/175484330-a71d7086-5639-4505-81df-6ffa96c07736.png)

In the Year 2019, Disney+ has added more than 600 movies to their platform. But after that, the graph of movie addition is declined may be due to covid-19 problem. I don’t see a much larger difference in the addition of TV shows to their platform over the years. Maybe because Disney focuses more on Movies than TV Shows.
![1 dMpmX_qzXT80ixMvmjuD6w](https://user-images.githubusercontent.com/97302476/175484365-54938bdb-3f33-425b-8e69-6817dbb8e203.png)

Disney+ dashboard created in powerBI
![Screenshot 2022-07-28 134059](https://user-images.githubusercontent.com/97302476/182329837-527fe159-3dc0-4703-93ad-236acc33141b.png)


# [Project 4] : newyork taxi fare prediction project

The project is done under the machine learning certification course from analyticsvidya. 

Problem statememt:
The maine reason of the project is to improve the taxi dispactchng systems for such services, it is importent to be predict how long a drive will Dave this taxi occupied.
if a dispatcher know approximately when a taxi driver would be ending their current role. they would be better able to idatify, which driver to assign to each pickup request.

We an Challenged to build a model that predict the total ride duratin of taxi trip in NY city.


(PART OF RESULT)
Feature transformation does change the distribution of the variable. When we have skewed distribution we use transformation to remove the skewness of the variable and hence changing the distribution. Functions like Log, square / cube, Square root / cube root, reciprocals can be used for feature transformation to reduce skewness of the variable.
Log transformation, square root and other nth roots are used for removing right skewness from the data. On the other hand, left skewed data distribution can be transformed using nth power or exponents functions
If we are taking the log of the variable that is negative or zero, it might show an error, as log of zero is undefined. Instead take log(x+c) where c is a constant with the objective that the log of the input must be greater than zero.

![Screenshot 2022-11-16 132339](https://user-images.githubusercontent.com/97302476/202120495-0fe0f4d3-34f1-45f9-be01-47323873d57a.png)

![Screenshot 2022-11-16 132317](https://user-images.githubusercontent.com/97302476/202120630-b0b13516-97fd-4706-b1f5-89ae39b687a5.png)


Conclusions

    1.The majority of rides follow a rather smooth distribution that looks almost log-normal with a peak just around exp(6.5) i.e. about 17 minutes.
    2.There are several suspiciously short rides with less than 10 seconds duration.
    3.As discussed earlier, there are a few huge outliers near 12.
    4.Most of the trips involve only 1 passenger. There are trips with 7-9 passengers but they are very low in number.
    5.Vendor 2 has more number of trips as compared to vendor 1
    6.Number of pickups for weekends is much lower than week days with a peak on Thursday (4). Note that here weekday is a decimal number, where 0 is Sunday and 6 is Saturday.
    7.Number of pickups as expected is highest in late evenings. However, it is much lower during the morning peak hours.
    8.We see that most trips are concentrated between these lat long only with a few significant clusters. These clusters are represented by the numerous peaks in the lattitude and longitude histograms
    9.Trip durations are definitely shorter for late night and early morning hours that can be attributed to low traffic density
    10.It follows a similar pattern when compared to number of pickups indicating a correlation between number of pickups and trip duration
    11.Median trip duration does not vary much as can be seen from the above plot for different vendors.
    12.The boxplot clearly shows that there not much of a difference in distribution for the most frequently occuring passenger count values - 1, 2, 3.
    13.Another key observation is that the number of outliers are reduced for higher passenger counts but that only comes down to the individual frequencies of each passenger count.
    14.From the correlation heatmap we see that the lattitude and longitude features have higher correlation with the target as compared to the other features.


