# Telling-stories-with-Data
My Portfolio

# About Me
Hello! I am Ananya Ghosh from India. I am a graduate student at Carnegie Mellon University, studying Information Systems Management with concentration on Business Intelligence and Data Analytics. I have worked as a software developer at SAP Labs for almost 3 years. My work was primarily in the e-commerce domain. My career aspirations are to work as a Data Analyst or Data Engineer in a company that addresses social issues. 

My hobbies include travelling and discovering my hidden potential. I love to meet new people and listen to their stories.

# What I hope to learn
They say "A picture is worth a thousand words". Similarly when complex ideas are expressed in pictorial form, even the most inexperienced person can understand the context. I believe that there are many stories hidden in data which are waiting to be uncovered. I want to learn to find such stories and narrate them effectively using tools that I will learn in this class. 

# Portfolio
Hey
It's week 3 at Telling stories with Data class! This week's agenda is to pick a bad visualization from internet, critique it, build wireframes and finally fix the visaulization.
Inspired by a presentation on gun deaths in Florida, I looked up some more articles on similar lines. I found [this](https://www.theglobeandmail.com/news/world/gun-control-in-america-a-state-by-state-breakdown/article6465107/)
site and felt that "Gun Laws by State" circular chart needed some changes. 
I found the chart to be "too much data concised in one place". The chart didn't fit into one page and there was too much of eye travel required. The chart does engage the user by providing more information on hovering over each state but again, reading the corresponding data required a lot of eye travel.
The aim of the chart was just to show different gun laws. But maker of the chart tried to put in extra information such as murder rate which contributed to increased eye travel.
It also took me time to figure out what the grey spots in the inner circles were for.

After a lot of thinking I thought that there should be a separate graph showing the relation between overall gun control score and murder rate. That would remove the main concern of excessive eye travel.
I tried using several charts and graphs but somehow no graph appealed me enough. Ultimately I came to the conclusion that the original chart is the best way to descibe all those data.

Next, I took up a new [chart](https://www.personalitycafe.com/member-polls/1150770-do-you-have-friends-opposing-political-party-ideology.html). This article mentions about a transition planning meeting that happened in the Oval Office on November 10 2016. The entire article revolves around comparing Democrats and Republicans around different metrics. I found the graph "What news or commentary source do you trust most?" to be majorly flawed. Although it does manage to convey the message that Republicans support Fox news more but on a second look, the graph is rather absurd.

Using bar chart was the first option that came to my mind but I wanted to use something different from what I generally use so I tried to use pie chart and line chart instead. Here is my wireframe.

[<img src="https://ananya-ghosh.github.io/Telling-stories-with-Data/images/wireframe.jpg"  alt="wireframe" width="250px">](wireframe)


Critiques received from friends:
1. don't use two different charts to depict the same thing. 
2. Line chart shows progression over time. The message isn't as clear as it should be.

Final design:  
I ended up using one form of bar chart at the end but the new design highlights what the chart title reads. Republicans prefer Fox news which others don't.
In my chart:
1.Republican is highted to put more emphasis on Republicans. 
2.There is consistency in the labeling. In the original graph only one x-axis label had a unit (%) mentioned. 
  

<iframe title="Fox News Favored by Republicans " aria-label="Stacked Bars" id="datawrapper-chart-Uyvgn" src="//datawrapper.dwcdn.net/Uyvgn/1/" scrolling="no" frameborder="0" style="width: 250px; min-width: 25% !important; border: none;" height="195"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>
