# calcofi_hackathon
A page where my code for the hackathon is posted

Quick summary:
The excel dataset I was working on was already cleaned and formatted by Charlene, who did things such as pivot the tables and clean up the dataset. I manually combined the datasets through excel and then worked on changing the column names for the species from there. 

In my first try, I was able to format a dictionary through python, which takes input and returns whatever value is associated with it. In this case, I set up species codes and names in the dictionary so that writing in a code would output the names of the species. Using this, I then worked on using this to change the column names in the datasets, so that we would have the actual names rather than just a bunch of numbers as the column titles. 

In my second attempt, I noticed that some of the sheets had very different column names and couldn’t be combined nicely, and worked on removing any outliers, such as column names with only a species number and no associated name, or column names not found in all the excel sheets.

After everything was formatted correctly, and each year had the exact same column headers, I then manually combined all the datasets into one big sheet, so that there could be a complete guide of phytoplankton catches from 1996 to 2018. 
