# Consumer Behaviour - Sales Analyis Dashboard

Data cleaning on sales date completed using Python Jupyter notebook

## Table of Contents

- Introduction
- Technologies used
- Wireframes and user stories
- Images
- Development process and data cleaning and transformation
- Unsolved problems

## Introduction

I was presented with 10 years of sales data that I had to clean and concatenate into one big data frame. This cleaned data then needed to be analysed and turned into a dashboard where the end user could vizualise the data.

## Technologies used

In order to clean the data and run any analysis to ensure everything was working as it should. The following technologies and libraries were used:
Visual Studio Code
Python
Jupyter notebook
Github
os
numpy
pandas
petl

## Wireframes and user stories

User Storiees:
drop downs: As a user I want to be able to select from a range of criteria so that I can see the exact data I require

As a user I want to be able to vizualise the data in a easily digestible manner so that I can understand the data

As a user I want to be able to click on a button that will display the data I have requested.

## Development process and data cleaning and transformation

1st I made rough notes outlining what it was that I needed to do.

I then proceeded to start with the cleaning of the date using Jupyter notebook.
I installed numpy, pandas and petl then imported them as np, pd and etl respectively

I then imported one file at a time to work on and started the clean up operation using the loop which goes through each file one by one to clean it up.

I decided to use the petl library to perform the analysis on my data so as to prevent me having to change the data back and forth between pandas and pets as this was time consuming. I did however import and use pandas for analysis.

I didn’t check for Nan’s because the data was collected by non-technical people and therefore we can assume that they wouldn’t have inputed this in any field.

I used the isnumeric() method to check the numeric columns for input that is not a number so they can be removed. The two columns that didn’t have data were quantity_purchased and amount_in_gap. With each operation I ran the function etl.nrows() to count the number of rows to see if there were rows removed due to the selected column having fields that were invalid.

I then concatenated all the files to form one table that could be used for analysis

Wireframe: https://lucid.app/lucidchart/dd2ddaab-b740-4fa0-847d-6d41a78d98d4/edit?invitationId=inv_951c5199-ecab-48bf-9453-e35bc8a46f9a

## Unsolved problems

A major issue faced was arround the size of the files and the amount of data included. It was preventing me from uploading to Github. So the data had to be massively compressed and reduced to work around this.

One of the graph also needs looking into as it is not working exactly as it should
