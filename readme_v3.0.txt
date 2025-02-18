SherlocFitAnalyzer
developed by gpoggiali

Current version 3


############################
Program description

This program was developed to analyse Scherloc raman spectra fitting multiple Voigt function on a selected band.
The program also allow to evaluate the noise in specific range to compare it with the intensity of the target band.
A the end if no error appear, the program will save in the current path three file:
- (png file) figure of the band analysed with fit overplotted the original data and the background with evaluated peak intensity.
- (txt file) report with all the information used in the analysis and the list of detected peak
- (csv file) table with the estimated parameters from the fit procedure

############################
Program initialization

To run the program be sure the adds-on "Image Processing Toolbox" and "Curve Fitting Toolbox" are installed in your current Matlab version.

1) Download the main file (matlab live script) with the current version
SherlocFitAnalyzer_v#.#.mlx

2) Download the folder named "ancillary_functions" and store it in the same folder of the main file

3) Open the main file and select the option "Hide code" from the menu at top right of the live script file

4) Follow the instruction on the live script to proceed with the analysis


############################
Log of changes

Version 1.0 - initial version

Version 2.0 - implementation of manual background removal and modification of ancillary functions

Version 2.1 - evaluation of single band areas as output parameter, addition of date and time in report file name

Version 3.0 - Added the possibility to select the spectrum from the computer folders. Removed the possibility of automatic baseline evaluation. Removed the option of gaussian fit helper to set initial parameter. Removed the manual setting of initial parameter, Changed the algorithm for fit evaluation to obtain errors on the fit. Add the error for each parameter and chi2 in the report.

