# Excel: Kickstart My Chart

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this project, organization and analysis a database of 4,000 past projects are conducted in order to uncover any hidden trends.

## Actions


Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

* Used conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

  * Created a new column Q called `Percent Funded` that uses a formula to uncover how much money a campaign made to reach its initial goal.

* Used conditional formatting to fill each cell in the `Percent Funded` column using a three-color scale. The scale starts at 0 and is a light shade of red, transitioning to green at 100, and blue at 200.

  * A new column R was was created called `Average Donation` that uses a formula to uncover how much each backer for the project paid on average.

  * Two new columns where created, one called `Parent Category` at S and another called `Sub-Category` at T, which use formulas to split the `Category and Sub-Category` column into two parts.

  * A new sheet called 'Pivot Table - State' was created with a pivot table that analyzed the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **Parent category and Sub-Category**.

  * A new sheet called 'Pivot Table - Country' was created with a stacked column pivot chart that can be filtered by country based on the table that has been created.

  * Created a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

* The dates stored within the `deadline` and `launched_at` columns use Unix timestamps. Formula was input to convert these timestamps to a normal date.

  * Created a new column named `Date Created Conversion` that used formula to convert the data contained within `launched_at` into Excel's date format.

  * Create a new column named `Date Ended Conversion` that used formula to convert the data contained within `deadline` into Excel's date format.

  * Created a new sheet called 'Pivot Table - Year Month' with a pivot table with a column of `state`, rows of `Date Created Conversion`, values based on the count of `state`, and filters based on `Parent Category`,`Sub-Category`and `Years`.

  * Created a pivot chart line graph that visualizes this new table.

* Created a report in MS Word and answered the following questions.

1. Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create?

- - -

© 2019 Trilogy Education Services
