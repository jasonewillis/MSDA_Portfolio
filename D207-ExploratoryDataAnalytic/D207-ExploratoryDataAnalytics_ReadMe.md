# Exploratory Data Analytics Project (D207)
MDSA Course D207 - Exploratory Data Analytics
- Hypothesis: "Did a patient’s initial inpatient stay (Initial_days) show an effect on their potential readmissions within our hospital chain?"
- By addressing the hypotheses directly between the chosen independent variables, the outcome should provide a group of patients to focus deeper on in reducing overall patient readmissions.  Through our initial exploratory analysis, the following data was directly compared:
  - If the patient was readmitted
  - If the patient was overweight
  -	The patients’ total charges for their inpatient stay
  -	The initial inpatient stay (in days) 
Analyzing these variables with an Analysis of Variance test (ANOVA), a test comparing the mean of two groups of data sets, i.e. if patients were readmitted or not.  Then, by comparing these independent variables, we were able to see a relation between patient initial stay length which pointed to a higher chance of readmission.



### ANOVA Test Comparing Patient Stay (Initial Days_ and Readmissions:

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207_ANOVA.png?raw=true "ANOVA")


### Histogram Compareing Initial Stay and Readmissions: 

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207HistogramCompareInitialStayAndReadmins.png?raw=true "Histogram")

### Univariate Analysis: Continuous and Categorical Data: 

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207_UnivariateAnalysisContViewingMedianAndModeStatistics.png?raw=true "Histogram")

### Univariate Continued: Viewing Median and Mode Statistics: 

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207_UnivariateAnalysisContViewingMedianAndModeStatistics.png?raw=true "Histogram")

### Histogram Plotting Numerical Data of Patients Vs Initial Patient Stay and Total Charges: 

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207HistogramsPlottingNumericalDataOfPatientsVsInitialInpatientStayAndTotalCharges.png?raw=true "Histogram")


### Boxplots Comparing Independent Variables: 

![alt text](https://github.com/jasonewillis/D207ExploratoryDataAnalytics/blob/19b0a6e39b5e83f9af7ff371fed6456a33973742/D207BoxplotsVisualizingComparisonsBetweenIndependentVariables.png?raw=true "Histogram")


# Recommended Course of Action
From the ANOVA testing, we can see a high F-statistic and low p-value which indicates the null hypothesis that initial stay length does not affect readmission rates, is rejected.  By referencing the Histogram comparing initial stay and remissions, Boxplots comparing initial stay and remissions and the average initial days calculated when a patient is readmitted, hospital providers could follow up with patients whose initial inpatient stays approached 60 days in length (average stay of readmitted patients was ~64 days), since these patients seem to have a higher risk of readmission within 30 days of their initial inpatient release.  By continuing a thread of communication, our hospitals could start to learn why this group is more prone to readmissions while making the process, if necessary, as seamless as possible.  

Additionally, I feel further investigation is required into known but not yet analyzed data and potentially additional data e.g. provider notes, reason for hospitalization in order to help understand the how and/or why better.  


