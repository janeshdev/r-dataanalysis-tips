r-dataanalysis-tips
===================

In this repository I will show you some basic tips that can be used to in daily life.   


Use `str` to any R object to find its structure. 

Check if two data frames are equal or not 
--------------------------------------
We can check if two data frames are equal or not using two functions. They are `all.equal` and `is.identical`. 

If two dataframes that are being compared are equal then both `all.equal` and `identical` functions return the same logical that is `TRUE`, however, if the two dataframes are not equal, then `all.equal` would should what are the things that are different while the function `identical` would simply return `FALSE`. 

