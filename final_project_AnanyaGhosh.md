## Overview - Food Recommendation System

### Outline:

When I first came to Pittsburgh, eating out was a nightmare. I had ample of apps to find out about the restaurants near me but my dining experience differed from that of the people who had reviewed the restaurants on those apps. As time passed, I befriended some Chinese friends. I noticed that they were using another app called Dazhondianping for finding out about restaurants. When I asked them why they didn't use Yelp or TripAdvisor, they said they didn't like the restaurants that had high rating on Yelp and TripAdvisor. Moreover, restaurants that had low rating on Yelp and TripAdvisor had good rating on Dazhondingpian. This conflict of interest made me curious to find out about the food preferences of people from different ethnic groups.

I have selected four websites - Yelp, TripAdvisor, Zomato and Dazhongdingpian - whose customer base varies from American to Indian to Chinese.

I have collected the following data about restaurants in Pittsburgh by scraping those 4 websites:
Name: 	                        name of the restaurant<br>
Address: 	                    street address<br>
Area: 	                        neighbourhood<br>
Phone: 	                        contact number<br>
Price : 	                    price range $-$$$$<br>
Category:  	                    Italian,American...<br>
Yelp_rating: 	                restaurant rating on Yelp (0-5)<br>
Yelp_number_of_reviews:	        number of reviews received on Yelp<br>
Yelp_review: 	                customer’s comments on food experience on Yelp<br>
Zomato_rating: 	                restaurant rating on Zomato (0-5)<br>
Zomato_number_of_reviews: 	    number of reviews received on Zomato<br>
Zomato_review: 	                customer’s comments on food experience on Zomato<br>
Tripadvisor_rating: 	        ratings from Tripadvisor<br>
Tripadvisor_number_of_reviews: 	number of reviews received on Tripadvisor<br>
Tripadvisor_review: 	        customer’s comments on food experience onTripadvisor<br>
Dazhongdianping_rating: 	    restaurant rating on Dazhongdianping<br>

* Correlations:<br>
    I will make the following comparisons:<br>
        - Most popular cuisine types in top 100 restaurants <br>
        - How the ratings of Indian restaurants vary in all four websites <br>
        - How the ratings of Chinese restaurants vary in all four websites <br>
        - How the ratings of American restaurants vary in all four websites <br>
        - How the ratings of other restaurants (like Ethipian, Italian etc) vary in all four websites <br>
        
At the end of this project, I am hopeful I will be able to find out about the taste and preferences of different ethnic groups and how they are differet from each other. I will also be able to create awareness that people from different places have differernt tastes, so next time someone is out with an international crowd, maybe they'd like to think more deeply about the food choices!


Here are few of the visualizations which I aim to establish:





![Project_Outline](https://raw.githubusercontent.com/sagnikrana/Portfolio-Telling-Stories-Using-Data/master/Final%20Project/Images/0001.jpg)

I am going to use shorthand to narrate my story. I would like to use Tableau to make the visualizations.

Here are few of the data sources: <br>
I used Beautiful Soup library in Python to scrape data from all the four websites.
Yelp Link: https://www.yelp.com/search?find_desc=Restaurants&find_loc=Pittsburgh%2C%20PA&start=0<br>
Zomato Link: https://www.zomato.com/pittsburgh<br>
TripAdvisor Link: https://www.tripadvisor.com/Restaurants-g53449-Pittsburgh_Pennsylvania.html#EATERY_OVERVIEW_BOX<br>
Dazhondingpian Link: http://www.dianping.com/pittsburgh/ch0<br>

Excel sheet containing all the scraped data can be found [here] (https://ananya-ghosh.github.io/Telling-stories-with-Data/ScrapedData/ScrapedData.xlsx)


NOTE: This project is strictly for academic purpose
