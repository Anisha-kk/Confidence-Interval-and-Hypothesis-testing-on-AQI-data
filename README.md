# Confidence-Interval and Hypothesis Testing on AQI Data
## Overview
This activity uses air quality index (AQI) data from the United States Environmental Protection Agency (EPA). Using Confidence intervals and hypothesis testing, this data is explored. 
1. In the confidence interval code,it is found from analysis of California AQI's that "given the observed sample AQI measurements, there is a 95% confidence that the population mean AQI for California was between 10.36 and 13.88. This range is notably greater than 10."
2. In the hypothesis testing code,  identified at the 5% significance level that the Los Angeles mean AQI was stastitically different from the rest of California, and that New York does have a lower mean AQI than Ohio. 
## Data Understanding
The Air Quality Index (AQI) is the Environmental Protection Agency's index for reporting air quality. A value close to 0 signals little to no public health concern, while higher values are associated with increased risk to public health. The United States is considering a new federal policy that would create a subsidy for renewable energy in states observing an average AQI of 10 or above. The data was taken from the EPA's own repository of AQI data and assembled for pedagogical purposes. This activity uses a dataset called c4_epa_air_quality.csv. The variables in the dataset have been adjusted to suit the objectives of this lab, and may vary from other versions of the dataset you have worked with previously. It contains air quality readings for various counties in the United States. The dataset contains: 260 rows – each row is a different aqi reading; and 10 columns
## Modeling and Evaluation
1. Confidence Interval code:  confidence interval at the 95% level of confidence from California data yielded [10.36 , 13.88]
2. Hypothesis testing code:  Even with small sample sizes, the variation within the data is enough to allow you to make statistically significant conclusions. You identified at the 5% significance level that the Los Angeles mean AQI was stastitically different from the rest of California, and that New York does have a lower mean AQI than Ohio. However, you were unable to conclude at the 5% significance level that Michigan's mean AQI was greater than 10.
## Conclusion
The 2 codes in this repository explores the different aspects of performing Hypothesis testing and computing Confidence Interval.
