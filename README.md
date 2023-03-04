# BigDataETL

## Background

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. They are quite large and can exceed the capacity of local machines. One dataset alone contains over 1.5 million rows; with over 40 datasets, data analysis can be very demanding on the average local computer. Your first goal will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

This Challenge contains two parts. Part 1 is required. Part 2 is optional but highly recommended to strengthen your new skills.

Part 1: Extract two Amazon customer review datasets, transform each dataset into four DataFrames, and load the DataFrames into an RDS instance.
Part 2: Extract two Amazon customer review datasets and use either SQL or PySpark to analyze whether reviews from Amazon's Vine program are trustworthy.
Before You Begin
Create a new repository for this project called "Big-Data-ETL". Do not add this homework to an existing repository.
Clone the new repository to your computer.
Inside your local Git repository, create two folders, "part-1" and "part-2", corresponding to the two parts. If you are not planning on doing "part-2" then create the "part-1" folder only.
Files


## Methods
Part 1
Upload the part_one_starter_code.ipynb into Google Colab and create a duplicate of this file.
Explore the Amazon ReviewsLinks to an external site. datasets and pick two datasets to perform ETL.
Rename each part_one_starter_code.ipynb file according to the dataset you are using. For example, if you are going to use the Video Game reviewsLinks to an external site. file, rename file, part_one_video_games.ipynb. Repeat the process for the duplicate file you created in Step 2.
