# The set of variables that were estimated from these signals are:

mean(): Mean value

std(): Standard deviation

mad(): Median absolute deviation

max(): Largest value in array

min(): Smallest value in array

sma(): Signal magnitude area

energy(): Energy measure. Sum of the squares divided by the number of values.

iqr(): Interquartile range

entropy(): Signal entropy

arCoeff(): Autoregression coefficients with Burg order equal to 4

correlation(): Correlation coefficient between two signals

maxInds(): Index of the frequency component with largest magnitude

meanFreq(): Weighted average of the frequency components to obtain a mean frequency

skewness(): Skewness of the frequency domain signal

kurtosis(): Kurtosis of the frequency domain signal

bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.

angle(): Angle between some vectors.


# Name	Time domain	Frequency domain
* Body Acceleration	TimeDomain.BodyAcceleration.XYZ	FrequencyDomain.BodyAcceleration.XYZ
* Gravity Acceleration	TimeDomain.GravityAcceleration.XYZ	
* Body Acceleration Jerk	TimeDomain.BodyAccelerationJerk.XYZ	FrequencyDomain.BodyAccelerationJerk.XYZ
* Body Angular Speed	TimeDomain.BodyAngularSpeed.XYZ	FrequencyDomain.BodyAngularSpeed.XYZ
* Body Angular Acceleration	TimeDomain.BodyAngularAcceleration.XYZ	
* Body Acceleration Magnitude	TimeDomain.BodyAccelerationMagnitude	FrequencyDomain.BodyAccelerationMagnitude
* Gravity Acceleration Magnitude	TimeDomain.GravityAccelerationMagnitude	
* Body Acceleration Jerk Magnitude	TimeDomain.BodyAccelerationJerkMagnitude	FrequencyDomain.BodyAccelerationJerkMagnitude
* Body Angular Speed Magnitude	TimeDomain.BodyAngularSpeedMagnitude	FrequencyDomain.BodyAngularSpeedMagnitude
* Body Angular Acceleration Magnitude	TimeDomain.BodyAngularAccelerationMagnitude	FrequencyDomain.BodyAngularAccelerationMagnitude

Note: features are normalized and bounded within [-1,1].

The data set is written to the file tidydata.txt.
