---
layout: post
title: Reflection Blog Post
---

For the following section, we(I and Lang Chen) wrote part of them as a group.

* Overall, what did you achieve in your project? 

We build an interactive webpage demonstrating data of the tax and transfer system by states using dash, flask, and plotly. This webapp could help people understand EITC and states EITC rules and be used to analyze the relationship between EITC and unemployment/poverty.


* What are two aspects of your project that you are especially proud of? 

We are especially proud of the interactive plotly graphs with detailed information and authoritative data source and presented it in webapp. Though it’s hard to draw any statistically significant relationship (we test that the regression significance in our case is pretty low), our data show that EITC does help alleviate poverty and decrease unemployment.


* How does what you achieved compare to what you set out to do in your proposal? (if you didn't complete everything in your proposal, that's fine!)

At first, we aim to construct models to calculate the optimal tax rate. However, through our research, we found that it’s much harder than we thought and requires more academic knowledge. Though we have the data, it’s difficult to adjust for the economic cycle and other possible factors. Hence, we narrow down our topics to EITC in the tax and transfer system and only draw conclusions from graphs. What we’ve achieved are data analysis and building an interactive web app.


* What are two things you would suggest doing to further improve your project? 

Now as we’ve shown that EITC has a positive effect, the next goal is to encourage more target poor working families to claim EITC and propose some policies to raise the amount of EITC. We can publish some policy memos and add links to direct users to EITC criteria and tax assistance in each state. After polishing it, we will deploy it using heroku and make it public.

As for the model development, we wish that we could gain more solid academic background, further explore available sources to develop better understanding and construct a more effective relationship between tax policy and other factors.


* What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc?

1. The first thing is definitely understand more about the webapp. Since we need to add interactive plotly graph to our webapp to make it possible for user to interact and make our graph be more useful in some degree, we learn about how to accomplish it by using dashboard and flask app, including jinjas, assets and structual aspects.

2. Actually though we fail to build up model based on the data, during the process of exploration, we did some regression model to test on the relevance of factor and whether the relationship is of statistical improtance. We learn more about how to do regression in python.

3. For the data collecting and data cleaning, we have data that belongs to different states and different time. When we did data processing, we learn more about groupby, filter, and other techniques.

 
* How will your experience completing this project will help you in your future studies or career? Please be as specific as possible. 

I believe that specific skills, like data cleaning, will definitely help me with my future studies when I need to deal with different dataset and want to gain specific form of information from the large dataset. Also, during the process of using webapp, I found that actually the presentation form can be really complex and nice, by using css and other style tools. I saw people actually use it to make financial report in a clean way, and I believe that probably I will try to use that to present my future work sometimes. Another thing that is kind of outside of techniques is that I found it is sometimes hard to gain needed information and being kind of lost from too many possible sources when you touch one novel field. In that case, after doing comprehensive exploration, I need further specify my goal and what I want to achieve, and then gain related source and develop my model base on that specific goal. I believe that this provides me better understanding about how to do future studies and even work in my career.

