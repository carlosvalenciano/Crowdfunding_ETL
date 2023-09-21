# Class Project 2 - Crowdfunding_ETL

#### **Table of Contents:**
* [Prep Work](#prep-work)
* [Instructions](#instructions)
* [Create the Category and Subcategory DataFrames](#create-the-category-and-subcategory-dataframes)
* [Create the Campaign DataFrame](#create-the-campaign-dataframe)
* 


## **Background**

For the ETL mini project, we worked as a team of four to practice building an ETL pipeline using Python, Pandas, Python dictionary methods and regular expressions to extract and transform the data. After we transformed the data, we created four CSV files and used the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.

We made sure to divide the work, it was essential to collaborate and communicate while working on different parts of the project and checked in regularly and for support.

## **Prep Work**
1. One group member created a new repository and named it <code>Crowdfunding_ETL</code> and added the other team members as collaborators.
2. We each cloned the new repository to our computers.
3. We had one person rename the <code>ETL_Mini_Project_starter_code.ipynb</code> file with the first name initial and last name of each member of the group. Then, added this Jupyter notebook file and the Resources folder containing the <code>crowdfunding.xlsx</code> and the <code>contacts.xlsx</code> files to our repository and pushed the changes to GitHub.
4. Then, each team member pulled the changes, so all of us would have the same notebook available on our computer.
5. As we worked through the project deliverables, we broke up the work across other notebooks that each of us worked on individually. Once complete, we combined all the subsections back into the final ETL_Mini_Project notebook.

## **Instructions**

The instructions for this mini-project are divided into the following subsections:

* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database

## **Create the Category and Subcategory DataFrames**  

1. Extract and transform the <code>crowdfunding.xlsx</code> Excel data to create a category DataFrame that has the following columns:
   *  A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories
   *  A "category" column that contains only the category titles
   *  The following image shows this category DataFrame:

  ![Category DataFrame](Resources/images/category_DataFrame.png)

2. Export the category DataFrame as <code>category.csv</code> and save it to your GitHub repository.
3. Extract and transform the <code>crowdfunding.xlsx</code> Excel data to create a subcategory DataFrame that has the following columns:
   * A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories
   * A "subcategory" column that contains only the subcategory titles
   * The following image shows this subcategory DataFrame:

 ![SubCategory DataFrame](Resources/images/subcategory_DataFrame.png)

4. Export the subcategory DataFrame as <code>subcategory.csv</code> and save it to your GitHub repository.

## **Create the Campaign DataFrame**

1. Extract and transform the <code>crowdfunding.xlsx</code> Excel data to create a campaign DataFrame has the following columns:
   * The "cf_id" column
   * The "contact_id" column
   * The "company_name" column
   * The "blurb" column, renamed to "description"
   * The "goal" column, converted to the <code>float</code> data type
   * The "pledged" column, converted to the <code>float</code> data type
   * The "outcome" column
   * The "backers_count" column
   * The "country" column
   * The "currency" column
   * The "launched_at" column, renamed to "launch_date" and with the UTC times converted to the <code>datetime</code> format
   * The "deadline" column, renamed to "end_date" and with the UTC times converted to the <code>datetime</code> format
   * The "category_id" column, with unique identification numbers matching those in the "category_id" column of the category DataFrame
   * The "subcategory_id" column, with the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
   * The following image shows this campaign DataFrame:
  



































