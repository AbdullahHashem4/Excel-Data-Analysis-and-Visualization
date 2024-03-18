# Excel Data Visualization Projects 💹 
## Global Tech Experience Internship - Excel Analysis

**1. Youtube Dataset:✅** In this project, I analyzed trending patterns across various video categorieso from Youtube in Excel. 
- I identified numeric columns, excluding certain ones like trending_date, publish_time, and category_id from standard numerical treatment due to their contextual relevance. 
- Additionally, I recognized text columns lacking natural ordering for interpretation beyond their textual representation.
- Further, I determined the number of boolean columns in the dataset. 
- Using functions, I determined the total number of videos, total likes, and average views on trending videos. 
- By sorting and filtering, I found the count of videos published before 2010, the most viewed video outside of Music or Entertainment categories, videos in Gaming and Nonprofits & Activism categories exceeding 10 million views and the average views respectively. 
- Finally, based on the analysis, I concluded that hitting 2 million views in categories like music, gaming, film, and animation isn't particularly exceptional due to the massive fan bases and typical view counts associated with successful content in these genres.

**2. SF Bart Daily Exits Dataset:✅** In this project, I conducted an analysis for the Bay Area Regional Transit (BART) to assist in making data-driven decisions regarding the next round of major trackway repairs. Using daily exit data for all train stations in the Bay Area, I performed the following tasks:
- Extracted the month from each date in the Month column.
- Extracted the day of the week from each date in the DayOfWeek column, with Monday designated as 1 and Sunday as 7.
- Engineered the YellowLine column to capture whether a station is on the Yellow Line by extracting the first letter from the Lines column and determining if it corresponds to the Yellow Line, labeling stations accordingly as "Yes" or "No."
Utilizing these engineered columns, I answered the following questions:
- Determined the total number of passengers who rode BART in all of 2021.
- Calculated the total number of rows of data.
- Analyzed the total number of passengers who rode during weekdays.
- Identified the total number of passengers who rode on the Yellow Line.
- Calculated the proportion of all passengers that ended on a station on the Yellow Line. Additionally, I provided an optional - LevelUp task where I extracted whether a station is one of the four stations in downtown San Francisco.

**3. DoorDash Delivery Dataset:✅** In this project, I conducted an exploration of delivery times and cuisine trends in major cities across the U.S. to assist the marketing team in rolling out coupons and promotions. Here's what I accomplished:
- Filled in the delivery_time column with the number of minutes it took between when an order was created and when it was delivered.
- Determined the average number of minutes it took for orders to be delivered across all orders in the data period.
- Calculated the standard deviation for the number of minutes it took for orders to be delivered.
- Created a PivotTable summarizing the total number of orders made, the average delivery time, and the average price of orders made in each market region.
- Identified the market with the highest total number of orders, the market with the lowest average delivery time, and the market with the highest average order price.
- Created a new PivotTable summarizing the total number of orders made by the primary category of each store, sorted by the number of orders made in descending order.
- Determined the most popular overall cuisine type and modified the PivotTable to add a grouping by market region and change the count of orders to be a percentage within each market region.
- Calculated the percentage of orders made in Boston from places labeled as 'chinese.'
- Identified the number of regions where the most popular overall cuisine was also the most popular within an individual market region.
- Determined the region with the highest percentage of orders coming from a 'sandwich' shop. Additionally, I completed the optional LevelUp activity by creating a PivotTable of the average delivery time by cuisine type, sorted it, and created a horizontal bar chart. The cuisine with the shortest average delivery time was highlighted in the PivotTable.

**4. Winter Sports Dataset:✅** In this project, I examined Google search trends of Winter Olympic sports to gauge interest in various winter sports over the years. Here's what I accomplished:
- Created a line chart capturing the trend in interest levels in "curling" over the recorded time span, revealing a noticeable rise in search interest around the beginning of winter and a decline around the end of winter. This seasonal pattern aligns with the traditional timing of the curling season, as the sport is often associated with colder months.
- Summarized the chart's findings, noting the repeating patterns in search interest for curling and attributing them to the sport's connection to colder months, with increased interest likely influenced by factors such as the start of curling competitions or public awareness during the winter season.
- Created a line chart capturing the trend in interest levels in "luge" over the recorded time span, contrasting its pattern with that of curling. Identified a notable spike in search interest between mid-2009 and early 2010, peaking in February 2010, likely due to the Winter Olympics that year, indicating heightened curiosity and global interest during major events.
- Created a line chart capturing the trend in interest levels in "hockey" and "snowboarding" over the recorded time span, describing their general trends as consistent increases at the start of each winter, followed by declines at season's end. Noted snowboarding's significantly higher overall interest compared to hockey and highlighted prominent peaks in early 2010 and early 2018, suggesting noteworthy events or competitions during those periods.
- Utilized the table to create a bar chart capturing the average interest in remaining sports: Speed skating, Nordic combined, Biathlon, Alpine skiing, and Bobsleigh, determining that Bobsleigh had the highest average search interest among the plotted Olympic sports.
- Completed the optional LevelUp activities by creating a horizontal stacked bar chart of search interest levels for speed skating, alpine skiing, Nordic combined, biathlon, and bobsleigh during February of the Olympic years and recreating the table of average search interest values of the listed sports.

**5. H&M Email Engagement A/B Test Analysis:✅** In this project, H&M aimed to enhance email engagement by altering the subject line of their marketing emails. Here's how I conducted the analysis and interpreted the results:
- Stated the null hypothesis: Changing the marketing subject line will NOT improve the opening rate of emails.
- Stated the alternative hypothesis: Changing the marketing subject line will improve the opening rate of emails.
- Utilized an A/B Test Sample Size Calculator to determine the minimum detectable effect associated with the desired increase in open rate and the total sample size required to reliably detect that level of increase.
- Created a PivotTable summarizing the total number of emails sent out to customers in each group and the number of times each version of the email was opened.
- Calculated the difference in the number of emails sent to each group and the difference in the number of emails opened in each group.
- Utilized an A/B Test Significance Calculator to determine the conclusion from the A/B test, assuming a statistical significance level of 5%. Concluded that Test "B" converted 10% better than Test "A" with 98% certainty, and that the A/B test is statistically significant, leading to the rejection of the null hypothesis.
- Identified the possibility of making a type I error if the truth is different from the conclusion drawn from the data, resulting in mistakenly concluding that changing the marketing subject line improves the opening rate of emails when it does not.

**5. A/B Testing Dataset:✅** In this project, H&M aims to boost email engagement by altering the subject line of their marketing emails. Here's how I analyzed the data to determine if the changes increased the conversion rate:
- Joined information about users and countries into the Orders table by filling in the country code and full country name for each purchase, as well as whether the user came in from a referral.
- Created a PivotTable from the combined Orders table showing the average money spent per order by country and referral status, revealing the average spent per order among all non-referral users and referral-using users.
- Identified the number of countries where non-referral users spend more per order than referral users.
- Created another PivotTable from the Orders table showing the total number of orders and revenue made by orders from non-referral and referral users, determining the revenue made from each group.
- Created a second PivotTable from the Users table showing the number of non-referral and referral users.
- Calculated the company's payout for new referral users and determined the average number of purchases made by each user group during the promotional period.
- Characterized the success of the referral program, concluding that despite the associated payout costs, the program was successful in driving higher revenue and engagement, recommending its continuation.
  Suggested additional analyses such as considering Customer Acquisition Cost and Referral Conversion Rate for a more informed judgment.
-Finally, I created a PivotTable showing the total consumer spending by country and the breakdown of spending by referred customers and customers without referrals.

**6. Referral Campaign Dataset:✅** In this project, I was tasked with assessing the effectiveness of their referral campaign, here's how I conducted the analysis and provided recommendations:
- Utilized the XLOOKUP function to join information about users and countries into the Orders table by filling in the country code and full country name for each purchase, as well as indicating whether the user came in from a referral.
- Created a PivotTable from the combined Orders table using XLOOKUP, showing the average money spent per order by country and referral status, identifying the average spent per order among all non-referral users and referral-using users, and determining the number of countries where non-referral users spend more per order than referral users.
- Utilized XLOOKUP in another PivotTable from the Orders table to show the total number of orders and revenue made by orders from non-referral and referral users, calculating the revenue made from each group.
- Employed XLOOKUP in a second PivotTable from the Users table to show how many non-referral and referral users there are.
- Identified the payout for new referral users and determined the average number of purchases made by each user group during the promotional period.
- Characterized the success of the referral program, recommending its continuation based on the higher revenue generated and increased engagement from referral users, despite the associated payout costs, and suggesting optimization to reduce costs while maintaining or enhancing effectiveness.
- Suggested considering factors such as Customer Acquisition Cost and Referral Conversion Rate for a more informed judgment about the program's success.
- LevelUp: I proposed creating a PivotTable using XLOOKUP showing the total consumer spending by country and the breakdown of spending by referred customers and customers without referrals.

**7. Mobile Site Survey Dataset:✅** In this project, Warby Parker rolled out a new mobile website, and I assessed its effectiveness for users through the following steps:
- Task 1: Analyzing User Satisfaction with the New Mobile Website
In this task, the objective was to evaluate the impact of changing the heading of the landing page on user satisfaction for Warby Parker's new mobile website. The null hypothesis stated that the change would not significantly affect user satisfaction, while the alternative hypothesis posited that it would have a significant impact. Using the Data Analysis ToolPak, a two-sample t-test assuming unequal variances was conducted on survey responses, comparing ratings for the new version with ratings for the old version. The statistical analysis revealed that, at a 5% significance level, there was insufficient evidence to reject the null hypothesis, suggesting that the change in the heading did not significantly impact user satisfaction.

- Task 2: Addressing Potential Errors and Providing Advice for Future Experiments
This task involved considering the possibility of making a Type II error, wherein a false null hypothesis is not rejected despite the existence of a significant effect. Additionally, advice was offered to the web team on setting up follow-up A/B tests or experiments. It emphasized the importance of involving the data team from the outset to ensure well-designed experiments, appropriate data collection, and thorough analysis, leading to more accurate results and actionable insights.

- Task 3: Exploring Trends in User Data by Region, Age, and Income
The LevelUp! worksheet contained user data, including region, age, income, and ratings, sorted in ascending order by user score. Three pivot tables were created to analyze variations in user ratings, ages, and incomes by region. Additionally, users were categorized into age groups based on whether they were 25 or older, and a pivot table was generated to compare user ratings between younger and older users. These analyses aimed to identify any notable trends or patterns in user data that could inform future strategies or optimizations for the mobile website.
 
