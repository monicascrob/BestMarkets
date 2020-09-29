# Find the best markets to advertise in for a E-learning company project

We're working for an e-learning company that offers courses on programming. 
Most of the courses are on web and mobile development, but we also cover other domains, like data science, 
game development etc. We want to promote our product and to invest some money in advertisement. 

# Our goal:
Find out the two best markets to advertise our product in.

We can try searching existing data thart might be available for our purpose. 
We can start by exploring the data from [freeCodeCamp.](https://www.freecodecamp.org/news/we-asked-20-000-people-who-they-are-and-how-theyre-learning-to-code-fff5d668969/)
[FreeCodeCamp](https://www.freecodecamp.org/news/) is a free e-learning platform that offers courses on web development. They run a populat Medium publication and their survey attracts new coders with varying interests. The 2017 survey data is publicly available [here.](https://github.com/freeCodeCamp/2017-new-coder-survey)

# Checking for sample representativity

We need to clarify first if we have the right group of people for our analysis.
The JobRoleInterest column describes the role they'd be interested in working for each participant. 
That should mean that they would also like to learn more about that domain.

At a first glance at the frequency distribution, we can notice that:
 - many people are interested in web development
 - many people have more than one interest
 - a few are interested in mobile development

31% of the participants are focused on one domain, but the rest are looking at more options. 
This might be a good thing for us, because we offer various courses. 
Our main interest is in web development and mobile development, and we found that
86% are interested in Web Developer or Mobile Developer roles.

# Spending Money
The top markets are USA, India, UK and Canda, that are also English speaking countries (our courses are written 
in English), so we did our analysis on those locations and analyzed forward their monthly spending amount.

# Looking for extreme Ouliers
It was surprising to see that people in UK and Canada are spending less on learning than people in India, 
considering the GDP, so we checked the outliers and removed those that didn't seem justifiable.

# Choosing the Two Best Markets
Considering the results we've found, one country we should definitely advertise is US. We have a big number of 
new coders (over 70% were located in the US), that are also willing to pay around $143/month. 
Our monthly subscription is $59, so the second option we needed to choose was either Canada ($93/month) 
or India ($65/month).
UK was definitely out of the question, as the coders there pay around $45/month.

Considering that we have a higher number of potential custumers in India (11%) than in Canada(7%), 
if we can only choose 2 markets, the obvious choices are US and India.
Other options could be to either only advertise in the US or split the budget in 3 and cover the US, India and Canada.

# Conclusion 
In this project we analyzed the survey data for new coders to find the best 2 markets to advertise in. 
The solid conclusion we've got is that we should advertise in the US. 
Even if it isn't 100% clear if we should go with Canada or India for the second place, 
we cand definitely say we have good data to send to the decision makers and a few recommendations to move 
forward with. 