# Analysis of data_science_job Dataset

## TABLE OF CONTENT

- [INTRODUCTION](#introdction)
- [DATA SOURCES](#data-sources)
- [TOOLS](#tools)
- [DATA CLEANING AND PREPARATION](#data-cleaning-and-preparation)
- [EXPLORATORY DATA ANALYSIS (EDA)](#exploratory-data-analysis-(eda))
- [RESULTS / FINDINGS](#results-/-findings)
- [CONCLUSIONS](#conclusions)
- [LIMITATIONS](#limitation)


### INTRODUCTION 
This dataset contains job listings for data science positions, providing a comprehensive view of the data science job market from year 2000 to 2002. This will help users analyze trends in data science employment.

### DATA SOURCES       
The primary data source for this analysis existed as ' data_science_job.csv' file. This is a 5000-row dataset that includes essential fields such as job title, company location, employee residence, work setting, salary in USD, required skills etc.

### TOOLS
1.	Python – Data Cleaning and EDA
2.	Power BI – Data visualization and Creating of  report

### DATA CLEANING AND PREPARATION
1.	There were 500 null values and they were replaced with ‘NA’
2.	The various columns were changed to their respective data types in power BI.
3.	Columns containing salary currency and salary were deleted while I maintained the salary in usd, which I used for the analysis.


### EXPLORATORY DATA ANALYSIS (EDA)
EDA involved exploring the 'data science job’ dataset to answer key questions, such as
1.	What is the most sort-after Data science job?
2.	What is the average salary for the various job titles in the data science roles?
3.	Which country offers most employment for the data science job?
4.	What are the average salaries for the various employment types in data science?
5.	Which type of work setting is most appropriate for the various data science jobs?
6.	What are the demands for various skills in data science roles?

### RESULTS / FINDINGS 
This is contained in the document labelled 'REPORT ON THE ANALYSIS OF THE DATA SCIENCE JOB DATASET' in this repository.

### CONCLUSIONS
1.	Data science job positions receives higher salaries when offered in companies located in Japan (JP), followed by Mexico (MX), then Germany (DE), US, India (IN), UK and China (CN)
2.	Data science job positions offered in large companies pays higher salaries, followed by medium and then small companies.
3.	The demand for the various data science jobs are almost the same but the most sort-after one is the Data Science job category.
4.	All work settings (Hybrid, In-person and Remote) were preferred in the data science job openings.
5.	Experience level plays little or no role in the salary negotiations for data science job position.

### LIMITATIONS
1.	The job experience level and employment type columns were filled with abbreviations which were not fully understood by me.
2.	The null values, NA’s were not included in the analysis



