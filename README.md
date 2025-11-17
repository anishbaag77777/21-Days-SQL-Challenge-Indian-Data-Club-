# 📌 21 Days SQL Challenge -Indian Data Club

The 21 Days SQL Challenge organized by Indian Data Club to focus on strengthening SQL skills through daily queries

# 📘 Overview

The SQL Challenge by **Indian Data Club** is a 21-day interactive learning series where each day focuses on a unique SQL concept.
Every day introduces a new real-world question, encouraging participants to explore, practice, and apply SQL concepts to solve practical business problems.
This project contains my daily solutions, learnings, and insights from the challenge, covering topics from basic SELECT queries to advanced analytical functions, all practiced using a Hospital Management Dataset in MySQL Workbench.

The dataset includes four key tables:

• **Patients**

• **Services_Weekly**

• **Staff**

• **Staff_Schedule**


These tables helped simulate realistic scenarios involving patient care, hospital operations, staffing, and service analytics.

# 🎯 Objectives

Strengthen SQL fundamentals through consistent daily practice.

Solve real-world hospital data queries and optimize SQL logic.

Understand data aggregation, filtering, joins, subqueries, and analytical functions in depth.

Build a habit of writing, testing, and debugging SQL queries effectively.

Develop hands-on experience with relational datasets and healthcare domain analysis.

# 📂 Project Structure

Each folder/day includes:

✅ The SQL query for that day’s problem

✅ A brief explanation of the logic used

✅ Sample outputs or screenshots (where applicable)

✅ Key learnings from the day’s topic

# 🛠 Tools & Environment

• **Database Engine**: MySQL

• **Tool Used**: MySQL Workbench

# 📊 Dataset Used — Hospital Data

 • **Patients**
 
    patient_id VARCHAR(50) PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    arrival_date DATE,
    departure_date DATE,
    service VARCHAR(50),
    satisfaction INT

• **Services_Weekly**

    week INT,
    month INT,
    service VARCHAR(50),
    available_beds INT,
    patients_request INT,
    patients_admitted INT,
    patients_refused INT,
    patient_satisfaction INT,
    staff_morale INT,
    event VARCHAR(100)

• **Staff**

    staff_id VARCHAR(50) PRIMARY KEY,
    staff_name VARCHAR(100),
    role VARCHAR(50),
    service VARCHAR(50)

• **Staff_Schedule**

    week INT,
    staff_id VARCHAR(50),
    staff_name VARCHAR(100),
    role VARCHAR(50),
    service VARCHAR(50),
    present TINYINT(1),
    FOREIGN KEY (staff_id) REFERENCES staff(staff_id)


# 🚀 What I Gained from This Challenge

• Taking part in this challenge has enabled me to:

• Strengthen my practical SQL skills and overall confidence in writing queries.

• Understand how to structure queries more efficiently and troubleshoot errors effectively.

• Use SQL to solve realistic, scenario-based problems from a business and data perspective.

• Develop a regular habit of analyzing data and approaching problems with a logical mindset.






