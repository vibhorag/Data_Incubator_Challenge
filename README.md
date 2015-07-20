# Data_Incubator_Challenge
This is the mock repository for initial financial data analysis.The Financial data decription is following:
The data represents features of various financial securities (198 in total) recorded at 5-minute intervals throughout a trading day.  feature name have been renamed starting with O.

data.zip - contains features for 510 days worth of trading, including 200 training days and 310 testing days
trainLabels.csv - contains the targets for the 200 training days

Each variable named O1, O2, O3, etc. (the outputs) represents a percent change in the value of a security.  Each variable named I1, I2, I3, etc. (the inputs) represents a feature. The underlying securities and features represented by these anonymized names are the same across all files (e.g. O1 will always be the same stock).

Within each trading day, you are provided the outputs as a relative percentage compared to the previous day's closing price.  The first line of each data file represents the previous close. For example, if a security closed at $1 the previous day and opened at $2 the next day, the first output would be 0, then 100.  All output values are computed relative to the previous day's close. The timestamps within each file are as follows (ignoring the header row):

Line 1 = Outputs and inputs at previous day's close (4PM ET)
Line 2 = Outputs and inputs at current day's open (9:30AM ET)
Line 3 = Outputs and inputs at 9:35AM ET
...
Line 55 = Outputs and inputs at 1:55PM ET
