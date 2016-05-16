# lanl-auth-cybersecurity

This is a data analysis of  a cybersecurity dataset from Los Alamos National Laboratory. The dataset and description of the dataset can be found at http://csr.lanl.gov/data/cyber1/ . 

Here I only worked with the file auth.txt.gz that represents authentication logs captured for the dataset. This file contains 8 columns of data and my goal was to use first seven columns to predict the values in the last column.

To accomplish this task, I used 64-bit linux computer with 8GB of RAM. 

Below I describe the steps I took for this analysis.

## First look

For speed and efficiency, I worked with auth.txt.gz directly. First I created a small subsample of the file just to get the feel for the data.
I created such file using bash commands:
```
zcat auth.txt.gz | cat -n | grep '00000    ' > sample2.csv
cat sample2.csv | cut -f 2 > sample2v.csv
```
After that I used jupyter notebook for my initial analysis that one can see in


## Trying machine learning

## Analysis