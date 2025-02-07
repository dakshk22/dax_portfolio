# dax_portfolio
Analytics portfolio

    
    
# [Project 1] : COVID 19 DATASET data analysis project

This is the first project i did during my final year in undergraduate.

We have taken a small dataset of Covid - 19 , just for your understaning purpose . You have to work on the original dataset which contains about 19000 rows .
The data used here is till 29 - April - 2020 and has records as on 29 - April - 2020 .
This data is available as a CSV file , downloaded from Kaggle.

the data is sorted in ascending order and the data is free from all the anomalies.

![Screenshot 2022-06-24 142336](https://user-images.githubusercontent.com/97302476/175500706-5ba86c78-d9b0-4893-b8e0-31bc6a4945b7.png)

![covid19](https://user-images.githubusercontent.com/97302476/212250773-3c004d38-4511-4f28-b137-1dfb74279233.png)





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
![Screenshot 2022-12-02 133722](https://user-images.githubusercontent.com/97302476/205245866-18143c2f-7c5d-43ca-8b1b-64c8a91ceeaf.png)



# [Project 4] : NY taxi fare prediction project

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


# [Project 5] : Amazon sales data analysis project

Project is the part of ineuron data analysis training.

problem statement

Sales management has gained importance to meet increasing competition and the needfor improved methods of distribution to reduce cost and to increase profits. Salesmanagement today is the most important function in a commercial and businessenterprise.Doing Amazon dataset and find for Sales-trend -> month wise , year wise , yearly_month wise.

Check the data from dataset.
![Screenshot 2022-11-22 134811](https://user-images.githubusercontent.com/97302476/203262136-c709a47e-563f-4946-b1f4-aa66f2fb8797.png)

![Screenshot 2022-11-22 134900](https://user-images.githubusercontent.com/97302476/203262143-24f5ad16-8ee7-4804-b1c7-edaf58dfd163.png)

month wise data
![Screenshot 2022-11-22 134928](https://user-images.githubusercontent.com/97302476/203262154-2c04801d-f863-4e37-af27-d14309d66402.png)

year wise data
![Screenshot 2022-11-22 134950](https://user-images.githubusercontent.com/97302476/203262156-337c2af8-3287-4e84-b366-d71bb84895d8.png)

power BI report of the data
![Screenshot 2022-11-24 121909](https://user-images.githubusercontent.com/97302476/203713531-dfcfcbf6-d9a8-488e-8b7a-359fde06e92c.png)

# [Project 6] : Adidas sales data power BI report 

![Screenshot 2023-01-23 120605](https://user-images.githubusercontent.com/97302476/213979554-e03b54e9-4689-4105-8177-288b8d3413b0.png)

# [Project 7] : Election commision of india (ECI) Electoral bond data report

Project is based on the data released by government of india before the general election 2024.

On 15th February, the Supreme Court of India scrapped the Electoral Bond Scheme introduced in 2018, which allowed anonymous political funding, and ordered the disclosure of donors, the amount they donated, and the recipients. The Election Commission published the electoral bonds data shared by SBI on its website. The data released showed the details of the purchase of electoral bonds by companies and individuals of denominations between Rs 1,000 to Rs 1 crore since April 12, 2019.

What is an Electoral Bond?

Electoral bonds are instruments/securities that are used to donate funds to political parties. Electoral Bonds may be purchased by a person who is a citizen of India or incorporated or established in India.
A person being an individual can buy Electoral Bonds, either singly or jointly with other individuals.
Only the Political Parties registered under Section 29A of the Representation of the People Act, 1951 (43 of 1951) and which secured not less than one percent of the votes polled in the last General Election to the House of the People or the Legislative Assembly of the State, shall be eligible to receive the Electoral Bonds.

In this Data Analysis Project, I have delved deep into the data and found some insights published in public by the State Bank of India right after that.

![Screenshot 2024-12-13 113905](https://github.com/user-attachments/assets/62577418-487d-4498-88d5-e05d78e8c076)

![Screenshot 2024-12-13 1127201](https://github.com/user-attachments/assets/c79f47f0-0e59-4ba0-831d-1bdefe71c4fd)



https://github.com/user-attachments/assets/147a66d7-38a8-4b1a-bebc-55330696d459

# [Project 7] : Spotify 2024 wrapped data report

Collected my own data from spotify to make the wrapped of 2024 with the help of microsoft power BI and let to know how spotify worked and give specific info about the most played tracks and artists.
The key points of the report is to show how spotify make there spotify wrapped of every user and what they know how and which type of songs are recommended to the particular user in the future.

![Screenshot 2025-01-02 115306](https://github.com/user-attachments/assets/9823cc96-11ed-43f9-963e-b4276afa4099)

![Screenshot 2025-01-06 131526](https://github.com/user-attachments/assets/2609c4cd-16d6-478a-8616-28942da8293b)

