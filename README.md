# Outliers Detection

This repository contains code that demonstrates the identification of outliers in a dataset using two different methods: the Z-score method and the Interquartile Range (IQR) method. 

Outliers are data points that significantly deviate from the rest of the data, and their identification is crucial in various statistical analyses.

## Table of Contents

- [Overview](#overview)
- [Z-Score Method](#z-score-method)
- [IQR Method](#iqr-method)

## Overview

In statistics, an outlier is an observation that lies an abnormal distance from other values in a random sample from a population. These outliers can skew results and affect the accuracy of statistical analysis. The Z-score method and the IQR method are two common approaches for identifying outliers in a dataset.

## Z-Score Method

The Z-score method is based on standardizing the data by subtracting the mean and dividing by the standard deviation. Any data point with a Z-score greater than a certain threshold (typically 2 or 3) is considered an outlier. This method is useful for normally distributed data.

## IQR Method

The Interquartile Range (IQR) method defines outliers as data points that fall below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR, where Q1 is the first quartile and Q3 is the third quartile. This method is robust to non-normally distributed data and is less sensitive to extreme values than the Z-score method.


This is a part of amazing statistics course by Krish Naik Sir, available for FREE! on Youtube. [Stats Playlist](https://www.youtube.com/playlist?list=PLTDARY42LDV6YHSRo669_uDDGmUEmQnDJ)
