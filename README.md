# Introduction [Data Set](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016)
I found this data set in Kaggle and given my experience with volunteering for a hotline, I was interested in how suicide rates differ across different demographics and time. I believe suicide is a complex topic that can't be understood from just a dataset, therefore, I will only be exploring how suicide rates differ between different age groups, sexes, and countries instead of looking for correlations. As well as examine how the rates have changed over the past few years for various countries. I will not be looking at the "HDI for year" column as almost 2/3 of the data is missing, and I will be exploring the GDP column as I don't aim to find correlations.  I also believe that there is an issue with the "generation" column of the data and it was appended after the data was processed using the age and year group, which creates artificial spikes, I only found this out after creating a few graphs so I removed all the graphs including this column. 



## 1 

![Alt text](plots/Total-Suicides-by-Country.png)<!-- -->


### Analysis 

We can see from the map that there are a lot of countries that have missing data, this could be due to lack of reporting or inaccessible data. This is especially true for Africa and Asia where the majority of countries are missing data. This makes a continent-by-continent comparison inaccurate. Furthermore, Russia has by far the highest number of suicides relative to the population, followed by East European countries. With the expectation of a few countries, the overall number of suicides is around 5k-7k for most countries. 



## 2 

![](Assignment_files/figure-html/unnamed-chunk-4-1.png)<!-- -->

### Analysis 

It is evident from the graph that the highest suicide number belongs to the "35-54 years" age group. We can see that "55-74 years" is the second highest, followed by the "25-34 years" group at the third highest. Surprisingly there are fewer suicides in the "75+ years" age group than almost any other group with the "5-15 years" group being the only group lower. A high disparity between the sexes can also be observed, with the highest disparity in the "35-54 years" group and the lowest disparity in the "75+ years" group. 



## 2 


![](Assignment_files/figure-html/unnamed-chunk-6-1.png)<!-- -->

### Analysis 

We can see the number of suicides skyrocketed between 1988 and 1996. Afterward, the graph increased ever so slightly, reaching its peak between 1998 and 2003. After this, it decreased steadily reaching it's 20-year minimum in 2015. However, we cannot generalize this trend to the following years. Moreover, the spike in 1988 might be due to underreporting in the earlier years.



## 3 


![](Assignment_files/figure-html/unnamed-chunk-8-1.png)<!-- -->

### Analysis 

The graph reveals that all the age groups have seen an increasing trend starting in 1989 and peaking at around 2003. This follows our global trend. Fortunately, There has been a steady decrease in the numbers since. Moreover, we can also observe that by far the greatest increase was in the "35-54 years" group followed by the "55-74 years" group and the "25-34 group" in that order. Interestingly there has been almost no change to the "5-14 years" age group.



## 4 


![](Assignment_files/figure-html/unnamed-chunk-10-1.png)<!-- -->

### Analysis 

We can see that the majority of the suicides between 1985-2015 have been men at around 70%.Let's explore this proportion throughout the years and in different countries. 



## 5 


![](Assignment_files/figure-html/unnamed-chunk-12-1.png)<!-- -->

### Analysis 

We can see that Men have always had a higher rate than women throughout the years. Also interestingly, Women's suicide numbers have remained roughly the same only fluctuating slightly, whereas men's numbers have changed drastically throughout, experiencing a spike in 1988, a peak in 2003, and a 20-year-old minimum in 2015. 




## 6 


![](Assignment_files/figure-html/unnamed-chunk-14-1.png)<!-- -->

### Analysis 
Some countries had missing values for this comparison, so this might not be the most accurate comparison, however, it is very interesting to see such a high degree of discrepancy between the proportions. The Men's suicide numbers go as low as 60%-70% for some countries. Interestingly most of these countries are also from east and southeast Asia, however, not exclusively with Albania and Netherlands having the 3rd and 4th proportions for men respectively. 



## 7 


![](Assignment_files/figure-html/unnamed-chunk-16-1.png)<!-- -->


### Analysis

We can also see that even though the overall trend of suicide numbers is decreasing not all countries follow this trend. We can see that the top 10 increase rates are of higher magnitude than the top 10 decrease rates. However, the worldwide decreasing trend would suggest that these countries are outliers or at least not the majority. However, exploring the reason behind these increases could be insightful. 
