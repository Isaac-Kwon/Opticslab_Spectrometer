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
		* Broad Peak
			* Fitting with Gamma Distribution or Maxwell-Boltzmann Distribution
		* Sharp Peak
			* Fitting with Gaussian Function
		* Sharp Peak with Background Slope
			* Fitting with Gaussian Function + Linear Slope (Background)
		* Find FWHM (Full Width of Half Maximum) or Sigma from fitting function.
* Plot raw data graph and fitted graph all together

### When cannot seperate
When cannot seperate peak of data from background noise, it should be been binning. Then, it can be terminate because almost all noise are sinusoidal ('binning' will integrate value and cancel fluctuation)


## This Repo Contains.
* Raw Data of Spectrometer of experiments

### Will Contain
* Data Analyze Script for MATLAB
* Analyzed Data
