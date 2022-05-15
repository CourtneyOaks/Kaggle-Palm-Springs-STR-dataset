## Kaggle's Palm Springs Vacation Rental Analysis

This data set is a list of over 2,000 vacation rental properties in Palm Springs, CA provided by Datafiniti's Property Database.

I started by cleaning the data, removed duplicates, unwanted spaces and started to explore what information I could gain from this data set. 
I have provided a series of questions I constructed as well as the SQL code used to confirm the answer.  

**How many rows are there in this data? Result: 11374**
![Kaggle_PS_1](https://user-images.githubusercontent.com/102244119/168496300-eac01ae2-1986-4f7d-b1a8-6bcf37055b9c.png)


**What is the number of unique rental names? Result: 1848**\
![Kaggle_PS_2](https://user-images.githubusercontent.com/102244119/168496320-f61ae180-a563-4cf5-911e-7e63264b260c.png)


**What is the loweest number of bedrooms? Result: 0 bedrooms**
![Kaggle_PS_3](https://user-images.githubusercontent.com/102244119/168496333-bafc9f90-29d3-4d8c-bc19-217d67b61628.png)


**What is the highest number of bedrooms? Result: 13 bedrooms**
![Kaggle_PS_4](https://user-images.githubusercontent.com/102244119/168496346-f3300e15-9efb-4d12-84c5-317c82bac866.png)


**What is the number of bedrooms per home? Results listed below:**
* 43 with 0 bedrooms
* 542 with 1 bedroom
* 398 with 2 bedrooms
* 580 with 3 bedrooms
* 231 with 4 bedrooms
* 79 with 5 bedrooms
* 17 with 6 bedrooms
* 7 with 7 bedrooms
* 5 with 8 bedrooms
* 4 with 10 bedrooms
* 1 with 13 bedrooms

![Kaggle_PS_5](https://user-images.githubusercontent.com/102244119/168496359-4855dfaa-1790-4d8e-8092-3eb801591f57.png)


**What is the average number of bedrooms for all 1848 rental homes? Result: 2.70 bedroom average**
![Kaggle_PS_6](https://user-images.githubusercontent.com/102244119/168496381-02b25e5a-4834-4a5a-8273-e6fee52fd8cd.png)


**What is the number of two bedroom homes? Result: 398**
![Kaggle_PS_7](https://user-images.githubusercontent.com/102244119/168496402-b4b9ec5a-8510-404c-88e4-e0ee92903fe6.png)


**What is the number of three bedroom homes? Result: 530**
![Kaggle_PS_8](https://user-images.githubusercontent.com/102244119/168496406-abce08e3-b309-48b5-886b-25c5d70ac70f.png)


**What type of pricing periods does this table reflect (removing nulls)? Result listed below:**
* Weekly
* Monthly
* Weekend night
* Weeknight
* Weekend night,Weeknight
* Nightly

![Kaggle_PS_9](https://user-images.githubusercontent.com/102244119/168496411-b2e61ab2-4ed4-420b-99ac-02da12200891.png)


**Of the homes with prices, how many bedrooms do they have? Results listed below:**
* 31 with 0 bedrooms
* 340 with 1 bedroom
* 237 with 2 bedrooms
* 330 with 3 bedrooms
* 132 with 4 bedrooms
* 48 with 5 bedrooms
* 7 with 6 bedrooms
* 5 with 7 bedrooms
* 2 with 8 bedrooms
* 1 with 10 bedrooms

![Kaggle_PS_10](https://user-images.githubusercontent.com/102244119/168496417-858ce945-dd40-466a-af4b-9966037fca64.png)


**Sort by most highest monthly price per property, removing NULLS and working with STRING column). Result: USD 99820 high price / US 44 low price**

![Kaggle_PS_11](https://user-images.githubusercontent.com/102244119/168496451-93f84b13-a302-4ac2-8599-72b77050c7aa.png)


**What is the highest monthly rate for a 2 bedroom property? Result: USD 17370 for 'Recently Renovated 2bd Palm Springs Condo'**
![Kaggle_PS_12](https://user-images.githubusercontent.com/102244119/168496467-6fbfa1d2-c2f1-4e5c-8cc4-e4a3f26682fb.png)


**What is the lowest nightly rate property (removing nulls). Result: USD 49 for 'Affordable and Modern Room'**
![Kaggle_PS_13](https://user-images.githubusercontent.com/102244119/168496477-e38e56ad-789b-4afb-97e5-babee4a28d20.png)


**What is the median price on nightly priced rental homes? Result: USD 171**
![Kaggle_PS_14](https://user-images.githubusercontent.com/102244119/168496493-b058d8df-9f4b-4b80-b1bc-f45c7d086c7a.png)


## Create a visualization to show number of properties versus number of bedrooms:
![Screen Shot 2022-05-15 at 4 53 35 PM](https://user-images.githubusercontent.com/102244119/168495426-d2030040-6dd2-439d-99ce-778e49443f25.png)

