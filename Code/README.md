  * Code (Python Notebooks)
    * Data Extraction: This refers to the raw data from the Experimental_Data folder (downloaded from the temporal discounting paradigm designed in lab.js), and creates anonymized, cleaned choice data, and stores them in Cleaned_Data and Combined_Data (information for all participants). 
    * DataToPatienceMeasures: This file reads in the cleaned data, extracts indifference points using logistic regression fits, performs curve fitting for linear, hyperbolic and exponential discounting functions, and then uses bootstrapping and bounds to ensure validity of estimates. 
    * TrendGeneration: Based on the fitting parameters and survey data, the trends and correlations were found. Although the results are insignificant, some correlations appear to exist. 
  *  Results (Other files & folders) 
      * Plots: Contain all the generated plots, including:
        * Logistic Regression Plots
        * Heatmaps
        * Fitting plots 
        * Bootstrapping plots 
     * PatienceMeasures: Stores the fitting parameters for the linear, hyperbolic and beta-delta function fits 
     * ParticipantEstimates: Stores the bootstrapping estimates, error values, 95% confidence intervals for all fit parameters, and indicates if the k-value was within the range
     * Trends: Contains the plots generated for the visualization of the fitting parameters versus the state of mind factors collected from the survey. This also contains the linear fits generated for Happiness, Stress, and Sleep with respect to the hyperbolic discounting factor k under various conditions. 
