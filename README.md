# kickstarter-analysis
 trend analysis on a database
# Kickstarting with Excel

## Overview of Project

We have been given an excel file with information on different plays with which we can know the income it generates, the cost of creating a play and much more,
this analysis will be carried out to help Louis, an entrepreneur who intends to make the best decisions based on our advice , so that she can be able to fund the play that she wishes to undertake


### Purpose

The purpose of the analysis is to be able to visualize and understand the launch dates of plays similar to Louis's in addition to the funding goals,
this in order to identify any pattern that can give us more information about what can be done in the future.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By reviewing the pivot table and the graph ("Theater_Outcomes_vs_Launch.png") we can draw several conclusions. 
The first could be that fortunately there are more successful plays than failed or canceled ones, so it will be important to choose a month in which a play can be released.
The month with the most successful plays would be May and followed by June, on the other hand, the worst month with the most successful plays would be December with a total of 37.

Now if we analyze the case of failed plays, there really is no big difference too big where they will fail, it could be said that there is a high season of failed plays from May to August,
in addition to the month of October, where it could be said that there have been the largest number of plays that failed.

And in the case of the plays that were canceled, for me the only useful point to highlight is that there are no plays canceled in the month of October, for the rest,
the range of cancellations is maintained throughout the year. , although this is very low.


### Analysis of Outcomes Based on Goals

There are two main thoughts that come to mind when looking at both the graph and the table generated through formulas in excel.

The first would be that there are no canceled plays, according to our leaked information, if we look at the canceled percentage column, everything is at zero,
and we can verify it in the graph, and the second observation I have is that the Success and failure values ​​have an inverse correlation almost 100% I would say.

Since there are several variations throughout the progress of the graph, I could not say that there is any general rule such as saying that the lower the funding goal,the higher the success cases,
the best for this type of information would be based on establishing goals according to the ranges where it is seen that there are greater successes than failures


### Challenges and Difficulties Encountered

I really did not have any problems to process the data and its analysis, for much I could say that you should only be careful when accommodating the data within the pivot table,
because if we make mistakes and we accommodate the information wrong at some point , we will have results totally different from those expected, and therefore we will have a bad analysis 
and bad decision making

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first would be that the best months to be able to release a work would be May and June, despite the fact that they are in the season with the highest number of failures,
the difference between successes and failures is too great, so if I I would dare to suggest that it be released in those months

The second would be that they should not be released in the last quarter of the year, since the success and failure values ​​are too close, I would see no reason to accept such a risk



- What can you conclude about the Outcomes based on Goals?

As I said before, in my opinion they have a fairly high negative correlation, so I would only dare to recommend the ranges previously established in the graph where the cases 
of success are greater than those of failure, or even if one wanted to be more conservative. , I would only dare to set funding goals at a value less than 15,000.00


- What are some limitations of this dataset?

Well, it could be that the original database was a bit messy and therefore several changes had to be made, although really valuable information could be obtained after making the modifications.

In my case, I would have liked to know about the sponsors and who made the works, since if there was any relationship about them, this would let me wonder if it also influenced whether 
a play was successful or a failure. I would like to know what more of the funds are spent on, that it was more detailed, because that way it would be known a little more about what patterns should
 be followed to ensure as much as possible that a play is successful


- What are some other possible tables and/or graphs that we could create?


It would be interesting to carry out an analysis and a line graph between the backers_count and outcomes columns, since this way we could see if it is very important to have a large number of 
sponsors and what we should do or wait if we do not have the help of many
