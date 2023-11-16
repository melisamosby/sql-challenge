# sql-challenge
Data Modeling:
Upon inspection of the CSV files, I noticed that in the employees and titles files that the title id columns were names slightly different. I made note of this because it might cause issues during the modeling steps.
Next, I created a schemata in QuickDBD and exported it to pgAdmin.

Data Engineering:
I created the tables from the codes that were generated from the QuickDBD.
I also ran the foreign key constraints.
Then I got errors involving column attributes.
Before I could correct the errors, I needed to drop the tables. 
While dropping the tables, I had to drop them in a certain order based on the constraints.
I enetered the drop table codes at the top of the queries.
Finally, the tables and foreign keys loaded.
I imported the csv tables and used SELECT * FROM to show that the data imported corrected.

Data Analysis:
I proceeded to follow the instructions for each question. I ran into an error when doing the frequency counts, but I met with a tutor and I figured it out.
I saved my assignment into several files: the schemata, the whole challenge in 1 SQL file, then 1 SQL file for data engineering and 8 SQL files for the 8 questions and 8 results.csv files related to the 8 questions.
