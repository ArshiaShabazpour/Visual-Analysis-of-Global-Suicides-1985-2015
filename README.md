# Introduction [Data Set](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016)
I found this data set in Kaggle and given my experience with volunteering for a hotline, I was interested in how suicide rates differ across different demographics and time. I believe suicide is a complex topic that can't be understood from just a dataset, therefore, I will only be exploring how suicide rates differ between different age groups, sexes, and countries instead of looking for correlations. As well as examine how the rates have changed over the past few years for various countries. I will not be looking at the "HDI for year" column as almost 2/3 of the data is missing, and I will be exploring the GDP column as I don't aim to find correlations.  I also believe that there is an issue with the "generation" column of the data and it was appended after the data was processed using the age and year group, which creates artificial spikes, I only found this out after creating a few graphs so I removed all the graphs including this column. 

## 1 

![Total Suicides by Country](plots/Total%20Suicides%20by%20Country.png)

### Analysis 

We can see from the map that there are a lot of countries that have missing data, this could be due to lack of reporting or inaccessible data. This is especially true for Africa and Asia where the majority of countries are missing data. This makes a continent-by-continent comparison inaccurate. Furthermore, Russia has by far the highest number of suicides relative to the population, followed by East European countries. With the exception of a few countries, the overall number of suicides is around 5k–7k per 100k people for most countries.

## 2 

![Total Suicides by Age Group](plots/Total%20Suicides%20by%20Age%20Group.png)

### Analysis 

It is evident from the graph that the highest suicide number belongs to the "35-54 years" age group. We can see that "55-74 years" is the second highest, followed by the "25-34 years" group as the third highest. Surprisingly there are fewer suicides in the "75+ years" age group than almost any other group with the "5-14 years" group being the only group lower. A high disparity between the sexes can also be observed, with the highest disparity in the "35-54 years" group and the lowest disparity in the "75+ years" group.

## 3

![Global Suicides (per 100k)](plots/Global%20Suicides%20(per%20100k).png)

### Analysis 

We can see the number of suicides skyrocketed between 1988 and 1996. Afterward, the graph increased ever so slightly, reaching its peak between 1998 and 2003. After this, it decreased steadily reaching its 20-year minimum in 2015. However, we cannot generalize this trend to the following years. Moreover, the spike in 1988 might be due to underreporting in the earlier years.

## 4

![Global Suicides (per 100k) by Age Group](plots/Global%20Suicides%20(per%20100k)%20by%20Age%20Group.png)

### Analysis 

The graph reveals that all the age groups have seen an increasing trend starting in 1989 and peaking around 2003. This follows our global trend. Fortunately, there has been a steady decrease in the numbers since. Moreover, we can also observe that by far the greatest increase was in the "35-54 years" group followed by the "55-74 years" group and the "25-34 years" group in that order. Interestingly there has been almost no change to the "5-14 years" age group.

## 5

![Total Suicides by Sex (1985-2015)](plots/Total%20Suicides%20by%20Sex%20(1985-2015).png)

### Analysis 

We can see that the majority of the suicides between 1985 and 2015 have been men at around 70%. Let’s explore this proportion throughout the years and in different countries.

## 6

![Suicides by Sex Over Time](plots/Suicides%20by%20Sex%20Over%20Time.png)

### Analysis 

We can see that men have always had a higher rate than women throughout the years. Interestingly, women’s suicide numbers have remained roughly the same—only fluctuating slightly—whereas men’s numbers have changed drastically throughout, experiencing a spike in 1988, a peak in 2003, and a 20-year minimum in 2015.

## 7

![Suicides by Country and Gender](plots/Suicides%20by%20Country%20and%20Gender.png)

### Analysis 

Some countries had missing values for this comparison, so this might not be the most accurate comparison; however, it is very interesting to see such a high degree of discrepancy between the proportions. The men’s suicide numbers go as low as 60%–70% for some countries. Interestingly most of these are in East and Southeast Asia, but not exclusively, with Albania and the Netherlands having the 3rd and 4th highest male proportions respectively.

## 8

![Change in Suicides per Country](plots/Change%20in%20Suicides%20per%20Country.png)

### Analysis 

We can also see that even though the overall trend of suicide numbers is decreasing, not all countries follow this trend. The top 10 increase rates are of higher magnitude than the top 10 decrease rates. However, the worldwide decreasing trend suggests that these countries are outliers rather than the majority. Exploring the reasons behind these increases could be insightful.

## Summary
In this analysis of global suicide data, we revealed that middle age people are at the highest risk, having higher numbers than younger and older demographics. Further, significant discrepancies were revealed between male and female suicide rates. And some countries, especially countries in east Europe such as Russia had higher rates, while some countries have higher increases overtime. 

