# The Fuel Economy Car Analysis

### Date created
February 4, 2020

### Description

From previous days to these days, automobiles have been necessity for American dream.

This project aims to analyze data of cars to gain clear insights from 2008 data and 2018 data.

The primary purpose of this project is to answer 3 questions :

Q: Are more unique models using alternative fuels in 2018 compared to 2008? By how much?

Q: What are the characteristics of SmartWay vehicles?

Q: For all of the models that were produced in 2008 that are still being produced now, how much has the mpg improved and which vehicle improved the most?

Thank you so much for reading this.


### Contents

cleansing_column_labels - Renamed the columns, dropped unncessary columns

drawing_conclusions - Answers questions with visualization.

exlporing_visuals - Uses histogram to visualize the variables

filter_drop_dedupe - Filters the region to CA, drops the NA values, and drops the duplicated values.

fix_datatypes_air_pollution - Rearrange the data in air_pollution_score by splitting '/' and changes the datatype into float.

fix_datatypes_cyl - Rearranges the cyl data by extracting integer values from string and convert datatype into integer.

fix_datatypes_mpg_greenhouse - Changes datatype of mpg values to float.

inspect_datatypes - See the datatypes of variables.

merging_data - Merges 2008 data with 2018 data

null_values_dedupe - drops NA values and checks whether there left na values and duplicate values

results_merged - creates new dataframe that groupby the models and cmb_mpg to find the most improved cmb_mpg vehicle.
