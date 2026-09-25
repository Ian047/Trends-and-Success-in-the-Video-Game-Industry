Project Description:

You work for the online store Ice, which sells video games worldwide. User and expert reviews, genres, platforms (e.g., Xbox or PlayStation), and historical game sales data are available from open sources. You need to identify patterns that determine whether a game is successful. This will allow you to spot promising projects and plan advertising campaigns.

You have access to data dating back to 2016. Let's imagine it is December 2016 and you are planning a campaign for 2017.

The dataset contains a "rating" column that stores the ESRB rating for each game. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating, such as Teen or Adult.

Instructions for completing the project

Step 1. Open the data file and examine the general information

File path:

/datasets/games.csv 

Step 2. Prepare the data

Replace the column names (convert them to lowercase).
Convert the data to the necessary types.
Describe the columns where data types were changed and explain why.
If necessary, decide how to handle missing values:
Explain why you filled in missing values ​​the way you did or why you chose to leave them blank.
Calculate total sales (the sum of sales across all regions) for each game and place these values ​​in a separate column.

Step 3. Analyze the data

Look at how many games were released in different years. Is the data for each period significant?
Observe how sales vary from one platform to another. Choose the platforms with the highest total sales and create a distribution based on the data for each year. Look for platforms that used to be popular but currently have no sales. How long does it generally take for new platforms to appear and old ones to disappear?
Determine which time period to use for your data. To do this, look at your answers to the previous questions. The data should allow you to build a model for 2017.
Work only with the data you consider relevant. Ignore data from earlier years.
Which platforms are sales leaders? Which ones are growing, and which are declining? Select several potentially profitable platforms.
Create a box plot for global sales of all games, broken down by platform. Are the differences in sales significant? What happens to average sales across various platforms? Describe your findings.
Examine how user and critic reviews affect sales for a popular platform (of your choice). Create a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
Based on your conclusions, compare the sales of the same games across other platforms.
Take a look at the general distribution of games by genre. What can be said about the most profitable genres? Can you make generalizations about genres with high versus low sales?

Step 4. Create a user profile for each region

For each region (NA, EU, JP), determine:
The top five platforms. Describe the variations in their market shares across regions.
The top five genres. Explain the differences.
Whether ESRB ratings affect sales in individual regions.

Step 5. Test the following hypotheses:

— Average user ratings for Xbox One and PC platforms are the same.
— Average user ratings for Action and Sports genres are different.
Set the alpha threshold value yourself.
Explain:
— How you formulated the null and alternative hypotheses.
— What criteria you used to test the hypotheses and why.

Step 6. Write a general conclusion

Format: Complete the task in a Jupyter Notebook. Insert programming code into code cells and text explanations into markdown cells. Apply formatting and add headings.
Data description
— ​​Name
— Platform
— Year_of_Release
— Genre
— NA_sales (sales in North America in millions of US dollars)
— EU_sales (sales in Europe in millions of US dollars)
— JP_sales (sales in Japan in millions of US dollars)
— Other_sales (sales in other countries in millions of US dollars)
— Critic_Score (maximum of 100)
— User_Score (maximum of 10)
— Rating (ESRB)
Data for 2016 may be incomplete.