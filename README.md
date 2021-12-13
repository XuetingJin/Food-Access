# Food-Access
Food Access During the COVID-19 Pandemic
Author: Daoqin Tong, Xueting Jin

Date Created: 11/23/2021

This notebook provides the code for running a Segmented Linear Regression Model to examine visits to grocery stores in six large metropolitan statistical areas (MSAs).

Defining variables:
  
   Visits_j,m: Total grocery store visits coming from block group j in month m
   
   AWDist_j,m: Average weighted travel distance from block group j to all the visited grocery stores in month m
   
   TripChain_B_j,m/TripChain_D_j,m: The visiting times of the visitors in block group j to both a POI and other brands on the same day in month m
   
   Fast_Visits j,m: Total fast food restaurant visits coming from block group j in month m
   
   OtherR_Visits j,m: Total restaurant visits expect fast food restaurant visits coming from block group j in month m
   
   Dist_Specialty_j: Distance from the population centroid of block group j to the nearest specialty food store.
   
   Dist_LargeRetailer_j: Distance from the population centroid of block group j to the nearest large retailer.
   
   Dist_Warehouse_j: Distance from the population centroid of block group j to the nearest warehouse club.
   
   Dist_Supermarket_j: Distance from the population centroid of block group j to the nearest supermarket.
   
   Dist_Convenience_j: Distance from the population centroid of block group j to the nearest convenience store.
   
   Population_j: Population in block group j
   
   PCT_17_j: Percentage of people who is 17 or less in block group j
   
   PCT_65_j: Percentage of people who is 65 or above in block group j
   
   PCT_race_j: Maximum of the percentage of Asian/Black/Hispanic people in block group j
   
   Income_j: Median household income in block group j
   
   No_Vehicle_B_j/No_Vehicle_D_j: Percentage of household without vehicle in block group j
   
   High_Educated_B_j/High_Educated_D_j: Percentage of people with bachelor or higher degree in block group j
   
   May: A dummy variable. 1 = in May; 0 = in April
   
   PCT_Case_a,m: Proportion of monthly cumulative confirmed cases in total population in MSA a in month m
   
   POP_Density_a:Population density in MSA a
   
   Commute_a: Average commuting time in MSA a
   
   PCT_Public_a: Percentage of people who use public transportation as their main commuting method in MSA a
   
   intD: A dummy variable. 1 = during COVID-19; 0 = before COVID-19
   
