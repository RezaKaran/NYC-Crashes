# Preprocessing NYC-Motor-Vehicle-Crashes


![Analysis](https://images.nycgo.com/image/fetch/q_70,w_900/https://www.nycgo.com/images/uploads/NY_in_3_days/TimeSquare-Manhattan-NYC-BrittanyPetronella_0069sat.jpg)


## About
There is a dataset of 100000 records of car crashes in New York that should be cleaned and modified to be ready for the later manipulations.



## First things first : Get to know the dataset

I observed the dataset as much as possible. I got information of datatypes,number of columns,rows,unique values,duplicated values,null values,index and so on. You can run this call functions on the project to see the results. 

| # Information().df_head(df)

| # Information().analyse_df_describe(df)

| # Information().analyse_df_columns(df)

| # Information().analyse_df_info(df)

| # Information().analyse_df_index(df)

| # Information().analyse_df_null(df)

| # Information().analyse_df_duplicated(df)

| # Information().analyse_df_datatype(df)

| # Information().analyse_df_uniquevalues(df)

## Second step: Clean the data
In this step I have cleaned the dataset. You can apply these functions on the project for each edit 

| # df=Cleaning().remove_strip(df)

| # Cleaning().rename_name_of_columns(df)

| # Cleaning().fill_null_values(df)

| # df=Cleaning(). need_investigation(df)

| # Cleaning().replace_texts(df)

| # Cleaning().changing_datatypes(df)

## Third step: Preprocessing

In this step we make the data frame ready for machine learning

| # df=Preprocessing().feature_selection(df)

| # df=Preprocessing().feature_slicing(df)

| # df=Preprocessing().feature_engineering(df)

| # df_normalized=Preprocessing().new_df_normalization(df)

| # Preprocessing().resampling(df)

## Final step: Now it is time to save our new dataset in a csv file

| # df.to_csv("Clean_database_NYC.csv")

## Why
Make the dataset more productive to get information afterwards. Moreover it will be ready for machin learning and future manipulation.

## When

I have started this project on Wednesday afternoon and the deadline is two days

## Usage

To install this project, you need to have Python3 and Pandas package
 
Afterwards, you can download the clean database 'Clean_database_NYC.csv' that is ready to use.


  
 This project will clean errors, NaN value etc...So afterwards we will have a new dataset.
 
 ## Objective 
My objective is to clean and make the database in a way to be easier for the next level of getting information from it.

