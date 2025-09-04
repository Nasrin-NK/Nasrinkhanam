load("d_HHP2020_24.RData")

d_HHP2020_24[1:20,1:6]

attach(d_HHP2020_24)

summary(d_HHP2020_24)

summary(Age[Gender == "female"])

summary(Age[Gender == "male"])

summary(Age[Gender == "trans"])

summary(Age[Gender == "other"])

mean(Age[Gender == "female"])

sd(Age[Gender == "female"])

mean(Age[Gender == "male"])

sd(Age[Gender == "male"])

> summary(Age[Gender == "female"])
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  17.00   39.00   52.00   51.62   64.00   88.00 
> 
> summary(Age[Gender == "male"])
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  17.00   40.00   54.00   53.29   67.00   88.00 
> 
> summary(Age[Gender == "trans"])
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  17.00   26.00   31.00   36.02   41.00   88.00 
> 
> summary(Age[Gender == "other"])
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  17.00   31.00   43.00   45.88   59.00   88.00 
> 
> mean(Age[Gender == "female"])
[1] 51.61668
> 
> sd(Age[Gender == "female"])
[1] 15.59165
> 
> mean(Age[Gender == "male"])
[1] 53.28593
> 
> sd(Age[Gender == "male"])
[1] 16.28551
> 
> ##Something interesting about this data is that average ages for both men and women are in their early 50s with similar standard deviations, with men being slightly higher than womens. For trans the average age comes out to much lower at around 36, and all others average out higher to 45.
> 
> ##Questions about household pulse data
> ##Why might some states report higher in anxious and worry compared to others? What might cause these geographic differences in results?
> ##What is the distribution of household sizes, and how do the smaller ones compare to larger ones?
> 



