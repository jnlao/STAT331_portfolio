# Assignment Feedback and Revisions

## Lab 3

### Summary

#### Feedback

Zero is one way missing values were coded, but there is another way. Look through the data documentation to find the other method used to code missing values and describe the benefits / drawbacks of this method.

#### Revision Reflection

I didn’t look hard enough in the information sheet so I missed where it stated that missing values were replaced with mean values. In the future, I will look more thoroughly through documentation to find my answers instead of glancing or skimming.

### Question 3

#### Feedback

I strongly recommend against nested functions, as they are difficult for people to understand what your code is doing. Having two lines is not less effficient and is more readable.

#### Revision Reflection

I’m used to using nested functions for my code but I understand how it can cause confusion when trying to figure out what the goal of my code is. In the future, I will strive to stray away from nested functions in order to keep my code more organized and readable! When working in RStudio, we can see the values in objects in the environment so I relied on that for the answer to the question but I failed to remember that the environment isn’t available in the HTML file. For future assignments, I will be more mindful about how the output of the code written can help answer the problems instead of relying on the environment for answers.

### Question 5

#### Feedback
I don't see these demographics nicely summarized and output…

Look at your output! Does that look right? How many subjects should there be?


#### Revision Reflection

I also relied on the environment for my answers and I added information that wasn’t necessary for the question such as city and county. I outputted the information needed for the demographics instead of relying on it being stored in the environment and I will also try to be more mindful about how/where my information is stored when I write code for future assignments.

### Question 6

#### Feedback

Nice work plotting your visualizations side-by-side!

Look at your y-axis! Do these counts make sense? How many should there be?

#### Revision Reflection

I was able to use the demographics data I got from fixing question 3.7. Before creating an object with each distinct subject, I relied on my entire cleaned hiphop dataset but after revisions, I realized that I had all the information and counts needed in the demographics object. In the future, I will be more mindful in which datasets I use for plotting, especially since it helps keep count of the unique subjects involved.

## Challenge 3

#### Feedback

Great work! You are on the right track! The next step is to find the differences in these means. Could you use another summarize() step to get these differences?

Where is the code output to confirm your summary?

#### Revision Reflection

I didn't fully understand the question at the time of doing the assignment and using summarize() to get the difference between the means did not cross my mind at all. I probably would have calculated the differences by hand/eyeballed it but after your suggestion to use another summarize() for the difference, I understood what to do better.  I've noticed I've been having a hard time noticing when to display output vs not display it so I will try harder to pay attention to when the question requires output for my answer or not. I hope to fix this problem of mine in lab5 and later assignments.

## Challenge 4

### Question 7

#### Feedback

Interesting idea, but the scales of house prices and avocado prices are substantially different. So, plotting them on the same axis is really difficult. Some people would choose to use a dual axis, which I stray away from because they are difficult to interpret. I think a more clear comparison would be to plot the relationship between home price and avocado price and color by year!

#### Revision Reflection

In order to solve the problem with the scales of the two prices being different, I scaled down the housing prices by 100,000 (as noted in the axis label). I knew I wanted to show a correlation between the two but I was over complicating how to approach the problem, which resulted in my first submission. After taking your advice, and plotting based on price and year, I think what threw me off was being able to display the regions (which is why I originally faceted by region) but I fixed this by having each region be its own symbol. In the future, I need to trust my gut and be less afraid to ask questions because they will probably save me a lot of time and over thinking!

## Challenge 7

### Question 2

#### Feedback

What data type do you want min_val and max_val to be?

#### Revision Reflection

While creating my out_of_bounds function, I forgot that it is good practice to always check to make sure my input values are what I expect them to be. I assumed that I would always pass in the right thing and forgot to check the type of the parameters. I will try to keep this in mind on future assignments because it is possible I won't be inputting the correct data one day and this could potentially break my code when it can be easily prevented through a type check.

### Question 3

#### Feedback

I’d be interested to know why you chose these thresholds!

#### Revision Reflection

During my first submission, I used generic measurements for the trout based off the data but this time, I used metrics I found off of the Montana field guide regarding the trout length measurements and then I used those measurements to get an estimated weight on another website. 

### Question 5

#### Feedback

There’s something going on with these lines! geom_line() expects for there to be one observation for each year. Is that the case? If not, what can you do to make this the case?

#### Revision Reflection

For the visualization at the end, I wasn't sure how to fix my line graph but this time, I got an average of the CI's for each fish per year and was able to graph those. I believe the visualization looks much better now and it's easier to see how the CI changed for each year and each trip. In the future, I will try harder to research more about how functions work to make sure my input is correct.

## Lab 9

### Question 2

#### Feedback

Is there a tidyverse function that you can pipe your data into and can take the place of 

allison_both_sexes[is.na(allison_both_sexes)] <- 0 ?

#### Revision Reflection

I read about the coalesce() function but didn't know how to implement it so I stuck with this method. After the revisions, I asked my group mates for suggestions on how to remediate this problem and one of them told me how to use the coalesce() function. After looking at my peer review, I realize that the solution to this problem was a little easier than I originally thought and I think I just had a brain fart while trying to finish this assignment. In the future, I should reference past labs and assignments to keep me on the right rack.

### Question 3

#### Feedback

Do I want to include Male Allisons in #3?

#### Revision Reflection

I thought I had filtered out male Allisons for this question but I probably messed up somewhere along the way. Looking back, I already had the answer to this question in question 2- I just needed to select the proper column which was a silly mistake on my part. 
