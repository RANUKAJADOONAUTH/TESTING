# Rising Tides of Deception: Financial Fraud in Guyana’s Oil & Gas Economy

# Introduction
Guyana discovered significant oil reserves off its coast in 2015. Production began in 2019, particularly in the colossal Stabroek Block under a consortium led by ExxonMobil, along with Hess and China’s CNOOC. Oil revenues have since become a major component of Guyana’s economy.
While oil can fuel development—building infrastructure, improving public services, reducing poverty—there is strong risk that fraud, corruption, and mismanagement will undermine those benefits. Without robust oversight, the very lucrativeness of oil projects can incentivize illicit or semi‑licit behavior (e.g. misreporting, cost inflation, undue political influence, non‑transparent contracting).
This project examines what kinds of financial fraud are increasing in Guyana’s oil & gas sector, with case studies; identifies systemic vulnerabilities; evaluates existing legal and institutional frameworks; and proposes measures to reduce fraud and increase accountability.
Types of Financial Fraud / Malpractice in Guyana Oil & Gas

# Common Types of Financial Fraud in Guyana's Oil Sector
1. Cost Recovery Abuse - Oil companies inflate their expenses to reduce how much profit Guyana gets.
2. Lack of Financial Transparency - Companies don't clearly report how much money they make or owe to Guyana.
3. Corrupt Licensing Practices - Oil licenses are awarded unfairly, often to friends or political allies.
4. Political Elite Capture - Powerful individuals benefit more from oil deals than the general public.
5. Fake Training and Services - Fraudsters offer fake courses or services related to the oil sector.
   
## 📊 Sample Data (STRs)

| Year | Suspicious Transactions | Value (GY$)     |
|------|--------------------------|-----------------|
| 2022 | 107                      | 1.96 Billion    |
| 2023 | 180                      | 153.3 Billion   |

## 🏗️ How to Use

1. Clone the repository
2. Open `index.html` in your browser
3. Customize content and styles as needed

## 📄 License

This project is licensed under the MIT License.



## 📄 License

This project is licensed under the MIT License.

# Content & Explaination
- - Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.
- At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

# Dataset Description
- There're two tables could be merged by ID:

1. Table 1
    1. ID ----------------------- 	Client number 	
    2. CODE_GENDER --------------	Gender 	
    3. FLAG_OWN_CAR -------------	Is there a car 	
    4. FLAG_OWN_REALTY ----------	Is there a property 	
    5. CNT_CHILDREN -------------	Number of children 	
    6. AMT_INCOME_TOTAL ---------	Annual income 	
    7. NAME_INCOME_TYPE ---------	Income category 	
    8. NAME_EDUCATION_TYPE ------ 	Education level 	
    9. NAME_FAMILY_STATUS -------	Marital status 	
    10. NAME_HOUSING_TYPE -------	Way of living 	
    11. DAYS_BIRTH --------------	Birthday ------------------- Count backwards from current day (0), -1 means yesterday
    12. DAYS_EMPLOYED -----------	Start date of employment --- Count backwards from current day(0). If positive, it means the person currently unemployed.
    13. FLAG_MOBIL --------------	Is there a mobile phone 	
    14. FLAG_WORK_PHONE ---------	Is there a work phone 	
    15. FLAG_PHONE --------------	Is there a phone 	
    16. FLAG_EMAIL --------------	Is there an email 	
    17. OCCUPATION_TYPE ---------	Occupation 	
    18. CNT_FAM_MEMBERS ---------	Family size

       "                  High         Low        Open       Close     Volume  \\\n",

# Table showing the increase in Fraud of Small Businesses  
   "Date                                                                    \n",
       "2020-02-20  118.110001  116.860001  117.209999  117.690002  5022900.0   \n",
       "2020-02-21  118.750000  117.309998  117.440002  118.580002  6242100.0   \n",
       "2020-02-24  118.459999  115.949997  117.459999  116.320000  6616000.0   \n",
       "2020-02-25  117.070000  114.050003  116.349998  114.389999  7764300.0   \n",
       "2020-02-26  115.169998  113.650002  114.699997  113.779999  6673300.0   \n",
       "\n",

   2. Table 2

    1. ID ---------------	Client number 	
    2. MONTHS_BALANCE --- 	Record month ---- The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on
    3. STATUS -----------	Status ---------- 0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month
    
 # Approach for Problem Solving
1. Understanding the Problem
2. Downloading the Dataset
3. Importing necessary Dependencies
4. Exploratory Data Analysis
5. Data Pre-Processing
6. Feature Engineering
7. Building the Model
8. Evaluation of the Model
9. End Results

# End Results
- After all the possible experiments Maximum accuracy of **92.59%** is achieved by using **XGBoosting Classifier**.
- Here our model correctly predicts whether we should approve Credit Card for Customer or not.
guyana-oil-fraud/
│
├── index.html
├── styles.css
├── images/
│   └── (optional images for charts or illustrations)
├── README.md
└── tables/
    └── data_tables.md
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Financial Fraud in Guyana's Oil & Gas Economy</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header>
    <h1>Financial Fraud in Guyana's Oil & Gas Economy</h1>
    <p>An overview of rising concerns, causes, cases, and solutions.</p>
  </header>

  <section>
    <h2>Introduction</h2>
    <p>Guyana has become one of the world’s fastest-growing economies due to large oil discoveries. However, with this new wealth, the country has seen a rise in financial fraud and corruption in its oil and gas sector...</p>
  </section>

  <section>
    <h2>Types of Financial Fraud</h2>
    <table>
      <thead>
        <tr>
          <th>Type of Fraud</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Cost Recovery Abuse</td>
          <td>Inflating operational costs to reduce profit share owed to Guyana.</td>
        </tr>
        <tr>
          <td>Lack of Transparency</td>
          <td>Failure to publish clear financial statements and oil revenue data.</td>
        </tr>
        <tr>
          <td>Corrupt Licensing</td>
          <td>Political favoritism in awarding oil blocks and contracts.</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Evidence of Growing Fraud</h2>
    <p>According to Guyana's FIU, the number of suspicious transactions increased by 68% between 2022 and 2023, with their value growing over 70-fold...</p>

    <table>
      <thead>
        <tr>
          <th>Year</th>
          <th>Number of STRs</th>
          <th>Value (GY$)</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2022</td>
          <td>107</td>
          <td>1.96 Billion</td>
        </tr>
        <tr>
          <td>2023</td>
          <td>180</td>
          <td>153.3 Billion</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Recommendations</h2>
    <ul>
      <li>Update legal and regulatory frameworks.</li>
      <li>Publish all oil contracts and payments online.</li>
      <li>Strengthen capacity of oversight institutions.</li>
      <li>Protect whistleblowers and investigative journalists.</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Guyana Oil Fraud Report | Built for educational purposes</p>
  </footer>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f8f8f8;
  color: #333;
}

header, footer {
  background-color: #004d66;
  color: white;
  padding: 20px;
  text-align: center;
}

section {
  padding: 20px;
  background: white;
  margin: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

h1, h2 {
  color: #004d66;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin: 15px 0;
}

table, th, td {
  border: 1px solid #ccc;
}

th, td {
  padding: 10px;
  text-align: left;
  background-color: #fdfdfd;
}

thead {
  background-color: #e0f7fa;
}
# Financial Fraud in Guyana's Oil and Gas Economy

This project explores the rise of financial fraud in Guyana's oil and gas industry, looking at the causes, examples, evidence, and proposed solutions. The project is built as a static website using HTML/CSS and designed for educational, journalistic, or civic engagement purposes.

## 🔍 Features

- Clean HTML layout with structured sections
- Styled tables showing key fraud statistics
- Recommendations for legal and institutional reforms
- Easy to customize or expand

## 📊 Sample Data (STRs)

| Year | Suspicious Transactions | Value (GY$)     |
|------|--------------------------|-----------------|
| 2022 | 107                      | 1.96 Billion    |
| 2023 | 180                      | 153.3 Billion   |


