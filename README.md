![giphy](https://user-images.githubusercontent.com/110810531/188515931-f1d18440-c79f-4fe0-bd3a-eb259a6ed296.gif)


# Project_W4_Oktoberfest

This project is about the possible relation between the beer consumption, the terrorist attacks in Europe and the Weather as possible indicators that reduce the beer consuption. 


### Gathering information

Firstly I've got the Oktoberfest Dataframe from Kaggle with information providd directly from a public source from Munich government. 

Once I've that, I analysed which could be the reasons why the beer consumption was reduced some years. After carful consideration, I drive the conclusion that some external causes could influence the beer consumption. 

Therefore I've scrapped a weather web in order to get the registers of the weather yearly from 2000 until 2019. As I've noticed that there was not a clear relation between that information I've decided to scrapp another web with the information about terrosist attacks during the same period. 


### Data Cleaning
After I've got the 3 dataframes, I've started to clean them to get the correct information when forwarding the information into SQL.

· Firstly, I've imported the Oktoberfest csv and drop some unnecessary colums and rows.

· After checking the shape of the diferent DataFrames and the information includen in them, I've started to clean dirty columns. That means eliminating unnecesary columns or re-naming them in order to be easier to work with those.

· Lastly checking wich informaton was important to join in SQL as they have the same information.

· Onced I've finished with the "cleaning" part, I've imported certain libraries that helped me to migrate the information to sql and transforming the data worked in Jupyter Notebook into CSVs.

### SQL:

· At SQL, I've created the union between the different tables setting primary and foreign keys.

· Once the connection was clear I've created some queries


### Conclusions: 

· The Year that less attendants went to the Oktoberfest was 2001, the year that 3 important terrorist attacks happend. In Spain: "Atentado de Rosas" and in the US "Atentado a las torres gemelas". 
· Something courious is that during 2016 when the beer price was over 10€ was not the date that less daily attendants went and also was not the day that lees beer was consumed. 
· The year that more beer consumption was, matches the year that more daily attendants were (2016), however 2001 was the year with the highest roast chicken consume.



