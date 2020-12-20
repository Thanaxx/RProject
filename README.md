# RProject
Use the (built-in) dataset WorldPhones 

WorldPhones data set is the number of telephones in various regions of the world (in 	thousands).
1.	Analyzing the data Set

a.	Print out built-in R data frame of WorldPhones data set.
		> WorldPhones
    
The WorldPhones data set  was composed of 7 different years that was use to check the number of telephones for each 7 different regions of the world. 
b.	Display the summary of the data set.
	> summary(WorldPhones)
		 
	The summary of the WorldPhones data set shows the values for each column observations, and the results for all the columns are shown together. 

c.	Print out the header of each column using names(WorldPhones)
 
The names() returns the column headers for each observation.

d.	Use str() to show the structure of the data set. 
		> str(WorldPhones)

		 
		
	The str() displays the total number of observations in the data set that is equal to 7 different no. of telephone numbers for each region. The total number of variables  are 7 which is the year which the total number of telephones are being counted 
		
e.	Display the number of rows and columns using dim()
	 
	The dim() obtains the dimensions of the data frame which are the number of its rows and columns.
 
