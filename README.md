# Crimes_in_US
The FBI collects these data through the UCR Program’s NIBRS. This table provides the number of offenses distributed by offense type. 
This table counts offense types using the following rules: 
-	Offenses – if the offense type in Data Element 6 (UCR Offense Code) is: 
-	Crime Against Person: count one for each victim, i.e., Victim Segment. 
-	Crime Against Property: count one for each unique offense type. 
- Crime Against Society: count one for each unique offense type. 
- The data used in creating this table were from law enforcement agencies submitting 12 months of NIBRS data to the FBI UCR Program for 2012 and were converted and published in CIUS, 2012. Upon meeting both criteria, the agencies’ actual NIBRS submissions were used in this table.

Data cleaning & Exploratory Data Analysis: 							             

-	Top 5 states with highest number of Assault offenses registered in all the agency types except cities. (Show pivot of sub-types of Assault offenses) 
-	Which category of crimes were most registered in universities?
-	Compare offenses at Michigan State University with offenses at all other universities.
-	Which provinces have state agencies with lowest number of digital offenses registered (Credit Card/Automated Teller Machine Fraud, Wire Fraud)
-	Which category of agency type and their respective agency names have the highest number of offenses registered per million people? 
-	Geospatial visualization of the data showing the offence type with highest number of offences in that province.

Modelling task:
- Build a linear regression model that fits best to the above data. You can use feature engineering to derive new features from columns in X.
- Build a statistical model of your choice from data available predicting total number of offenses. 

