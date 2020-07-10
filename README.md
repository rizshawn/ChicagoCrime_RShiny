This project is focused on visualizing crimes data for for the city of Chicago via an R Shiny web application. The Shiny applicaton can be found at the following link:

[Chicago Crime RShiny](https://rizshawn.shinyapps.io/ChicagoCrime_Rshiny/)

The data used is from [a Chicago crime dataset from Kaggle](https://www.kaggle.com/currie32/crimes-in-chicago/data). The data spans the years 2012 to 2017 and includes the following information:

- Date & time of when the crime was committed 
- Exact block where the crime was committed 
- Type of crime
- If an arrest occured 
- Location coordinates 

Due to size of the dataset and ShinyApps.io server limitations the data had to be limited to the years 2014 to 2016.

The dashboard consists of three different tabs you can click on teh sidebar:

1. Heatmap
	- A map of Chicago that visualizes density of crime in 	 		  different areas filtering by charge (misdemanor or 		  	  felony), location, and year range 

2. Cluster Map
	- Helps visualize crime by showing crime counts clustered by 	  area. The user can zoom into a specific location/pin and 	  	  is able to see the crime type, date of crime, whether an 	 	  arrest was made, and the type of location. 

3. Time
	- This tab consists of various analyses over time

4. Data 
	- Contains the full dataset 

Please see the `Visualizations` folder for snapshots of the dashboard. 




