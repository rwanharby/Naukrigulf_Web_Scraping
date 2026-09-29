# 🔎 Data Engineer Job Listings Web Scraper

## 📌 Project Overview

This project is a web scraping application built with **Python and Selenium** to automatically collect real job listings related to **Data Engineer** positions from **Naukrigulf**.

The scraper dynamically navigates through the first three pages of search results, extracts the required job information, and stores the collected data in a structured **CSV file**.

---

## 🎯 Project Objective

The main objective of this project is to automate the process of collecting and organizing job listing data from a live job portal using Selenium.

The extracted data can be used for further analysis, reporting, or other data processing tasks.

---

## 📊 Data Extracted

For each job listing, the scraper extracts:

- **Job Title**
- **Company Name**
- **Job Location**
- **Required Experience**
- **Full Job Description**

---

## 🛠️ Technologies Used

- **Python**
- **Selenium**
- **Web Scraping**
- **CSV**
- **Data Extraction**

---

## ⚙️ How It Works

The scraping process follows these steps:

1. Open the Naukrigulf website.
2. Search for **Data Engineer** job listings.
3. Navigate dynamically through the first three pages of search results.
4. Open and process the available job listings.
5. Extract the required information from each listing.
6. Organize the extracted data into a structured dataset.
7. Export the final dataset to a **CSV file**.

---
├── data_engineer_jobs.csv
├── README.md
└── requirements.txt
