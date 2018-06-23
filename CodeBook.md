# Code book for Getting and Cleaning Data course project

The structure of dataset is explained in the *data section*, its variables in the *Variables section*.

## Data 

The `tidy_data.txt` data file is a text file, containing space-separated values.

The first row contains the names of the variables, which are listed and described in the Variables section, and the following rows contain the values of these variables. 

## Variables
Each row contains, for a given subject and activity, 79 averaged signal measurements.

### Identifiers

- *subject*

	Subject identifier, integer, ranges from 1 to 30.

- *activity*

	Activity identifier, string with 6 possible values: 
	- WALKING
	- WALKING_UPSTAIRS
	- WALKING_DOWNSTAIRS
	- SITTING
	- STANDING
	- LAYING

### Average of measurements

#### Time-domain signals

- Average time-domain body acceleration in the X, Y and Z directions:

	- timeDomainBodyAccelerometerMeanX
	- timeDomainBodyAccelerometerMeanY
	- timeDomainBodyAccelerometerMeanZ

- Standard deviation of the time-domain body acceleration in the X, Y and Z directions:

	- timeDomainBodyAccelerometerStandardDeviationX
	- timeDomainBodyAccelerometerStandardDeviationY
	- timeDomainBodyAccelerometerStandardDeviationZ

- Average time-domain gravity acceleration in the X, Y and Z directions:

	- timeDomainGravityAccelerometerMeanX
	- timeDomainGravityAccelerometerMeanY
	- timeDomainGravityAccelerometerMeanZ

- Standard deviation of the time-domain gravity acceleration in the X, Y and Z directions:

	- timeDomainGravityAccelerometerStandardDeviationX
	- timeDomainGravityAccelerometerStandardDeviationY
	- timeDomainGravityAccelerometerStandardDeviationZ

- Average time-domain body acceleration jerk in the X, Y and Z directions:

	- timeDomainBodyAccelerometerJerkMeanX
	- timeDomainBodyAccelerometerJerkMeanY
	- timeDomainBodyAccelerometerJerkMeanZ

- Standard deviation of the time-domain body acceleration jerk in the X, Y and Z directions:

	- timeDomainBodyAccelerometerJerkStandardDeviationX
	- timeDomainBodyAccelerometerJerkStandardDeviationY
	- timeDomainBodyAccelerometerJerkStandardDeviationZ

- Average time-domain body angular velocity in the X, Y and Z directions:

	- timeDomainBodyGyroscopeMeanX
	- timeDomainBodyGyroscopeMeanY
	- timeDomainBodyGyroscopeMeanZ

- Standard deviation of the time-domain body angular velocity in the X, Y and Z directions:

	- timeDomainBodyGyroscopeStandardDeviationX
	- timeDomainBodyGyroscopeStandardDeviationY
	- timeDomainBodyGyroscopeStandardDeviationZ

- Average time-domain body angular velocity jerk in the X, Y and Z directions:

	- timeDomainBodyGyroscopeJerkMeanX
	- timeDomainBodyGyroscopeJerkMeanY
	- timeDomainBodyGyroscopeJerkMeanZ

- Standard deviation of the time-domain body angular velocity jerk in the X, Y and Z directions:

	- timeDomainBodyGyroscopeJerkStandardDeviationX
	- timeDomainBodyGyroscopeJerkStandardDeviationY
	- timeDomainBodyGyroscopeJerkStandardDeviationZ

- Average and standard deviation of the time-domain magnitude of body acceleration:

	- timeDomainBodyAccelerometerMagnitudeMean
	- timeDomainBodyAccelerometerMagnitudeStandardDeviation

- Average and standard deviation of the time-domain magnitude of gravity acceleration:

	- timeDomainGravityAccelerometerMagnitudeMean
	- timeDomainGravityAccelerometerMagnitudeStandardDeviation

- Average and standard deviation of the time-domain magnitude of body acceleration jerk:

	- timeDomainBodyAccelerometerJerkMagnitudeMean
	- timeDomainBodyAccelerometerJerkMagnitudeStandardDeviation

- Average and standard deviation of the time-domain magnitude of body angular velocity:

	- timeDomainBodyGyroscopeMagnitudeMean
	- timeDomainBodyGyroscopeMagnitudeStandardDeviation

- Average and standard deviation of the time-domain magnitude of body angular velocity jerk:

	- timeDomainBodyGyroscopeJerkMagnitudeMean
	- timeDomainBodyGyroscopeJerkMagnitudeStandardDeviation

#### Frequency-domain signals

- Average frequency-domain body acceleration in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerMeanX
	- frequencyDomainBodyAccelerometerMeanY
	- frequencyDomainBodyAccelerometerMeanZ

- Standard deviation of the frequency-domain body acceleration in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerStandardDeviationX
	- frequencyDomainBodyAccelerometerStandardDeviationY
	- frequencyDomainBodyAccelerometerStandardDeviationZ

- Weighted average of the frequency components of the frequency-domain body acceleration in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerMeanFrequencyX
	- frequencyDomainBodyAccelerometerMeanFrequencyY
	- frequencyDomainBodyAccelerometerMeanFrequencyZ

- Average frequency-domain body acceleration jerk in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerJerkMeanX
	- frequencyDomainBodyAccelerometerJerkMeanY
	- frequencyDomainBodyAccelerometerJerkMeanZ

- Standard deviation of the frequency-domain body acceleration jerk in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerJerkStandardDeviationX
	- frequencyDomainBodyAccelerometerJerkStandardDeviationY
	- frequencyDomainBodyAccelerometerJerkStandardDeviationZ

- Weighted average of the frequency components of the frequency-domain body acceleration jerk in the X, Y and Z directions:

	- frequencyDomainBodyAccelerometerJerkMeanFrequencyX
	- frequencyDomainBodyAccelerometerJerkMeanFrequencyY
	- frequencyDomainBodyAccelerometerJerkMeanFrequencyZ

- Average frequency-domain body angular velocity in the X, Y and Z directions:

	- frequencyDomainBodyGyroscopeMeanX
	- frequencyDomainBodyGyroscopeMeanY
	- frequencyDomainBodyGyroscopeMeanZ

- Standard deviation of the frequency-domain body angular velocity in the X, Y and Z directions:

	- frequencyDomainBodyGyroscopeStandardDeviationX
	- frequencyDomainBodyGyroscopeStandardDeviationY
	- frequencyDomainBodyGyroscopeStandardDeviationZ

- Weighted average of the frequency components of the frequency-domain body angular velocity in the X, Y and Z directions:

	- frequencyDomainBodyGyroscopeMeanFrequencyX
	- frequencyDomainBodyGyroscopeMeanFrequencyY
	- frequencyDomainBodyGyroscopeMeanFrequencyZ

- Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body acceleration:

	- frequencyDomainBodyAccelerometerMagnitudeMean
	- frequencyDomainBodyAccelerometerMagnitudeStandardDeviation
	- frequencyDomainBodyAccelerometerMagnitudeMeanFrequency

- Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body acceleration jerk:

	- frequencyDomainBodyAccelerometerJerkMagnitudeMean
	- frequencyDomainBodyAccelerometerJerkMagnitudeStandardDeviation
	- frequencyDomainBodyAccelerometerJerkMagnitudeMeanFrequency

- Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body angular velocity:

	- frequencyDomainBodyGyroscopeMagnitudeMean
	- frequencyDomainBodyGyroscopeMagnitudeStandardDeviation
	- frequencyDomainBodyGyroscopeMagnitudeMeanFrequency

- Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body angular velocity jerk:

	- frequencyDomainBodyGyroscopeJerkMagnitudeMean
	- frequencyDomainBodyGyroscopeJerkMagnitudeStandardDeviation
	- frequencyDomainBodyGyroscopeJerkMagnitudeMeanFrequency
