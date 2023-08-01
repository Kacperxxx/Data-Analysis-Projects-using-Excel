# Problem description

I have a dataset with information about used cars. I want to create a dashboard with charts and tables 
to extract information from the dataset.

# Dataset description

This dataset comes from the Kaggle and there is link to the dataset:

https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?select=UserCarData.csv


# What I did in this project:

1. Finding and deleting duplicates based on id column

2. Finding blank values in the dataset and deleting them if exist

3. Hiding columns: torque, mileage, engine

4. Adding currency to the price - $ sign

5. Removing leading and trailing spaces in columns: State or Province, City and Region

6. Calculating Age column and select older than 10 years as pink and select between 5 and 10 as blue

7. Adding color scales for selling_price column red - the highest, yellow - medium and green - lowest

8. Adding "Environmental rating" column and filling cells based on fuel type and FuelRating table but if there is value
   not defined in fuel in FuelRating write Unkown fuel and color cell to red

9. Creating FuelCount table with column fuel and total count to count the number of vehicles based on fuel

10. Creating MakesTable table with column make and total sales to calculate the sum of sales of vehicles of a given 
    brand whose sold status is as sold

11. Adding Count Sold, Count All and Sold to All columns in MakesTable and color scales to Sold to All column

12. Adding RegionFuelCount table to see how many vehicles are available with a given fuel type based on the selected
    region and total number of vehicles in  the region

# What I want to do in the future:

1. Create a dashboard with charts and tables

2. Create a pivot table with the following columns

3. Make some dynamic results

