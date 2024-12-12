# SherlocFitAnalyzer
developed by giopoggiali (Giovanni Poggiali, giovanni.poggiali@inaf.it)

Current version 2.2

Copyright (C) 

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.


############################
System requirements

The software was developed on MATLAB 2024a (but could be used on older version) using a Windows operating system. It could be used with MATLAB on any operating system.
Some problem could arise from the folder path format in the code and can be manually corrected depending on the used operating system.

Once MATLAB is installed on the computer the SherlocFitAnalyzer will run as a script without any additional installation.


############################
Program description

This program was developed to analyse Scherloc raman spectra fitting multiple Voigt functions on a selected band.
The program also allows to evaluate the noise in specific ranges to compare it with the intensity of the target band.

At the end of the fitting process, if no errors appear, the program will save three files in the current path:
- (png file) figure of the analysed band showing the fit overplotted onto the original data and the background, with the evaluated peak intensity highlighted
- (txt file) report with all the information used in the analysis and the list of detected peaks
- (csv file) table with the estimated parameters from the fit procedure

A simulated band to test the scrip and the obtained results is included in the release.

The code will typically take a few minutes to fit a complex band (more than 1 peak) the analysis time will increase depending on the number of peak in the band.

############################
Program initialization and run

1) Download the main file (matlab live script) with the current version
SherlocFitAnalyzer_v#.#.mlx

2) Download the folder named "ancillary_functions" and store it in the same folder of the main file

3) Open the main file and select the option "Hide code" from the menu at top right of the live script file

4) Use the first button to upload the spectrum to be analysed

5) Follow the instructions on the live script to proceed with the analysis

6) The script will save in the current path the output specified above


############################
Log of changes

Version 1.0 - initial version

Version 2.0 - implementation of manual background removal and modification of ancillary functions

Version 2.1 - evaluation of single band areas as output parameter, addition of date and time in report file name

Version 2.2 - added the possibility of select and import any spectrum from the computer

