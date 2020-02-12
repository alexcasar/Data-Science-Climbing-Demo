# Data-Science-Climbing-Demo

## Description

This git consists of a step-by-step example of a basic data science work flow, from data aquisition and preparation, to exploratory analysis, to pattern/correlation finding and finally to inference or prediction modeling. Different phases of the pipeline will be divided into different files in order to make it more evident and specific.

The data used for this exercise will be information regarding rock-climbers' profile and their climbing performance. Information was gathered using the following on-line survey https://forms.gle/dgZAkwvBHcoapj8D9 (feel free to answer it if you happen to be a rock-climber, to continue gathering data) so the data consist of real climbers' profiles.

It is intended as an introductory showcase of data science pipeline in a real world scenario, in order to provide a little bit of guideline to those interested in data science but which do not know how to initially get into it.

I hope someone finds it useful.

## Files

### Data Files
#### 0.1 rawData.csv:
Contains the answers to the survey shown above:

#### 0.2 niceData.csv
Contains the data after going through the Data Preparation phase.

#### 0.3 filteredData.csv
Contains the data after outlier removal.

#### 0.4 normData.csv
Contains the data after going through min-max scaling.

#### 0.5 features.csv
Contains the features resulting from the feature importance phases.

### Jupyter Notebooks
#### 1. Data Preparation
Contains the code and explanation for transforming the raw data into a more processing-friendly format.
*Note that there was very little data cleaning in this example, this is because the survey has some basic input validation and I performed a simple data clean-up as well just to reduce the scope of this example. Industrial scenarios will have a lot of miss-inputs, incorrect datatypes, missing data, etc. which have different strategies to deal with, but which I won't exemplify here.

#### 2. Data Exploratory Analysis
This document will showcase the normal initial exploratory analysis, where you simply try to look at the data to see how each variable behaves, their distribution, their behavior over different subsets of the whole population, etc.

#### 3. Correlation and feature importance
This will finally start showing some insights as to how the variables interact with each other, and which variables -seem- to have an impact (correlation does not imply causation) on the variables you care about the most .

#### 4. Inference, forecast and optimization
Finally this will showcase how to use the correlations previously found in order to infer performance on the variable of interests, or to suggests strategies to improve or optimize it.

## Notes

Data science is very dependent on the amount and quality of data. This was performed using only 156 responses (extremely little database) of a survey created by myself, someone with data science knowledge but without any proper knowledge about climbing or sports science, nor the tools to get more detailed quantitative information (rather bad quality of data). With either more responses, or with the help of an actual sports professional to create a more appropiate survey to gather actually useful information or the actual application of physical tests, the performance of these kinds of analysis will greatly improve, the results would be more evident and the findings become much more useful.

This notebook is a static shot of the code from the last time I ran it, if you download the code and run it in your own computer, the results may change and the "hardcoded examples" might stop making any sense because several of the processes are stochastic. This means that they have an intrinsic randomness in their inner workins that causes them to yield different outputs every time you run them, but usually quite similar. This is both good and bad, a good thing is that you can run these processes many times, storing the best result (as we did in the "trainModel" methods of this function) to get very good performances, but the bad thing is that they might not be directly replicable if the random seed was not stored.

## Collaboration

Feel free to contact me at alexcasar@gmail.com if you would like to collaborate on a data-driven climbing project.
