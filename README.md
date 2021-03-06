Getting and Cleaning Data Course Project
========================================

The data set used as base information for this script is:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Data from train and test data sets was joined and tagged in order to generate a new data set will all information.

The values are an average of each mesure by each original variable, where x, y, and z defines a vector and "mean" is the mean value and "std" is the standard deviation:

tbodyacc_mean_x  
tbodyacc_mean_y  
tbodyacc_mean_z  
tbodyacc_std_x  
tbodyacc_std_y  
tbodyacc_std_z  
tgravityacc_mean_x  
tgravityacc_mean_y  
tgravityacc_mean_z  
tgravityacc_std_x  
tgravityacc_std_y  
tgravityacc_std_z  
tbodyaccjerk_mean_x  
tbodyaccjerk_mean_y  
tbodyaccjerk_mean_z  
tbodyaccjerk_std_x  
tbodyaccjerk_std_y  
tbodyaccjerk_std_z  
tbodygyro_mean_x  
tbodygyro_mean_y  
tbodygyro_mean_z  
tbodygyro_std_x  
tbodygyro_std_y  
tbodygyro_std_z  
tbodygyrojerk_mean_x  
tbodygyrojerk_mean_y  
tbodygyrojerk_mean_z  
tbodygyrojerk_std_x  
tbodygyrojerk_std_y  
tbodygyrojerk_std_z  
tbodyaccmag_mean  
tbodyaccmag_std  
tgravityaccmag_mean  
tgravityaccmag_std  
tbodyaccjerkmag_mean  
tbodyaccjerkmag_std  
tbodygyromag_mean  
tbodygyromag_std  
tbodygyrojerkmag_mean  
tbodygyrojerkmag_std  
fbodyacc_mean_x  
fbodyacc_mean_y  
fbodyacc_mean_z  
fbodyacc_std_x  
fbodyacc_std_y  
fbodyacc_std_z  
fbodyacc_meanfreq_x  
fbodyacc_meanfreq_y  
fbodyacc_meanfreq_z  
fbodyaccjerk_mean_x  
fbodyaccjerk_mean_y  
fbodyaccjerk_mean_z  
fbodyaccjerk_std_x  
fbodyaccjerk_std_y  
fbodyaccjerk_std_z  
fbodyaccjerk_meanfreq_x  
fbodyaccjerk_meanfreq_y  
fbodyaccjerk_meanfreq_z  
fbodygyro_mean_x  
fbodygyro_mean_y  
fbodygyro_mean_z  
fbodygyro_std_x  
fbodygyro_std_y  
fbodygyro_std_z  
fbodygyro_meanfreq_x  
fbodygyro_meanfreq_y  
fbodygyro_meanfreq_z  
fbodyaccmag_mean  
fbodyaccmag_std  
fbodyaccmag_meanfreq  
fbodybodyaccjerkmag_mean  
fbodybodyaccjerkmag_std  
fbodybodyaccjerkmag_meanfreq  
fbodybodygyromag_mean  
fbodybodygyromag_std  
fbodybodygyromag_meanfreq  
fbodybodygyrojerkmag_mean  
fbodybodygyrojerkmag_std  
fbodybodygyrojerkmag_meanfreq  
angletbodyaccmean_gravity  
angletbodyaccjerkmean_gravitymean  
angletbodygyromean_gravitymean  
angletbodygyrojerkmean_gravitymean  
anglex_gravitymean  
angley_gravitymean  
anglez_gravitymean  

This variables were extracted from original data set and formated for R processing. It was removed spaces, brackets, periods and dots from variable names.
