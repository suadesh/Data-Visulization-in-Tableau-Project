# Dataset exploring with Tableau 

## Student : Massimiliano Z. D'Adamo
## Udacity NanoDegree Data Analyst 


------------------------

## [Tableau Public Link Final Version](https://public.tableau.com/profile/massimiliano.d.adamo#!/vizhome/DAND_UDACITY_Story_Final_version/Story1)

## [Tableau Public Link V_1](https://public.tableau.com/profile/massimiliano.d.adamo#!/vizhome/DAND_UDACITY_Story_V1/Story1)



## Summary: 

This data set use in this project is one of the dataset proposed by Udacity. it contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
One of the most interesting feature in this dataset is the *loan status*, that shows if the loan has been repaid or not. I mostly focus my attention to this features, looking for other features around it.


As shows at the beginning of the tableau story, __83,14%__ of the loans are completed, current or in the final payment stage. __15,04%__ are charged-off or defaulted while __1,82%__ are pas-due and around __0%__ are cancelled. 
The loans informations are from _2005_ to _2014_, and the more than __50%__ of the loans are from the last 3 of these years. 

We can clearly see in the graphics of the first slide the tremendous impact that the subprime crisis had in the late 2008, where there was completely stop of the loans. 

The story than explores briefly the geography of the loans, where we can see the amount and volume in us dollar of the loans. 

Than focusing on the economical informations of the borrower, like the employment status , the occupation and the income range. 
In the employment status slide , while the delinquencies in higher in the __not available__ category, the higher lander yield is for the __Not employed__ category. 
For the Income range is slide we can see how it has changed over time the income range of the borrower, and how the **richest** people demands increase over time. 
Also interesting is the average the loan for category with no income that was higher in the past, while all the other categories have a logical that respect their income. 

In the classification chart by top 10 occupations of the borrower , we can see that __professional__ was always the first one, while other categories moved over the years. __Clerical__ on the other hand moved almost at the bottom. 

Finally the story shows the reason of the loans, and as we can see the most of the loans are used for debt consolidation.

---------------

## Design: 

At beginning I used a similar colour palette  for the first 2 slides, but after a feedback I eventually chose to do not use orange in the second one and only a gradation of blue. 
The first and the third slides i used bar charts becouse i fell that they were more indicated for these description. In the this i removed the y axis information , and instate i added labels that i think help better have the understanding of the information given. 
For the second slide I used the map graph that i think is the best way to explain one or more geographical information. The fourth slide was challenging, at the beginning i used a staked area plot , but i received multiple feedback that it was not so clear, and in the end I chose the area chart, but not fixed, and i added 2 small plots with a simple line of the average, anf a classification chart. 
The last 2 slides are classifications graphics , that I learned to build after the udacity course and that i think are quite clear. 
In all the story pages, except the geographical one, i added the hoover action to make enchant the relation between each graphics in the slide with the same categorical feature. 
  

-------------------

## Feedback: 

At the beginning I used the same colour palette for the first 2 slides, blue to orange, but was to similar. So I change the second in a blue palette gradient that was better appreciate. 


I used for the income range area chart , the stacked version , but was not clear for the audience. The feedback was that eventually we are distracted from the information that the number of loans are very much lower at the beginning of the period, increasing systematically at the ed of the period. 

The classification charts were sometime to confusing to read, and to make it better , i added hover actions over every chart. This i think make very easy to pass with the mouse over , and read immediately the trend of the categorical value. 


-----------------------
## Resources: 

Udacity Data visualization in Tableau materials 

