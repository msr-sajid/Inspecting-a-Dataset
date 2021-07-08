# Inspecting a Dataset
As a data analyst, I use data to answer questions and solve problems. When I analyze data and draw conclusions, I generate insights that can influence business decisions, drive positive change, and help stakeholders meet their goals.<br> 
<br>Inspecting the dataset helps me pinpoint what questions are answerable and what data is still missing. I may be able to recover this data from an external source or at least recommend to stakeholders that another data source be used.<br>
## The Scenario
You are a data analyst working for an ice cream company. Management is interested in improving the company's ice cream sales.

The company has been collecting data about its sales—but not a lot. The available data is from an internal data source and is based on sales for 2019. You’ve been asked to review the data and provide some insight into the company’s ice cream sales. Ideally, management would like answers to the following questions:

1. What is the most popular flavor of ice cream?
2. How does temperature affect sales?
3. How does profitability differ for new versus returning customers?

### Inspect the data
<b>Question 1:</b> What is the most popular flavor of ice cream?<br>
To discover the most popular flavor, I first need to define what is meant by "popular." 
- Is the most popular flavor the one that generated the most revenue in 2019? 
- Or is it the flavor that had the largest number of units sold in 2019? <br>
Sometimes my measured choices are limited by what data I have & I can review spreadsheet to find out if either of these definitions of “popular” make sense based on the available data.  

Click the <b>flavors sheet</b>, it has three columns and 209 rows of data. The column headers are <b>week</b>, <b>units sold</b>, and <b>flavor</b>. This dataset did not come with a data description, so I have to figure out the significance of the columns on MY own. Based on the data, I deduce that these columns provide information about the number of units sold for each ice cream flavor, by week, in 2019. <br>
![image](https://user-images.githubusercontent.com/80061230/124871791-1c940e00-dfe2-11eb-8a59-477581ff0a65.png)<br>
In this case, I discovered what the most popular flavor is by using units sold as measure. In particular, I used the <b>units sold</b> column to calculate the total number of units sold during the year for each flavor. Unfortunately, the dataset does not provide the annual sales amount by flavor. In this case, next step would be to ask stakeholders if the annual sales per flavor data is available from another source. If not, I can add a statement about the current data’s limitations to my analysis.<br><br>
<b>Question 2</b>: How does temperature affect sales?<br>
To explore second question, I clicked the temperatures tab and check out the data. The <b>temperatures sheet</b> has two columns and 366 rows of data. The column headers are <b>temperature</b> and <b>sales</b>. The data may show total 2019 sales per temperature (for instance, the first entry might sum up $36.69 in sales for three separate days that each had a high of 60 degrees). Or, the data may show  a snapshot of sales and temperature for each day in 2019 (for instance, the first entry might refer to a single day with a high of 60 degrees and $39.69 in sales).<br>
![image](https://user-images.githubusercontent.com/80061230/124872744-439f0f80-dfe3-11eb-90d4-62e1433521d4.png)<br>
So, which is it? It’s probably a daily snapshot because there are 365 entries for temperature, and multiple rows with the same temperature and different sales values. This implies that each entry is for a single day and not a summary of multiple days. However, without more information, I can’t be certain. Plus, I don’t know if the current data is listed in consecutive order by date or in a different order. My next step would be to contact the owner of the dataset for clarification. 

If it turns out that temperature does affect sales, I’ll be able to offer stakeholders an insight such as the following: “When daily highs are above X degrees, average ice cream sales increase by Y amount. So the business should plan on increasing inventory during these times to maximize sales.”<br>

<br><b>Question 3</b>: How does profitability differ for new customers versus returning customers?<br>
Datasets does not contain sales data related to new customers. Without this data, I won’t be able to answer my final question. However, it may be the case that the company collects customer data and stores it in a different data table. 

If so, my next step would be to find out how to access the company’s customer data. I can then join the revenue sales data to the customer data table to categorize each sale as from a new or returning customer and analyze the difference in profitability between the two sets of customers. This information will help stakeholders develop marketing campaigns for specific types of customers to increase brand loyalty and overall profitability. 

## Conclusion
When working on analytics projects, I won’t always have all the necessary or relevant data at your disposal. In many of these cases, I can turn to other data sources to fill in the gaps.<br> 
<br>
Despite the limitations of dataset, it’s still possible to offer stakeholders some valuable insights. For next steps, my best plan of action will be to take the initiative to ask questions, identify other relevant datasets, or do some research on my own.  No matter what data I'm working with, carefully inspecting data makes a big impact on the overall quality of my analysis. 
