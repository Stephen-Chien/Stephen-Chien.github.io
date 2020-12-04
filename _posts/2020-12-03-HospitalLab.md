---
layout: post
title: Hospital Lab
subtitle: Third Lab
tags: [ArtofData]
comments: true
---


## County

The county that has the most hospital beds per person is **New York County**

## Obtaining and Cleaning Dataset

The first step for this Lab was obtaining the Dataset, which I used by creating a method that took each id(row) and printed it. A resource that I used often was the Web Api Worksheet and the Weather Api that we worked on in class. For the method itself, the payload consisted of the API Key and the id, which was then used as a parameter for what data we wanted (in this case, the rows). In order to continue having the program iterate through the different rows, I used a while loop that took in a boolean, and when the method returned false, the program would stop. 

To clean the dataset, I had to standarize the bed measures. I first read in the .csv file and used a for loop to recognize if the measure was 500 HAB (beds for 500 people), 1000 HAB, or 2000HAB. Then, for the measures that were 500HAB or 1000HAB, I multiplied them by 4 or 2, respectively, in order to make it equal to 2000HAB. From there, I printed out each individual row of the uncleaned .csv file,and made a new csv file for all of the code. 

## Process

As always, I like to try and divide up my thought process. For this lab, the main focus I had was on **analyzing** the data, because I knew the general method of obtaining and cleaning the data. I wrote down all my thoughts without coding in a file ![File](/assets/img/thoughtpng). For the analysis part of the code, I didn't want to hard-code it like I did in the Iris Lab, so I used a method called get_max that goes through each row and keeps track of the current max, and updates the max if needed. I then used a csv reader in order to read the rows, and then appended those values to a separate dictionary to add all the values by county. 

I think that carefully reading the prompt one more time could have saved a lot of time and anxiety, as I thought that we needed to find the id, not that the id is used to find the rows. I learned a lot from this lab, including how to obtain data using an API and using methods to analyze data. I think that there could have been a smarter way to clean the data, but I didn't figure that out in a short time. 

