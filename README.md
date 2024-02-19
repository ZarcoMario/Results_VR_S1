# Results_VR_S1

The data was processed according to the following steps:

- Resample data using the Matlab resample method (90 Hz)
- Filter data with a low-pass Butterworth filter (dual pass, 10 Hz cutoff, 2nd order)
- Motion onset and motion termination were calculated to extract the reach trajetcory
- FDA-based normalization of the data

The following metrics were calculated:

- it : initiation time
- mt: movement time
- mpd : maximum perpendicular deviation 
	- xz
	- xy
	- zy
	- xzy

Note: changes of mind have not beeen calculated as the baseline trials to be considered have not been specified.

 
