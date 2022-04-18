# temporal-discounting
Behavioral Experiment on Temporal Discounting (Implementation in Python) 
Contents of the Project

1. Cleaned_Data: Contains the anonymized data at a partipant level for their Choices and Information. There is one file for the participant’s choices, one for their survey information, and one containing both. The response times are included, and reference IDs have been assigned. 
2. Code: 
I.	Code (Python Notebooks)
a.	Data Extraction: This refers to the raw data from the Experimental_Data folder (downloaded from the temporal discounting paradigm designed in lab.js), and creates anonymized, cleaned choice data, and stores them in Cleaned_Data and Combined_Data (information for all participants). 
b.	DataToPatienceMeasures: This file reads in the cleaned data, extracts indifference points using logistic regression fits, performs curve fitting for linear, hyperbolic and exponential discounting functions, and then uses bootstrapping and bounds to ensure validity of estimates. 
c.	TrendGeneration: Based on the fitting parameters and survey data, the trends and correlations were found. Although the results are insignificant, some correlations appear to exist. 
II.	Results (Other files & folders) 
a.	Plots: Contain all the generated plots, including:
b.	Logistic Regression Plots
c.	Heatmaps
d.	Fitting plots 
e.	Bootstrapping plots 
f.	PatienceMeasures: Stores the fitting parameters for the linear, hyperbolic and beta-delta function fits 
g.	ParticipantEstimates: Stores the bootstrapping estimates, error values, 95% confidence intervals for all fit parameters, and indicates if the k-value was within the range
h.	Trends: Contains the plots generated for the visualization of the fitting parameters versus the state of mind factors collected from the survey. This also contains the linear fits generated for Happiness, Stress, and Sleep with respect to the hyperbolic discounting factor k under various conditions. 
3. Combined_Data: This folder contains the .csv files with the data combined for all participants. All choice data and survey information is collated into a single file for easier use
4. Experimental_Data: This folder contains the original data collected from the participants. (Since it contains identifying information, these files will not be uploaded to GitHub.) Once files are generated using our temporal discounting paradigm, they should be placed here for appropriate data extraction. 
5. FinalParadigm: This folder contains a copy of our temporal paradigm. This was created using lab.js, and was published online via Netlify at: https://tubular-basbousa-d35eae.netlify.app/
6. Report: This contains the report for project 1, as submitted for the course Representations of Choice on 18th April, 2022. This is a Spring course with course code: 580.462 at Johns Hopkins University. The figures & tables included in the Report are also provided separately in the PowerPoint presentation entitles ‘Figures’. 

