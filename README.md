# World-Economic-Dataset

## Problem Statement :
The dataset ( World Economic Indicator), which has different countries' and regions' GDPs, populations, and other factors that might impact GDP/Capita. Now using Data Analysis methods, we have to develop a solution that can be referred to as “How a country can attain sustainable growth“.

## Dataset : [World Economic Indicator](https://docs.google.com/spreadsheets/d/1JKS-C_gXbFWzj-RreMZ1p92t4mjGoDhf49vQhuYpMlI/edit#gid=1984831915)


## Steps that I followed :

## Formating 
1: Rearranged the columns in all sheets where I bring all the common columns as the first three columns of the individual sheet.
2: Then performed formatting on each sheet to make it presentable and understandable.

## Data Processing Steps :
1.	Concatenate country region with year to make one lookup value for VLOOK UP Operation.
2.	Merge all the sheets using VLOOKUP function as country region with year column as lookup value.
3.	Empty all the cell values where you get N/A after VLOOKUP so that we know that other sheets are not having that value and we can analyze data accordingly to handle missing values. 
4.	While analyzing the data, I found that following countries have very less data/ no data available. So it is better to remove these rows. In total I deleted 401 rows as they will lead distraction in the data. One major reason is they have all the 12 years data blank. Even if we fill them with mean/ median, all the years will show same result. Hence, no effect on the data. 
(a)	American Samoa-Oceania
(b)	Cayman Islands-The Americas
(c)	Curacao-The Americas
(d)	Faeroe Islands-Europe
(e)	Greenland-The Americas
(f)	Guam-Oceania
(g)	Isle of Man-Europe
(h)	Sint Maarten (Dutch part)-The Americas
(i)	St. Martin (French part)-The Americas
(j)	Turks and Caicos Islands-The Americas
5.	Now handle missing values of all the columns using standard deviation method. 
6.	Use engineering features to add required columns to the data based on the data available.

## Data Analysis 
Find individual features and study their distribution in the dataset. Further, analyse how they impact the GDP column (like how Lending Interest affects GDP ) and
develop factors that affect a country's GDP.
Performed Uni Variate and Bi Variate Analysis due to which I was able to find the Factors that are Affecting GDP :
A) Health Sector
B) Lending Interest rate
C) Population and Birth rate
D) Energy Usage
E) Tourism Sector
F) Business and technology sector 

## Therefore A Country can attain Sustainable Growth by Foccusing on these Factors.
