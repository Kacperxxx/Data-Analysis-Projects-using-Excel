# Problem description

I have a dataset with information about cars. I want to create a dashboard with charts, tables and summary to 
extract information from the dataset about specific makes and models.

# Dataset description

This dataset comes from the Kaggle and there is link to the dataset:

https://www.kaggle.com/datasets/rakkesharv/used-cars-detailed-dataset?select=FINAL_SPINNY_900.csv

# What I did in this project:

1. Added Age column which is calculated based on the Make_Year column and added data bars to the Age column

2. Added color scales and currency sign to the Price column

3. Added background color to the Mileage_Run column:
    * green - less than 10000
    * pink - between 50000 and 85000
    * brown - more than 90000
   
4. Calculated l/100km column based on Mileage(kmpl) which had some text values and changed them to 0 and then replaced
    0 with average mileage for the rest of the values different from 0.

5. Added Fuel Rating column where values are added based on the Fuel_Type column and FuelRatinTable table but 
    if there is value  not defined in fuel in FuelRatingTable write 'no rating'.

6. In BodyType by FuelType sheet I created a range of cells with body types for selected fuel type and then created a 
    dynamic pie chart with body types for selected fuel type.

7.  In Transmission Type Pivot Table I created Pivot Table with Year in rows, Transmission Type in columns and 
    Count of Transmission Type in values and then created a dynamic chart with this Pivot Table.

8. In Make and Model choice sheet I created drop down list for Make and drop down dependent list for Model based on 
    selected Make. Then I created short summary with Make, Model, Total Count, Most Common Transmission Type, Most Common
    Transmission, Most Common Seating Capacity and Average Price.

9. In Average Make Price sheet I created a Pivot Table with Year in rows, Make in columns and Average Price in values
    and then created a dynamic chart with this Pivot Table where we can see average price for selected make and year 
   and thanks to slicers we can select specific year and make to quickly compare average price for selected make. 
    So we don't need to filter data in the table.


# Summary

Based on created dashboard we can see that no matter which year of production we choose, manual transmission is more 
popular than automatic transmission. We can also see that the most popular Body Type is hatchback and unfortunately
there is too many cars with diesel as fuel type, which is the most harmful to the environment.