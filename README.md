# Context
This is a 2017 data set from the University of British Columbia, Canada on lolly preferences during Halloween. The data contains all kinds of horrid inconsistencies that make it hard to analyse. For additional context, the survey originally presented to respondents can be found here: https://www.scq.ubc.ca/wp-content/uploads/2017/10/candyhierarchysurvey2017.pdf 

# The Process
In this project, I use a variety of analysis techniques to polish the data. You'll find four main files in this repository. 
1. A Jupyter notebook containing heavy-handed transforms like unpivoting the data.
2. A T-SQL script for fine-tuning.
3. Three .xlsx files.
- 3.1 The raw data, as downloaded from the University of British Columbia.
- 3.2 The data post-transform, which is then loaded into a database using SSMS.
- 3.3 The final output.
