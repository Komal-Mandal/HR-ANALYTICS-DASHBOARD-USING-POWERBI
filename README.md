# HR-ANALYTICS-DASHBOARD-USING-POWERBI

# 🎯 Goal of the Project

The main goal of this project is to:

Understand why employee attrition is happening,Identify the key reasons behind employees leaving,Analyze patterns like department, salary, job role, overtime, experience, etc.it Helps the company take data-driven decisions to reduce attrition

# 🧹 Step 1: Data Cleaning & Preparation (Power BI – Power Query)

First, I performed data preprocessing in Power BI.

### 1️⃣ Check Data Types

- Go to Transform Data

- Select all columns

- Click Transform → Detect Data Type

- Ensure correct data types (Number, Text, Date, etc.)

 #### Why?
- Because wrong data types affect analysis and calculations.

### 2️⃣ Check Null Values

- Go to View → Column Quality

  ##### It shows:

- Valid

- Error

- Empty (Null values)

- If null values exist:

- Sort the column

- Go to Home → Remove Rows → Remove Top Rows

- Enter number of rows to remove

### 3️⃣ Remove Duplicates

- Right-click on the column

- Click Remove Duplicates

##### Why?
- Duplicate data gives wrong insights.

### 4️⃣ Check Spelling Errors

- Right-click on categorical columns (like Department, Job Role)

- Check unique values

- Make sure spellings are correct (e.g., “Sales” vs “sale”)

##### Why?
- Spelling mistakes create multiple categories incorrectly.

### 5️⃣ Close & Apply

- After cleaning:

- Click Close & Apply

- Load the clean dataset into Power BI for analysis.

### 📊 What We Analyze in Attrition Project

##### We analyze:

- Attrition by Department

- Attrition by Job Role

- Attrition by Salary Level

- Attrition by Overtime

- Attrition by Experience

- Attrition by Age Group

## Dashboard Screenshot:

<img width="577" height="327" alt="image" src="https://github.com/user-attachments/assets/157b053e-8260-44d0-8b45-70f6422edbb0" />
