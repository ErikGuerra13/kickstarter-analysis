# kickstarter-analysis

## Overview of Project

    In this project we are assisting Louise to find out how different theater plays performed by month and also in comparasion to their fundraising goals. By combing through this data we provided Louise with a visual representation for both their launch dates and their funding goals. Providing this visualization will make it much easier for Louise to understand the data instead of having to comb through a large amount of data manually.

### Purpose

    The purpose of this project is to provide Louise with the necessary information for her to know how well theater plays performed in certain months and how they performed in comparasion with their funding goals. This will allow Louise to know which months were the most successfull and also be able to know if the funding goals can have an affect if the plays are successfull or not. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

    In order to better visualize the data in the kickstarter workbook we created a pivot table and line chart to see theater outcomes by launch date. We accomplished this by placing the appropiate fields in the pivot table and filtering by successful, failed, and canceled. This allowed us to get a better understanding how campaigns performed in certain months. Once we had our pivot table created this allowed us to create a visual representation of the data by creating a line chart found in the link below. 

    [Outcomes Based on Launch Date]https://github.com/ErikGuerra13/kickstarter-analysis/blob/bc1ae828c8416d454801eaaa97791e68f0e611fa/resources/Theater_Outcomes_vs_Launch.png


### Analysis of Outcomes Based on Goals

    Louise also wanted to know how the campaigns performed in comparasion to their funding goals. To accomplish this we created a line chart to better visualize the date. To do this we had to first gather our data from the kickstarter worksheet. The campaigns had 12 funding goals ranging from less than $1000 to greater than $50,000. We used the COUNTIF() function to calculate the total number of successful, failed, and canceled in each of the 12 funding goal ranges. After using the COUNTIF() function this allowed us to calculate the percentage of each outcome. This in turn allowed us to visualize the data using a line chart shown in the link below. 

    [Outcomes Based on Goals](https://github.com/ErikGuerra13/kickstarter-analysis/blob/bc1ae828c8416d454801eaaa97791e68f0e611fa/resources/Outcomes_vs_Goals.png).



### Challenges and Difficulties Encountered

    One of the challenges I encountered at first was using the COUNTIF() function to calculate the total number of succesfull, failed, and canceled campaings. At first I was getting erros or numbers I knew that were incorect and it turned out to be because I still had filters on my kickstarter worksheet. Once I removed those filters I was able to get the correct data that I needed. I quickly learned the importance of having the correct data. One other challenge I ran into was when I was calculating the the total number of canceled campaings. I was getting 0 across all funding goals and at first I thought it was due to an error with my COUNTIF() function but have quickly going through the data in the manually and using filters I was able to confirm that there was in fact no cancelled theater plays based on the criteria we were looking for. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    Two cononclusions we can draw about the outcomes based on launch dates is that we can see that theater plays had great success in the summer months of May, June, and July, with May having the best month with a total of 111 successful campaigns. The second conclusion is that winter months struggled the most, December having the lowest amount of successful plays. With this information we can conclude that Summer time is better to launch a campaign.

- What can you conclude about the Outcomes based on Goals?

    We can conclude that projects in that had a lower funding goal had a higher percenatage of success with the less than $1000 having the highest success rate. The second highest success percenatge is the next goal category of $1000 to $4,999. In my opinion this shows that a higher funding goal does not gaurentee that the theater play will be succesful. 

- What are some limitations of this dataset?

   In my opinions one of the limitations of our dateset would have been to also add the campaigns that are currently live so that we can also get a better understanding to how those a performing as well. 

- What are some other possible tables and/or graphs that we could create?

    Being able to easily visualize data is extremely important and I believe that also using a bar graph for the total number of succesfull, failed, and canceled campaings based on their outcomes would help Lousie as well. 
