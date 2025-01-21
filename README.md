# Istanbul Shopping Mall Analysis
![image](https://github.com/user-attachments/assets/f2d43fe6-fe2c-4b9a-b9bb-dca22515d7e5)
## Introduction
The dataset used for this final project is for the “Istanbul Shopping Malls”. Its columns consist of revenue, payment methods, gender, shopping malls, etc. This dataset consists of approximately 90,000 plus data. The tools used to accomplish this project are MS Excel and Power BI. The dataset was cleaned before any analysis was carried out.
This dataset was provided by our instructor for our final project. I got my hands dirty with this dataset to practice my skills of data cleaning, analysis and visualization.

## Business Case
- Can we see the most preferred payment method?
- How much revenue can we boast of?
- Can we see sales trend for the past years?
- Which gender patronizes us the most?
- Which shopping mall generates the highest revenue?
- How many quantities have we sold so far?
- How many categories do we have?
- How many shopping malls do we have?
- If possible, can we see out top 5 loyal customers?

## Data cleaning and Preparation
- There are no duplicates found in the dataset and columns with nulls were deleted.
- All column headings were changed using proper case.
- The misspelt word under the gender column were replaced “Malle” with “Male”.
- The misspelt words under the category column were all replaced.
- The misspelt words under the Payment Method column were replaced “kredit Car” with “Credit Card”.
- The Invoice Date format was changed to a short date to have a consistent date format.
- The shopping mall column contents contains empty spaces, it was rectified by using the trim function.

#### Power BI Concepts Applied:
- Dax Concepts: Calculated colums, Custom Columns, Year(),Month(), Day(), IF().
- Data Modeling: Star Schema (*:1)
#### Excel Concepts Applied:
- Revenue =[@Quantity]*[@Price]

### Modelling
Automatically derived relationship are adjusted to remove and replace unwanted relationships with the required.
![MODEL](https://github.com/user-attachments/assets/a2a9079e-39de-4723-9ec7-1a719fb558b6)


### Dashboard
![POWERBI ISTANBUL DASHBOARD](https://github.com/user-attachments/assets/64809199-234a-4473-b22e-ab407a22df8c)
The dashboards provide detailed analysis of Istanbul's shopping mall performance, revealing revenue trends, customer demographics, and payment preferences, etc.

- **Revenue Trends and Distribution:** The malls generate 251,505,794.25₺ in revenue, with year-on-year increases from 2021 to 2023, indicating strong consumer spending growth. Monthly sales trends show seasonality, allowing mall managers to optimize operations and promotions during high-traffic periods.
- **Payment Methods:** Customers' payment preferences are primarily credit card transactions, followed by cash and debit card payments, indicating the need for efficient processing systems and loyalty programs.
- **Gender Distribution:** There is nearly a balanced gender distribution among shoppers, with a slight male skew. Retailers should offer diverse products and services to cater to both genders
- **Individual Mall Performances:** Among the listed malls, the data underscores varying levels of success. The data shows malls' success varies, with high-performing ones like Forum Istanbul and Istinye Park generating substantial revenues, while those with lower revenues may need revitalization.

Additionally, for the Power BI, Dax functions were used to define custom calculations for Calculated Columns, Measures, Calculated Tables, the CY (Current Year), PY (Previous Year) and YoY (Year Over Year), etc.

### Recommendations
- **Optimize Seasonal Strategies:** Malls should implement targeted marketing campaigns to boost promotions during high-revenue months and counter sales dips during slower periods due to seasonal sales fluctuations.
- Investing in secure and seamless payment systems, especially for credit card usage, this can significantly enhance the shopping experience.
- Malls can enhance their offerings and advertising strategies by considering gender-based preferences to better cater to their audience.
- **Benchmarking and Resurgence:** Low-performing malls can improve by benchmarking against successful ones and implementing best practices like improved tenant curation or enhanced customer experiences.

