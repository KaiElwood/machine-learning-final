# Machine Learning for Cities Final Project

The purpose of this repository is to keep all materials used in developing the class project for Machine Learning for Cities course

The Project Team:
* Danielle Bayer
* Kai Elwood-Dieu
* Jennah Gosciak
* Ariadne Rivera

The problem:

The objective: Use machine learning techniques to identify buildings at risk of fires.

The order to run the scripts is

### a) Data preparation

1. [Calculate catchment area for the proportion of census tract each alarm box serves](code/00a_calculate_catchment.ipynb)
2. [Process building data PLUTO](code/00b_data_processing.ipynb)
3. [Clean census data at the census tract level](code/00c_census2009_2019_data_processing.ipynb)
4. [Clean building HPD/DOB violations](code/00d_HPD_DOB_violations_data_processing.ipynb)

## b) Create analyitic files

1. [Building level dataset](code/01_merge_bbl.ipynb)
2. Alarm box level dataset has two steps
    * [Merge boxes fire and census tract data](code/merge_boxes_boroughs.ipynb.ipynb)
This code merges census tract data at the fire alarm box level, based on the weights for the proportion of census tract each.

    * [Fire alarm box level dataset](code/02_merge_box.ipynb.ipynb.ipynb)
This code merges fire alarm box with census tract data with other databases.

## c) Analysis Building Level
1. [Random forest](code/03a_rf_bayesnet_bbl.ipynb)
2. [Bayes Net](code/03a_rf_bayesnet_bbl.ipynb)
3. [Cluster analysis]
4. [SVM]
5. [Naive bayes](code/03b_naivebayes_gp_bbl.ipynb)
6. [Gaussian processes](code/03b_naivebayes_gp_bbl.ipynb)

## 2) Analysis Alarm Box Level
1. [Random forest](code/04a_rf_bayesnet_box.ipynb)
2. [Bayes Net](code/04a_rf_bayesnet_box.ipynb)
3. [Cluster analysis]
4. [SVM]
5. [Naive bayes](code/04b_naivebayes_gp_bbl.ipynb)
6. [Gaussian processes](code/04b_naivebayes_gp_bbl.ipynb)
