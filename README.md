# Metaverse-City-Testbed

Metaverse program:
Input (test data):
•	Time/date of crimes
•	Location of crimes (neighbourhood and point in neighbourhood)
•	Severity of crimes (1-5)
•	Population density of areas
•	neighbourhoods

Processing: 
•	Frequency(per month) = amount of crime in 24h * 28
•	Heat of location = frequency*severity/population density
•	Points of risk based on location heat and frequency of the heat value
•	Split neighbourhoods into 100m^2 portions

Output:
•	A heat map of most frequent crime spots
•	Predictions on where a crime will take place in the future and at what approximate time
