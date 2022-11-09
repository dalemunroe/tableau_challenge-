# tableau_challenge-

## Findings

-> Popularity increased on the weekends during the Covid pandemic and this trend is continuing.
-> The Corner of West St and Chambers is the most popular start and end station over a 5 year period.
-> Usage dropped by 40% in 2020 (Covid 19) 



## Process

|__ 5x files were downloaded from the citibike website.
|   |__201805-citibike-tripdata.csv  338,6661KB
|   |__201905-citibike-tripdata.csv  358,407 KB
|   |__202005-citibike-tripdata.csv  277,035 KB
|   |__202105-citibike-tripdata.csv  481,994 KB
|   |__202205-citibike-tripdata.csv  541,795 KB

## ELT Process

These *.csv files were then loaded into Pandas datafranes using "ConCat_Data_v1.ipynb"
    -> The files were interigted and it was found that the data recored changed format in 2021.
    -> New columns like bike type were added, and columns like age and sex were dropped.
    -> The data was run through an ELT process to format the columns, headings and data formats correctly.
    -> A 10% random sample was taken from each *.csv file and then concatenated into a single file "cleaned_combined_data.csv"
    -> The final combined cleaned file was reduced to 169,847 KB after a 10% sample.

## Tableau

THe file "cleaned_combined_data.csv" was loaded in as the dataset.
|__ The visualization contains
|   |__2x Dashboards
|   |__1x Storybook
|   |__3x Maps in which 1x is interactive by year.
|   |__8x Visulaisations consiting of bargraphs and heatmaps


![chart](https://github.com/dalemunroe/tableau_challenge-/images/tabpublic_nbQjWYt6qC.png)

