---
layout: post
title: Project 2 Blog Post
---
Sarah McLaughlin 

[Link to Project](https://sarahmclaughlin.github.io/ST558_Project_2/)   

# ST 558 Project 2

**Outline of Project**  
In this project, I had two objectives. Predict the number of shares of an article by using a linear model and an ensemble model. For my project, I tried to outline my thought processes behind each of the models: why I picked them, which variables I used a why, why I didn't pick some models, etc. Another objective was to use a github repo for the project (I ran into an issue that I will discuss later but proved beneficial to my learning) and to use rmarkdown for automation of reports. 

**What would you do differently?**  
When I first began this project, I found it to be fairly straight forward. It was really just the past few homework assignments put into a project and working with a larger data set. I will admit that I struggled with the linear regression. I ended up doing a logistic regression because my multiple linear regressions were so poor. The number of variables was overwhelming. I realize this is a class specifically for coding but it was difficult knowing how to code a model but not having enough understanding to create a good/better model. My adjusted R-Squared was so small. This proved to be very difficult for me. On the coding side, I am content with my understanding. (I realize that this is the age old statistics question: "What makes a good model and how can we make it better?" As someone who prefers straightforward answers and directions, this takes some getting used to.)  

I had chosen Random Forest for my ensemble model because it is better than the bagged trees and not as slow as boosted trees. The Random Forest still took awhile to run, though. My first model got a very low misclassification rate - suspiciously low. Not really sure what happened there.  

**What was the most difficult part for you?**  
Aside from the linear regression issues, working with the github repo proved to be difficult for me. Firstly, I couldn't get my README.md file to be the homepage for my repo. I researched how to fix this and it took awhile to find an answer. In the end, I just deleted the index.md and that fixed the problem. 

I assumed that the automation of the reports would be the most difficult part, but that was very straightforward. The code I used for that can be found [here](https://sarahmclaughlin.github.io/ST558_Project_2/Render-Code.html). 

Another issue I had in my repo was after I had automated my RMarkdown Documents. Originally, I had made htmls for each day but had to instead create the md files. I had tried to push the markdown files for each day to the github repo but I had received an error. The error said something about how the changes were too big or that my local repo was too far ahead of my repo on Github. It would not let me push the md files to my repo. As an act of desperation, I just manually uploaded them to my repo. However, this made things worse. It still would not led me push my commits to the repo. I had deleted the html files I had made from github but not from my repo on my computer. This caused an issue. Eventually, I figured out that my git in RStudio had these little boxes next to the files where I could merge, delete, overwrite, etc. I needed my repo on my computer to better match the one on github. (I apologize for not being better able to explain the issue; I am still getting familiar with github.) Once, I did that, I was able to push my commits to github. Originally, I had merged my md files within RStudio but that just added the md text to the md file I had uploaded manually. I fixed this by committing again the md files, which were then overwritten to the md files. It all worked out in the end but it was stressful at the time.  

Another difficult part with these projects is I struggle to decide how much of my process I should include in my project. I had issue with cache-ing and due to my long run time, it was hard to change one thing and then have to wait awhile to see if it worked. I wish I was able to have a sort of "scratch paper" where I put all of my rejected models, include my rejected models in the project without actually running the code, and discuss why they were rejected. 

**What are your big take-aways from this project?**  
Again, I feel comfortable in my ability to code. My lack of statistical understanding had led me to believe that I had coded incorrectly. Looking back, I am thankful for my github issues as I had learned much from it (I had virtually no issues with github during Project 1) but at the time is was terrible. I really appreciated working more with the ensemble model, too! I feel like I really understand this type of model and am comfortable using it in the future.  
