# Predicting Credit Risk 

Credit Risk Prediction is a machine learning project aimed at predicting the likelihood of a borrower defaulting on a loan. This project utilizes a variety of statistical and machine learning models to analyze historical loan data and identify patterns that indicate credit risk. By accurately predicting credit risk, financial institutions can make better lending decisions, minimize defaults, and improve overall financial stability. The original credit dataset for this project in the form provided by Prof. Hofmann, contains categorical/symbolic attributes and classifies people described by a set of attributes as good or bad credit risks.

### There are 20 features and a class predictior with assigned credit risk.
Attribute1: Status of existing checking account
Attribute2: Duration
Attribute3: Credit history
Attribute4: Purpose
Attribute5: Credit amount
Attribute6: Savings account/bonds
Attribute7: Present employment since
Attribute8: Installment rate in percentage of disposable income
Attribute9: Personal status and sex
Attribute10: Other debtors / guarantors
Attribute11: Present residence since
Attribute12: Property
Attribute13: Age
Attribute14: Other installment plans
Attribute15: Housing
Attribute16: Number of existing credits at this bank
Attribute17: Job
Attribute18: Number of people being liable to provide maintenance for
Attribute19: Telephone
Attribute20: foreign worker
class: 1 = Good, 2 = Bad

### Additional Variable Information
'Attribute 1:  (qualitative)      \r\n Status of existing checking account\r\n             A11 :      ... <    0 DM\r\n\t       A12 : 0 <= ... <  200 DM\r\n\t       A13 :      ... >= 200 DM / salary assignments for at least 1 year\r\n               A14 : no checking account\r\n\r\nAttribute 2:  (numerical)\r\n\t      Duration in month\r\n\r\nAttribute 3:  (qualitative)\r\n\t      Credit history\r\n\t      A30 : no credits taken/ all credits paid back duly\r\n              A31 : all credits at this bank paid back duly\r\n\t      A32 : existing credits paid back duly till now\r\n              A33 : delay in paying off in the past\r\n\t      A34 : critical account/  other credits existing (not at this bank)\r\n\r\nAttribute 4:  (qualitative)\r\n\t      Purpose\r\n\t      A40 : car (new)\r\n\t      A41 : car (used)\r\n\t      A42 : furniture/equipment\r\n\t      A43 : radio/television\r\n\t      A44 : domestic appliances\r\n\t      A45 : repairs\r\n\t      A46 : education\r\n\t      A47 : (vacation - does not exist?)\r\n\t      A48 : retraining\r\n\t      A49 : business\r\n\t      A410 : others\r\n\r\nAttribute 5:  (numerical)\r\n\t      Credit amount\r\n\r\nAttibute 6:  (qualitative)\r\n\t      Savings account/bonds\r\n\t      A61 :          ... <  100 DM\r\n\t      A62 :   100 <= ... <  500 DM\r\n\t      A63 :   500 <= ... < 1000 DM\r\n\t      A64 :          .. >= 1000 DM\r\n              A65 :   unknown/ no savings account\r\n\r\nAttribute 7:  (qualitative)\r\n\t      Present employment since\r\n\t      A71 : unemployed\r\n\t      A72 :       ... < 1 year\r\n\t      A73 : 1  <= ... < 4 years  \r\n\t      A74 : 4  <= ... < 7 years\r\n\t      A75 :       .. >= 7 years\r\n\r\nAttribute 8:  (numerical)\r\n\t      Installment rate in percentage of disposable income\r\n\r\nAttribute 9:  (qualitative)\r\n\t      Personal status and sex\r\n\t      A91 : male   : divorced/separated\r\n\t      A92 : female : divorced/separated/married\r\n              A93 : male   : single\r\n\t      A94 : male   : married/widowed\r\n\t      A95 : female : single\r\n\r\nAttribute 10: (qualitative)\r\n\t      Other debtors / guarantors\r\n\t      A101 : none\r\n\t      A102 : co-applicant\r\n\t      A103 : guarantor\r\n\r\nAttribute 11: (numerical)\r\n\t      Present residence since\r\n\r\nAttribute 12: (qualitative)\r\n\t      Property\r\n\t      A121 : real estate\r\n\t      A122 : if not A121 : building society savings agreement/ life insurance\r\n              A123 : if not A121/A122 : car or other, not in attribute 6\r\n\t      A124 : unknown / no property\r\n\r\nAttribute 13: (numerical)\r\n\t      Age in years\r\n\r\nAttribute 14: (qualitative)\r\n\t      Other installment plans \r\n\t      A141 : bank\r\n\t      A142 : stores\r\n\t      A143 : none\r\n\r\nAttribute 15: (qualitative)\r\n\t      Housing\r\n\t      A151 : rent\r\n\t      A152 : own\r\n\t      A153 : for free\r\n\r\nAttribute 16: (numerical)\r\n              Number of existing credits at this bank\r\n\r\nAttribute 17: (qualitative)\r\n\t      Job\r\n\t      A171 : unemployed/ unskilled  - non-resident\r\n\t      A172 : unskilled - resident\r\n\t      A173 : skilled employee / official\r\n\t      A174 : management/ self-employed/\r\n\t\t     highly qualified employee/ officer\r\n\r\nAttribute 18: (numerical)\r\n\t      Number of people being liable to provide maintenance for\r\n\r\nAttribute 19: (qualitative)\r\n\t      Telephone\r\n\t      A191 : none\r\n\t      A192 : yes, registered under the customers name\r\n\r\nAttribute 20: (qualitative)\r\n\t      foreign worker\r\n\t      A201 : yes\r\n\t      A202 : no\r\n'
