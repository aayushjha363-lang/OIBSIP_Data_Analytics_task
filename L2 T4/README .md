## Project Overview

This project explores the mobile application marketplace to gain insights into category trends, pricing strategies, and overall user satisfaction. By analyzing key attributes such as ratings, downloads, and application categories, the study aims to identify patterns that influence app performance and popularity in the market.

## Dataset Description

The dataset contains information about various mobile applications and their market performance indicators, including:

* **App** – The name of the mobile application.
* **Category** – The classification of the app within the marketplace (e.g., Games, Productivity, etc.).
* **Rating** – The average user rating assigned to the application, typically ranging from 1.0 to 5.0.
* **Reviews** – The total number of user reviews submitted for the application.
* **Installs** – The total number of times the application has been downloaded or installed.
* **Type** – Indicates whether the application is **Free** or **Paid**.

## Data Cleaning and Preprocessing

To ensure accurate analysis, several preprocessing steps were performed:

* Removed special characters such as `+`, `,`, and `$` from numerical columns to enable proper numerical computation.
* Addressed missing values in the **Rating** column to maintain dataset consistency.
* Converted relevant columns from object data types to **float** for statistical and mathematical analysis.

## Project Files

* **apps.csv** – The original dataset containing application marketplace data.



