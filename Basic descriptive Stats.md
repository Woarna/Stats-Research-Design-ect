# Measures of Central Tendency

Central tendency is the archetypal value in a probability distribution. 
The three most common measures of central tendency are mean, median, and mode. 
The mean can be expressed as the following summation.

![image](https://cdn.discordapp.com/attachments/928314217617043456/928315053759946812/unknown.png)

Where N is the amount of observations.
The median is the middle value is an ordered list of numbers.
The mode of a sample is the value that occurs the most frequently.

* If your data is nominal, the use of mean and median don't make much sense as measures of central tendency as numerical values don't have much meaning. It's probably best to use mode.
* if your data is ordinal, median is probably the measure of central tendency you want to use. Median makes use of the ordering of numbers.
* If your data is either interval or ratio, preference for mean or median depends on what you're trying to achieve. The mean has the advantage of using all information in the data, but is sensitive to extreme outliers.

# Measures of Variability

Variability is the difference exhibited between data points in a data set. 
The most common measures of variability are range, interquartile range, mean absolute deviation, median absolute deviation, variance, and standard deviation.

The range of a data set is the biggest value of the set minus the smallest value. This is one of the worst measures of variability, outliers skew the value heavily.
The interquartile range is similar except it's the difference between the 25th percentile and 75th percentile. (x-th percentile is the value where x% of the data falls below). 
This can be thought of as the range of the middle half of the data.

While range and interquartile range measure variability by looking at the spread of the data, another way of measuring variability is selecting a meaningful reference point 
(like the mean) and then reporting the typical deviations from that reference point. The typical deviation is usually either the mean or median value of the deviations. 
This leads to two different measures, the mean absolute deviation or the median absolute deviation. Let the mean absolute deviation be AAD (Using A for average rather than M for mean to avoid confustion between mean and median absolute deviation)

If so, the mean absolute deviation is the following

![image](https://cdn.discordapp.com/attachments/928314217617043456/928324030254186496/unknown.png)

Where N is the total number of observations and X bar is the mean. It's the ABSOLUTE deviation because we take the absolute value of the data subtracted from the average.

Suppose we squared the deviation from the mean rather than simply taking the absolute value. Doing so gives us the variance

![image](https://cdn.discordapp.com/attachments/928314217617043456/928325246740729906/unknown.png)

**NOTE:** This is if you LITERALLY intend to calculate the variance of a sample purely descriptively. Variance is calculated different when drawing inferences

Standard deviation is the square root of the variance.

![image](https://cdn.discordapp.com/attachments/928314217617043456/928326787363119124/unknown.png)

Quick summary of measures of Variability:

![image](https://cdn.discordapp.com/attachments/928314217617043456/928327569743437874/unknown.png)
![image](https://cdn.discordapp.com/attachments/928314217617043456/928327569995092018/unknown.png)

# Skewness

Skewness is a measure of asymmetry.
If a data has a lot of extreme small values and not so many extremely large values the data is negatively skewed, in reverse the data is called positively skewed

![image](https://cdn.discordapp.com/attachments/928314217617043456/928328576313487400/unknown.png)
![image](https://cdn.discordapp.com/attachments/928314217617043456/928328948134330378/unknown.png)

Where N is number of observations, X bar is the mean, and Delta Hat is standard deviation (For the delta hat standard deviation calculation, 1/N-1 is used over 1/N)

# Kurtosis

The kurtosis is the "pointyness" of a set of data, not used very much as a method of analysis.

![image](https://cdn.discordapp.com/attachments/928314217617043456/928329259280371774/unknown.png)
![image](https://cdn.discordapp.com/attachments/928314217617043456/928329315010105425/unknown.png)
![image](https://cdn.discordapp.com/attachments/928314217617043456/928329358714761217/unknown.png)

**NOTE:** The -3 in the kurtosis calcuation is used to ensure a normal distribution has a kurtosis zero

# Standard scores

Standard scores (also referred to as z-scores) are defined as the number of standard deviations above the mean some score lies.

![image](https://cdn.discordapp.com/attachments/928451370191843368/928451379385761814/unknown.png)

In addition to allowing you to interpret a raw score in relation to a larger population (and thereby allowing you to make sense of variables that lie on arbitrary scales), 
standard scores serve a second useful function. Standard scores can be compared to one another in situations where the raw scores can’t. 
Because each standardised score is a statement about where an observation falls relative to its own population, it is possible to compare standardised scores across completely different variables.

