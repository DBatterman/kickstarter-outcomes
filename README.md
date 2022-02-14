# kickstarter-outcomes
Looking at the outcomes of kickstarter data based on launch date and goals

## Overview and Analysis 

The purpose of this project was to help our client successfuly launch a kickstarter campaign for her upcoming play. To do this, we analyzed data from various fundraising efforts across different timetables and for different subjects so we can give our client the best chance for success. This particular analysis looked at how successful campaigns were based on when they were launched, and how successful campaigns were based on the amount of money they were trying to raise.

## Analysis and Challenges 

We ultimately analyzed this data using the functions in Excel. THe first result was looking at how successful a campaign was based on the month it was launched. This was achieved by using the Years() function, and then grouping the results by month. Our data ended up looking like this:

<img width="389" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/98666269/153811535-6a50c6c3-9a6a-467d-8057-12634ff1d582.png">

The second result was looking at how successful a campaign was based on its total fundraising goal. It was compiled using the CountIFs() function in excel, and looks like this:

<img width="547" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/98666269/153811743-7b7409fa-8fdb-4981-a888-f034832fb55d.png">

The challenges I personally had were all about how to apply the new techniques we learned in this challenge. It took me a while to figure out how to correctly group the data in order to display the months instead of the years for the first project in the pivot table. I also struggle a bit with arranging pivot tables, but I know that will get ironed out with more experience.

As for the second deliverable, I was pulling from the wrong column on two seperate occasions. This made my data not show the correct information when given the sample. It made me realize the importance of double checking my work as giving the wrong results to a client could be disasterous. 

## Results 

###### What are two conclusions you can draw about the Theater Outcomes by Launch Date?

The first conclusion that I can draw is that the best month to launch a theater based kickstarter is May. Roughly 67% of campaigns were successful during this month across the years spanned in our data were successful. June was the second best month at 65%, so it's likely that early summer is the best time for these campaigns. The second conclusion is the flip side - December is the worse month to start a campaign. Only 49% of kickstarters were funded in December, likely due to people spending money for the holidays.

###### What can you conclude about the Outcomes based on Goals?

It seems like the most successful ranges for plays are either very small or relatively large. The best range is around $5000 or less, followed by 35000 to 45000. 

###### What are some limitations on the dataset?

Some limitations that I can see on the dataset are the fact that you don't know where the donations are coming from. It also doesn't give an explanation as to what about a particular campaign allured donaters to give their money. I cannot see a good reason as to why campaigns did so well in May or June, as well as why the 35000 to 45000 benchmark rebounced compared to the rest of the dataset. It would be curious to see what caused those trends.

###### What are some other possible tables and/or graphs we can create?

We can look at campaigns launched in different countires and their goals to see if there was any regional bias for what drew donations where. We also can see what countries had different subcategories of campaigns to gauge popularity in certain nations.
