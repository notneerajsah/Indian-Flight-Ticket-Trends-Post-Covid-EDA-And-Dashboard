# Indian Flight Ticket Trends: Post-Covid EDA & Dashboard 

## Overview 🎯

This project is an **Exploratory Data Analysis (EDA)** on Indian domestic flight ticket prices post-Covid-19. With global events and rising ATF prices, ticket costs have fluctuated significantly.

The goal is to analyze **factors affecting ticket prices**, such as airline, class, flight duration, stops, and booking timing, and to answer questions like:

* How many flights are available across India?
* How do prices vary across airlines and classes?
* What is the optimal time to book tickets?

**Project Notebook:** [Indian Flight Fare Analysis Exploratory Study.ipynb](./Indian%20Flight%20Fare%20Analysis%20Exploratory%20Study.ipynb)

---

## Dataset 📊

* **Source:** [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)
* **Records:** 300,261 | **Features:** 11 | **Duration:** 50 days (Feb–Mar 2022)
* Covers flights between India’s **top 6 metro cities**, including Economy & Business classes

**Key Features:**

* Airline, Flight, Source City, Destination City
* Departure & Arrival Time, Stops, Class, Duration
* Days Left (booking to travel), Price (target variable)

---

## Power BI Dashboard 📈

Visualize ticket price trends and patterns using the **Power BI Dashboard**:
[Dashboard on Indian Flight Fares.pdf](./Dashboard%20on%20Indian%20Flight%20Fares.pdf)
[Flight Fare Dashboard-PowerBi.pbix](./Flight%20Fare%20Dashboard-PowerBi.pbix)

**Dashboard Highlights:**

* Compare ticket prices across airlines, cities, and classes
* Analyze price trends with respect to stops and flight duration

---

## Key Insights 💡

* **Cheapest Airlines:** Economy → Air Asia | Business → Air India
* **Booking Timing:** 3–7 weeks in advance is optimal; last-minute tickets can sometimes be cheaper
* **Price vs Duration:** Prices generally rise with duration (~20 hrs peak), then slightly drop due to outliers
* **Stops & Timing:** More stops → higher ticket price; late-night departures and early-morning arrivals are cheapest
* **City Trends:** Delhi → cheapest flights | Hyderabad → most expensive
