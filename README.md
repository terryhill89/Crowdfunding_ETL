# Crowdfunding_ETL
For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track.

Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support.
___________________________________________________________________________________________________________________
## Instructions
The instructions for this mini project are divided into the following subsections:

 * Create the Category and Subcategory DataFrames
 * Create the Campaign DataFrame
 * Create the Contacts DataFrame
 * Create the Crowdfunding Database

Create the Category and Subcategory DataFrames
1. Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame that has the following columns:

 * A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of   unique categories

 * A "category" column that contains only the category titles
 
 * The following image shows this subcategory DataFrame:

<img width="250" alt="subcategory_DataFrame" src="https://user-images.githubusercontent.com/112741203/224893854-83165880-9bc3-47b7-b192-ca837cf84366.png">

4. Export the subcategory DataFrame as subcategory.csv and save it to your GitHub repository.

## Create the Campaign DataFrame
1. Extract and transform the crowdfunding.xlsx Excel data to create a campaign DataFrame has the following columns:

* The "cf_id" column

* The "contact_id" column

* The "company_name" column

* The "blurb" column, renamed to "description"

* The "goal" column, converted to the float data type

* The "pledged" column, converted to the float data type

* The "outcome" column

* The "backers_count" column

* The "country" column

* The "currency" column

* The "launched_at" column, renamed to "launch_date" and with the UTC times converted to the datetime format

* The "deadline" column, renamed to "end_date" and with the UTC times converted to the datetime format

* The "category_id" column, with unique identification numbers matching those in the "category_id" column of the category DataFrame

* The "subcategory_id" column, with the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame

* The following image shows this campaign DataFrame:
 

