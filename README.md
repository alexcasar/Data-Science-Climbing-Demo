# Data-Science-Climbing-Demo

## Description

This git consists of a step-by-step example of a basic data science work flow, from data aquisition and preparation, to exploratory analysis, to pattern/correlation finding and finally to inference or prediction modeling. Different phases of the pipeline will be divided into different files in order to make it more evident and specific.

The data used for this exercise will be information regarding rock-climbers profile and their climbing performance. Information was gathered using the following on-line survey https://forms.gle/dgZAkwvBHcoapj8D9 (feel free to answer it if you happen to be a rock-climber, to continue gathering data) so the data consist to real climbers' profiles.

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
