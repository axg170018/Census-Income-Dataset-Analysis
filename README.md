# Census-Income-Dataset-Analysis
The dataset used in this project has 199,523 records and a binomial label indicating a salary of &lt;50K or >50K USD. 94% of the records in the dataset have a class label of &lt;50K. The data has been divided into a training set containing 133,680 records and a test dataset containing 65,843 records. 

If the notebook is not able to load then you can go to this link to view the notebook:
https://nbviewer.jupyter.org/github/axg170018/Census-Income-Dataset-Analysis/blob/master/BUAN6340.004.06.project%20code.ipynb


The dataset has been added here as well along with a detailed report of our findings and which model we choose as our best model.

 This data was extracted from the census bureau database found at
| http://www.census.gov/ftp/pub/DES/www/welcome.html
| Donor: Terran Lane and Ronny Kohavi
|        Data Mining and Visualization
|        Silicon Graphics.
|        e-mail: terran@ecn.purdue.edu, ronnyk@sgi.com for questions.
|
| The data was split into train/test in approximately 2/3, 1/3
| proportions using MineSet's MIndUtil mineset-to-mlc.
|
| Prediction task is to determine the income level for the person
| represented by the record.  Incomes have been binned at the $50K
| level to present a binary classification problem, much like the
| original UCI/ADULT database.  The goal field of this data, however,
| was drawn from the "total person income" field rather than the
| "adjusted gross income" and may, therefore, behave differently than the
| orginal ADULT goal field.
|
