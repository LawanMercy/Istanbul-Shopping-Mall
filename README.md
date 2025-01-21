# Istanbul Shopping Mall Analysis
![image](https://github.com/user-attachments/assets/f2d43fe6-fe2c-4b9a-b9bb-dca22515d7e5)
## Introduction
The dataset used for this final project is for the “Istanbul Shopping Malls”. Its columns consist of revenue, payment methods, gender, shopping malls, etc. This dataset consists of approximately 90,000 plus data. The tools used to accomplish this project are MS Excel and Power BI. The dataset was cleaned before any analysis was carried out.
This dataset was provided by our instructor for our final project. I got my hands dirty with this dataset to practice my skills of data cleaning, analysis and visualization.

## Data cleaning and Preparation
- There are no duplicates found in the dataset and columns with nulls were deleted.
- All column headings were changed using proper case.
- The misspelt word under the gender column were replaced “Malle” with “Male”.
- The misspelt words under the category column were all replaced.
- The misspelt words under the Payment Method column were replaced “kredit Car” with “Credit Card”.
- The Invoice Date format was changed to a short date to have a consistent date format.
- The shopping mall column contents contains empty spaces, it was rectified by using the trim function.

### Power BI Concepts Applied:
- Dax Concepts: Calculated colums, Custom Columns, Year(),Month(), Day(), IF().
- Data Modeling: Star Schema (*:1)
### Excel Concepts Applied:
- Revenue =[@Quantity]*[@Price]

