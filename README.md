# 🏬 Investigate Hotel Business using Python

**Tool** : Jupyter Notebook  
**Programming Language** : Python  
**Libraries** : Pandas, NumPy  
**Visualization** : Matplotlib, Seaborn  
**Dataset**: fact_aggregate_bookins.csv, fact_bookings.csv, dim_date.csv, dim_hotels.csv, dim_room.csv

## Table of Contents

 - [STAGE 0: Problem Statement](#-stage-0-problem-statement)
      - [Introduction](#Introduction)
      - [Business Questions](#business-questions)
      - [Objective](#business-questions)
  - [STAGE 1: Data Preprocessing & Exploration](#-stage-1-data-exploration)
      - [Data Overview](#data-overview)
      - [Data Assessment](#data-assessment)
  - [STAGE 2: Data Analysis](#-stage-2-data-Analysis)
      - [Monthly Hotel Booking Analysis Based on Hotel Type](#1-monthly-hotel-booking-analysis-based-on-hotel-type)
      - [Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates](#2-impact-analysis-of-stay-duration-on-hotel-bookings-cancellation-rates)
      - [Impact Analysis of Lead Time on Hotel Bookings Cancellation Rates](#3-impact-analysis-of-lead-time-on-hotel-bookings-cancellation-rates)
  - [STAGE 3: Summary and Recommendations](#-stage-5-summary-and-recommendations)


## 📂 STAGE 0: Problem Statement

### Introduction

Analyzing business performance is crucial for companies striving for success. Through thorough analysis, businesses can uncover their strengths, weaknesses, and areas for improvement. In the hospitality industry, understanding customer behavior is particularly vital. By gaining insights into what drives customers to make hotel reservations, companies can identify key influencing factors. Additionally, they can pinpoint which products or services are underperforming in the market. This knowledge enables businesses to refine their strategies, enhance customer experiences, and work towards achieving long-term goals.


### Business Questions
- What is revenue realized per hotel type?
- What is average rating per city?
- What is month by month revenue?

### Objective <br>

Create data-based visualizations as insights for the hotel business

----
## 📂 STAGE 1: Data Preprocessing & Exploration

### Data Overview

The dataset consist of 5 different data set.

### Data Assessment
Data assessment is a critical step to ensure that the data used for further analysis is accurate and reliable. Here’s a breakdown of the essential tasks involved in this process:
  - Checking for null or missing values ​​in data
  - Check for duplication of data
  - Perform data type and value consistency
  - Check for outliers or unusual data


Table 1 - Assessment Data Results
| Data Assessment | Finding | Handling |
| -------- | -------- | -------- |
| Missing values | There are null values ​​for `ratings_given`,`no_booking` | - `ratings_given`: filled by calculating average indicating the rating given is between 1 to 5 <br>- `no_booking`: filled negative values with 0, indicating the no booking is been done. |

----
## 📂 STAGE 2: Data Analysis

As the dataset needs to cleaned as it contain missing value, negative value and null values which need to be replaced or removed.
And after cleaning we have performed the transformation on  the cleaned data.

Now we will do analysis in order to find the out the trend for revenue, bookings and type of hotel. This analysis can help companies to better understand their customer and market needs which will help them to
improve operational efficiency and optimzie the revenue. <br>

![image](https://github.com/user-attachments/assets/f085fcf8-c036-4a5c-89f0-536064eb231a)

<div align="center">
  <img src="https://github.com/user-attachments/assets/f085fcf8-c036-4a5c-89f0-536064eb231a" alt="Image Description" />
</div>
<p align = 'center'>
  
Figure 1 — Pie chart of revenue realized per booking platform

The provided pie chart offers a visual representation of the distribution of hotel booking revenue realized per booking platform. A careful examination of the chart reveals that the "others" category accounts for the most substantial portion of the total revenue, suggesting a significant market share held by smaller, less prominent platforms or a diverse range of booking channels. Following closely behind is "makeyourtrip," indicating its strong position in the hotel booking industry.

The remaining segments of the pie chart showcase the contributions of "logtrip," "direct online," and "journey," each representing a notable share of the overall revenue. These platforms likely employ distinct strategies to attract customers and generate bookings, such as competitive pricing, exclusive deals, or targeted marketing campaigns.

"Direct offline" and "tripster" occupy relatively smaller portions of the chart, suggesting that traditional offline booking methods and specialized platforms catering to niche markets or specific traveler demographics may have a less significant impact on the overall hotel booking landscape.

In conclusion, the pie chart provides valuable insights into the competitive dynamics of the hotel booking industry. The dominance of the "others" category highlights the fragmentation and diversity of the market, while the presence of established platforms like "makeyourtrip" underscores the ongoing competition for market share. Understanding these trends can inform strategic decisions for both hoteliers and booking platforms seeking to optimize their revenue generation and customer acquisition efforts.


----

## 📂 STAGE 3: Summary and Recommendations
<br>

