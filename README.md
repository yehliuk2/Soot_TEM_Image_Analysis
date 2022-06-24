# Soot TEM Image Analysis Tool
This repository contains the Matlab scripts files that are needed to analyze the nanostructure of the TEM images of soot 

### Recommended File Format and Magnification
Recommended File Format: TIF, 1024*1024, 8-bit Gray Scale, 300k - 500k 

### Dependencies
Required product: MATLAB and Image Processing Toolbox 
Please use the follow command to find the file dependencies. 
[flist,plist]=matlab.codetools.requiredFilesAndProducts('Filename.m')

### Platform 
This tool is verified by executing on MATLAB 2009a (Windows XP) and MATLAB R2019a (Windows 10) and the associated image processing toolbox. 

### Preparation
Extract the zip file from the website. Then, start Matlab and set the current path to the folder containing all the extracted files. 

### Recommended Order of Execution
(1) load_image_and_process_v30.m 
(2) analysis_fringe_v30.m
(3) fringe_space_analyze_v30.m
(4) load_data_and_process_v30.m 

### Auxiliary program
plot_scale.m
Find_out_scale_simple.m

### Tutorial
ImageAnalysisToolTutorial.ppt
Some line numbers are outdated so please refer to the variable names and search in the code when the line numbers does not match with the variable names. 

### Reference
Kuen Yehliu, Randy L. Vander Wal, André L.Boehman, Development of an HRTEM image analysis method to quantify carbon nanostructure, Combustion and Flame, Volume 158, Issue 9, September 2011, Pages 1837-1851
