# project-eda
Exploratory data analysis on a Google Playstore dataset with customer reviews 
1. The file cleaned_play_store and clean_user_reviews are the dataset which has underdone data cleaning and ready for data
visualization
2. Playstore&userReviewsCombined is a tableau workbook file that contains data visualization of both cleaned_play_store  and 
clean_user_reviews dataset combined


1.	Loading the first dataset ( Play Store  ).
2.	Looking at head, tail, shape, info, and descriptive statistics.
1.	Data preprocessing.
3.1 Conversion of identified Numerical columns to int or float from object datatype (Reviews, Size, Installs, Price needed preprocessing and typecasting to numerical)
4.	Data cleaning
	4.1 Handling missing values for Size Column.
	4.2 Handling missing values for Rating Column
	4.3 Handling missing values for Columns of Type, Android version, and Current version
	4.4 Removing Duplicates rows
      		4.4.1 By index
      		4.4.2 By App name
5.	Loading second Dataset (User Reviews)
6.	Looking at details of dataset like head, shape, tail, info, descriptive statistics
7.	Data Cleaning (Removing nan values)
8.	Handling outliers, visualization of First dataset (Play store ) outliers
	8.1 Handling Size outliers
	8.2 Handling Rating outliers
	8.3 Handling Reviews outliers
	8.4 Handling Price outliers
9.	EDA
	9.1 Play Store dataset
    		9.1.1 Correlation matrix with heatmap 
    		9.1.2 Category with the maximum number of apps
    		9.1.3 Top 10 apps that made the most profit (Paid Apps)
    		9.1.4 Common price range most of the apps have (Paid Apps)
    		9.1.5 Checking correlation between Price and Installs (Paid Apps)
    		9.1.6 Category with a maximum average of app purchases
    		9.1.7 Category having most of the paid apps
    		9.1.8 Category that has maximum Installs (Sum of all app installs under category)
    		9.1.9 Visualizing the average rating of category
    		9.1.10 Content Rating proportion (Pie Chart)
    		9.1.11 Check the Average Installs of app Content Rating wise (To check the age-wise usage of apps)
    		9.1.12 Check if customers feel the size of app a burden
    		9.1.13 Best rated and underrated apps based on Genres of apps vs mean of rating
    		9.1.14 Check if any trend recorded in Installs and Updates releases vs Months  
    		9.1.15 Visualize the size of the apps compared to genres
	9.2 Visualization of Second dataset User Reviews
     		9.2.1 Correlation matrix with heatmap
     		9.2.2 Proportion of apps having positive, negative, and neutral  feedback from customer
	9.3 Combining both the datasets
    		9.3.1 Data Cleaning
    		9.3.2 Top 10 apps with most positive feedback and negative feedback with a minimum of 100 feedback counts
10. 6 Sheets of Data Visualization of combined data in Tableau BI tool


Summary:
The conclusion got while performing EDA on Playstore with Customers reviews 
Are:
1.	From the correlation matrix of Playstore data Installs are positively correlated to Reviews with the value of 0.63
2.	Most of the apps belong to the family category dominating the android market
3.	Minecraft is one of the top 10 profitable apps making a profit of 69 Million
4.	Price of paid apps are expected to be in between the range 1 $to 6$,
5.	Price and Purchases have a negative correlation if Price increase Purchases decreases and vice versa
6.	Game is most Installed Category in terms of paid apps
7.	Game has the total number of (sum) Installs (Overall apps)  
8.	Content Rating of most the apps is related to EVERYONE for high exposure around 81%
9.	 Teenagers are using most of the apps, as Content Rating related to Teen has the highest average Installs compared to other
10.	Customers are not feeling the size of the app is a burden (up to 100 MB)
11.	Most of the last Updates of every year happen in July
12.	Apps Last updated in August have highest average Installs
13.	Only 64% of customers are happy about using the apps
14.	Apps related to the game category have maximum size compared to another category.




