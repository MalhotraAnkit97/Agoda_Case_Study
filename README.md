# Agoda Booking Analysis: A Data-Driven Case Study

<img width="681" height="677" alt="image" src="https://github.com/user-attachments/assets/f4c3fcf1-3b8a-453e-90b7-f434723a36d6" />


## 📖 Overview

This project presents an in-depth analysis of hotel booking data from the online travel agency, Agoda. The goal is to uncover actionable insights into customer booking behaviors, accommodation performance, and seasonal trends across five different cities. By exploring patterns in booking windows, pricing, and accommodation preferences, this case study aims to provide data-driven recommendations for marketing and revenue management strategies.

---

## 📊 The Dataset

The analysis is based on a comprehensive dataset (`Case_Study_Urgency_Message_Data.xlsx`) containing thousands of booking records. The data is segmented into five distinct cities (City A, B, C, D, E) and includes the following key attributes:

* **ADR_USD**: Average Daily Rate in USD.
* **hotel_id**: Unique identifier for each hotel.
* **city_id**: Identifier for the city where the hotel is located.
* **star_rating**: The star rating of the accommodation.
* **accommodation_type_name**: The type of property (e.g., Hotel, Resort, Hostel).
* **chain_hotel**: A boolean indicating if the hotel is part of a chain.
* **booking_date**: The date the booking was made.
* **checkin_date**: The date of check-in.
* **checkout_date**: The date of check-out.

---

## 🔬 Key Analysis & Findings

The project explores several dimensions of the booking data, leading to the following insights:

### 1. Booking Window Analysis
We calculated the **Booking Gap** (the number of days between the booking date and the check-in date) to understand customer planning horizons.
* **Key Finding**: A significant percentage of bookings occur with a short lead time, highlighting the importance of last-minute availability and pricing strategies.

### 2. Accommodation Performance
The analysis breaks down booking volume, average price, and length of stay by accommodation type.
* **Key Finding**: While hotels dominate booking volume, resorts command a much higher average daily rate (ADR). Hostels and Guest Houses serve a distinct budget-conscious segment with shorter booking gaps.

### 3. Seasonal Trends
By analyzing booking and check-in dates, we identified the busiest months and quarters.
* **Key Finding**: The fourth quarter (Q4), particularly **October and November**, emerges as the peak booking season across most cities, suggesting a prime window for marketing campaigns.

### 4. Star Rating and Hotel Type
We compared the performance of chain vs. non-chain hotels and analyzed trends across different star ratings.
* **Key Finding**: Higher-star hotels tend to have longer booking gaps and significantly higher ADRs. Chain hotels show different booking patterns compared to independent properties.

---

## 🛠️ Tools & Libraries

This analysis was conducted using Python in a Jupyter Notebook environment. The core libraries used are:

* **Pandas**: For data manipulation and wrangling.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For static data visualization.
* **Plotnine**: For creating ggplot-style declarative visualizations.

---

## 🚀 How to Run this Project

To replicate this analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/agoda-booking-analysis.git](https://github.com/your-username/agoda-booking-analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd agoda-booking-analysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn plotnine openpyxl
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  **Open the main analysis file:**
    `Agoda_case_study_final_code.ipynb` and run the cells.
