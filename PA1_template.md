---
title: "Reproducible Research: Peer Assessment 1"
author: "Tobias""
output: 
  html_document:
    keep_md: true
---


## Loading and preprocessing the data

```r
activity <-read.csv("activity.csv")
```


## What is mean total number of steps taken per day?

```r
boxplot(activity$interval)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png) 


## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
