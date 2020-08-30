# Nonlinear-FEM-Integration-Scheme
Comparative study on using Full Integration, Reduced Integration and Selective Reduced Integration for cantilever beam subjected to tip shear.
1. In the main folder, there are three main folders.
   One for Full Integration, One for Reduced Integration and One for SRI.
   In each integration folder there are MATLAB Files:
   	Main File: 'Final_Project_FI.m'
   	Function Files: 'DTS.m', 'calstress.m', 'plotbeam.m', 'shape.m', 'MatConst.m'
   	Additional function files for SRI: 'DTS_SRI.m', 'MatConstdev.m', 'MatConstvol.m'
 
   There are three subfolders in each main folder that includes results for each element discretization
	Subfolders: '20by2', '40by4', '80by8'
	
2. Folder 'Comparative Study' includes all the plots to compare FI, RI and SRI for load vs. displacement and stress values. 
	Matlab File: 'Plot_project_final.m'
   To import data for Matlab File two excel files are also kept in the same folder
	Excel Files: 'Plot_project.xlsx', 'Final Project Reference Solution.xlsx'
