# Results_VR_S1

The data was processed according to the following steps:

- Resample data using the Matlab resample method (90 Hz)
- Filter data with a low-pass Butterworth filter (dual pass, 10 Hz cutoff, 2nd order)
- Motion onset and motion termination were calculated to extract the reach trajectory
- FDA-based normalization of the data

The following metrics were calculated:

- it : initiation time
- mt: movement time
- mpd : maximum perpendicular deviation 
	- xz
	- xy
	- zy
	- xzy

Note: changes of mind have not been calculated as the baseline trials to be considered have not been specified.

The results can be found in the csv files within the Hand Tracking Metrics folder

Warning: The FDA-based normalization method might return duplicate elements of the array which triggers an error in the subsequent methods.
The duplicate elements were deleted and this number is indicated in the output file (fda_de). If 0, no element was eliminated (which is the case for most trials).
 
