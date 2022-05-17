# Background Information:
Using Python Pandas skills, we have the capabilities of analyzing and answering business questions. The datasets used consist of 12 months worth of electronic sales with hundreds of thousands which are broken down by month, product type, cost,and etc. for certain products a company sells. 

## Cleaning Data:
Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Changing datatypes of columns (to_numeric, to_datetime, astype)

## Data exploration: 
To answer some business questions, many different pandas & matplotlib methods were utilized. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

### 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?

![image](https://user-images.githubusercontent.com/90146132/168719748-e15b340d-df31-443b-a949-b0cba5610d7d.png)

According to our bar chart, we can conclude that the month with the best sales were during the month of December. Sales were more than 4.5 million sales.

- What city sold the most product?

![image](https://user-images.githubusercontent.com/90146132/168720814-a7c6747d-744f-4d7c-b33e-796270f569ee.png)

We can conclude that San Francisco, CA had the most sales throughtout the year with more than 8.5 million sales.

- What time should we display advertisemens to maximize the likelihood of customer’s buying product?

![image](https://user-images.githubusercontent.com/90146132/168721367-586216f2-76ad-41a9-b8fe-e33a7f59a2ec.png)

Looking at the line graph, I recommend advertising around the hours of 11:00 and 18:00 to increase total orders

- What products are most often sold together?

![image](https://user-images.githubusercontent.com/90146132/168722054-f3d82d91-5c44-4010-990f-6893635a4290.png)

The iPhone and Lightning Charging Cable are the two products most often sold together.

- What product sold the most? Why do you think it sold the most?

![image](https://user-images.githubusercontent.com/90146132/168722459-222ffbea-e6c0-4e34-977a-3ab9dc3db516.png)

The product that sold the most was the AAA Batteries (4-pack).

![image](https://user-images.githubusercontent.com/90146132/168722812-eb89f6ad-64d4-46c7-a210-25dced56d3c7.png)
 
 By looking at the plot above, batteries are one of the cheapest items available which I believe is was is driving the quantity ordered since those prices are more attainable for purchasing those items.

