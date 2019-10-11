## Project Outline
Finding a restaurant that suits your taste bud is a daunting task, especially when you have too many options to choose from. Restaurant finder apps do come to the rescue but do they really serve their purpose towards foreign students?
I met a lot of Chinese friends here at Heinz college. One problem that I found common to most of them was that they don't trust reviews given on Yelp and TripAdvisor. They find those two websites do not really give reviews that align with their taste buds. Instead, they rely on Chinese version of Yelp called Dazhongdianping. 
In this project I have investigated further into this difference in taste and preference. I collected information about all the restaurants in Pittsburgh and observed how ratings differed for different ethnic groups. I chose 4 websites - Yelp, TripAdvisor, Zomato and Dazhongdianping for this purpose.

I scraped data from 4 websites and drew some conclusions from them. I chose these four websites with an assumption that ratings given on Yelp and TripAdvisor reflect the likings of Americans or people who are not first generation Indians or Chinese. The ratings on Zomato reflect those who are more India while the ratings on Dazhongdianping reflect those of Chinese.
I found out what are the top cuisine categories across the 3 ethnic groups. I took first 4 most popular category and used boxplots to show how the ratings varied across different ethnic groups. 
The purpose of the project was to let my fellow classmates know that we, as foreign students, find it difficult to adjust with food here.

Project consists of three main elements.
First is my experience at a dinner with my Chinese friends and the findings at that dinner that led me to choose this topic.
Second is how I used the data collected from different websites to arrive at my final conclusion.
Third is spread awareness among my classmates that poeple can have different preferences when it comes to food. Be understanding and try to be sensitive towards people's likes and dislikes. Afterall good food is an integral part of good relationship!


Data collection was the most challenging part of the project. Since none of the data was publicly available, I had to use several python libraries to scrape data through all the websites. During the data collection process I faced a couple of problems:
1. When I searched restaurants on each of those websites, I saw that Yelp had the highest number of restaurants (around 4000). I built my extraction logic based on the data available on Yelp. But when I actually ran my scraping logic, I discovered that Yelp didn't let me collect information about all the 4000 restaurants. Pages weren't available after 800 restuarants. For this reason, I had to redesign my database and scraping logic for other websites.
2. Dazhongdianping had strong security mechanism which didn't let me access their restaurant information. I had to use a multi agent web crawling mechanism to dodge their security.
3. Most of the restaurants listed on Dazhongdianping was retrieved as Chinese characters. I had to use address field as a key to join all the four tables and contruct a single table.
4. When I did data analysis using python, I was surprised to see that there were hardly any Indian restaurant in the top 100 restaurants! I had to change my analysis because of this too.

I got four tables after collecting all the necessary data from all the four websites. I merged those four tables based on the following logic.
 
###### merging logic picture



My main approach to the project was building a merged data table and run some analysis on the data collected.
My aim was to create two types of graph.
1. a stacked bar chart to show the most popular cuisine types
2. how the ratings vary for a single category across different websites.


User Research
My target user group was my classmates. When I first walked into class, I saw that there were hardly any Indians or Chinese. In fact this was the first class in Heinz where I felt Indians and Chinese didn't outnumber people from rest of the world. During the introduction session on the first day, I also figured that people come from various professional background. I wanted to connect with such diverse set of people. And that's when I thought what could connect to people better than food!
Around the time when I had to decide on a topic, I went out for lunch with my Chinese friends. The discussions that we had at the lunch table along with my observations led me to come up with this topic.

I created the following storyboard for the user research:<br><br><br>
![<img src="./images/StoryBoard1.jpeg" width="100%">](https://ananya-ghosh.github.io/Telling-stories-with-Data/images/StoryBoard1.jpeg)
![<img src="./images/storyboard_updated.jpeg" width="100%">](https://ananya-ghosh.github.io/Telling-stories-with-Data/images/storyboard_updated.jpeg)
 
Since I was interested in mainly three ethnic group, I showed my storyboard to three people from three ethnic groups - America, Indian and Chinese.
I got very reaction about my topic but I observed that all of them could easily connect with my topic. 
They suggested that I should make the following modifications:
1. More charts are needed
2. Some points about history of Indian and American food can be better
3. Add context to memes

There was a critique session in class, during which I had to take opinion from my fellow classmates about my project. One of my really talented classmate suggested that I make a chart similar to beeswarm chart. I thought it to be a really good idea but implementating that chart didn't come up too well. Hence I had to drop that idea.

Choosing the best chart to depict the rating variance was quite difficult. As a student of statistics, boxplots was the first choice in mind but I wanted to explore more so that I could target people who does not have statistical background. But the more I searched for different graph types, the more I was convinced that boxplots were the best way to show variation. This goes back to one of the classes where Chris told us that there are untold conventions that you need to follow (like red represents danger, pink is for women, blue for men etc) And I felt that variance was best represented by boxplot.

Here is my final data story! 

I learnt a lot of things from this project.
1. Every time I thought of doing something, I always made sure that I took my audience's perspective into consideration. For example, my decision to do a project on food was something that I took solely based on my audience's interest. And it was during my user research that I realised that choosing a topic which everyone can connect to is the best way to keep everyone engaged.

2. I was part of Toastmasters club for a short while. When I joined this class, I thought my learning at Toastmasters was enough to sail through my final presentation. But that was no the class. Every step that led up to the final presentation played a very important part in shaping my final story. 

3. Visualizing data is not stressed upon in a day to day life, but when data is visualized in the right manner data can tell a lot of story. Coming up with a perfect way to tell story through data is really interesting but at the same time very difficult.

4. I feel that everything that I learnt in this class is applicable to other works of life. I worked as a software developer for three years. My job was client facing and I had to deal with a lot of UI/UX work. I could corelate a lot of things I learned in this class with the learnings I had from my job.


