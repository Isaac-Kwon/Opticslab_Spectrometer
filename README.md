# Opticslab_Spectrometer
Analyzing Data of Spectrometer for lecture, 'Optics Laboratory'

Require MATLAB, Curve Fitting Toolbox.

## Sequence of Analyzing

### When data's peaks can separate from background noise
* Input raw data (xlsx)
* Convert raw data to MATLAB Data file
* Plot raw data graph
* Analyze graph
	* Select peak region to fit function
		* Sharp Peak
			* Fitting with Gaussian Function
		* Broad Peak
			* Fitting with Gamma Distribution or Maxwell-Boltzmann Distribution
		* Find FWHM (Full Width of Half Maximum) or Sigma from fitting function.
* Plot raw data graph and fitted graph all together

### When cannot seperate
When cannot seperate peak of data from background noise, it should be been binning. Then, it can be terminate because almost all noise are sinusoidal ('binning' will integrate value and cancel fluctuation)
