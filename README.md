# aid_water_conflict
Here is the code for my master thesis, titled "Aid, Water, and Peace: Assessing Foreign Assistance’s Impact on Conflict in Water-Stressed India - A Spatial Grid Analysis"

The structure is as following
- 01_masterthesis_rawdata.Rmd is the file where I organized and organized the necessary raw data for the study. The data of each countries in Asia are also downloaded for the study 
- 02_masterthesis_grid_datawork.Rmd is the file where I set up the foundation of study by arranging the suitable spatial unit for the study as well as manipulating all of the data. Finally a ready-to-be-regressed dataset is created for each country
- 03_masterthesis_data_regression.Rmd is where I run different regressions and export the result tables
- Master_thesis_Le Minh Hoang.pdf is my written thesis
- aid_water_conflict.Rproj is the project file to be run in R

The folder data-processed are the intermediary files that are exported from the manipulation of 02_masterthesis_grid_datawork
The folder data-r4r is all the final data that are ready to be used in the 03_masterthesis_data_regression.Rmd
In the my own work there is another folder which is called data-raw which are the raw data downloaded from the 01_masterthesis_rawdata.Rmd, this folder is not included because of its big size. 
