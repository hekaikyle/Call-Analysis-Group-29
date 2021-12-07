# Call-Analysis-Group-29

## Introduction:

The project is an Analysis on calls to 311 in New York City to show:

1. top 10 incident types of 10025 area

2. whether illegal parking incidents are a larger fraction of total 311 incidents in 10025 area than they are in general

## Zip code chosen: 10025 , NYC

## Group name: group 29

## Section: 001

## Name and UNI

Kai He, UNI kh3069

Abhirat Shinde, UNI aas2357

## Project Description

### Top10.ipynb
1. Read the data from the csv file
2. Shortlist data belonging to Zip 10025.0, year 2020
3. Review columns to choose only the relevant columns, ie. 'Complaint Type' column. 
4. Group complaints and sort them in descending order based on their frequency of occurance in a series object type
5. Shortlist the Top 10 such complaints by frequency and assign them to a new object of dataseries type
6. Test the series object whose index is a string of the 'Complaint Type' column and respective values are frequency of occurance

### Parking.ipynb

1. Read data from the csv file
2. Confirm there're no missing data in 'Unique Key' and 'Complaint Type' column, and confirm that the data only include calls in 2020
3. Filter the original df to only include illegal parking calls in 2020
4. Compute number of total incidents and number of illegal parking incidents, in whole NYC and in 10025 area, respectively, by counting the unique keys of each incident
5. Compute illegal parking fractions, both in general NYC and 10025 area, and compare them
