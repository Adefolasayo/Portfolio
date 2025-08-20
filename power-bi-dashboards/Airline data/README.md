# ✈️ Airline Flight Analytics Dashboard (Power BI)

## 📌 Project Overview
This project explores flight data from **6 airlines across multiple cities** using an interactive **Power BI dashboard**.  
The dashboard provides insights into flight patterns, pricing, and passenger preferences by transforming raw CSV data into meaningful visualizations.

Dataset source: [Kaggle – Airlines Flights Data](https://www.kaggle.com/datasets/rohitgrewal/airlines-flights-data)

---

## 🗂️ Dataset Description
The dataset contains details of individual flights with the following 12 columns:

| Column            | Description |
|-------------------|-------------|
| **index**         | Index of the row |
| **airline**       | Name of the airline |
| **flight**        | Flight code |
| **source_city**   | City where the flight departs |
| **departure_time**| Departure time (Morning, Afternoon, Night, etc.) |
| **stops**         | Number of stops (Direct or Connecting) |
| **arrival_time**  | Arrival time at the destination |
| **destination_city** | City where the flight lands |
| **class**         | Flight class (Economy or Business) |
| **duration**      | Duration of the flight in hours |
| **days_left**     | Number of days left before the departure |
| **price**         | Ticket price |

---

## 📊 Dashboard Features
The Power BI dashboard is designed across **2 pages** with the following highlights:

### **Page 1: Flight Overview**
- KPI cards for:
  - Average Price
  - Average Duration (hrs)
  - Total Number of Flights
  - Minimum Price (cheapest ticket)
- Clustered bar chart: **Flight departures by city and time of day**
- Distribution of flights by stops (direct vs connecting)

### **Page 2: Price Analytics**
- Average ticket price comparisons across:
  - Airlines
  - Flight class (Economy vs Business)
  - Days left before departure
- Route-based price analysis (most expensive vs most popular routes)

---

## 🔑 Key Insights
- **31%** of passengers book Business Class, mainly on *Air India* and *Vistara*.  
- The **Chennai → Bangalore** route has the highest average ticket price.  
- The **Delhi → Mumbai** route is the most frequently traveled.  
- **Late-night flights (<1%)** are the least chosen and also the cheapest.  

---

## 🎨 Design Approach
Inspired by *Igboejesi Chidera’s* dashboard design process:  
- Sketched a **layout plan** before development.  
- Selected a **consistent color theme** to maintain aesthetics.  
- Focused on **data storytelling** for better readability and impact.  

---

## 🛠️ Tools Used
- **Power BI Desktop** – Data cleaning, modeling, and dashboard creation  
- **CSV Dataset** – Imported from Kaggle  

---


## 🚀 Next Steps
- Add **time-series analysis** for flight prices.  
- Integrate **Python** for advanced forecasting models.  
- Expand to a larger dataset for deeper airline trend analysis.  

---

## 👤 Author 
**Adefolasayo Gboyega-Adejuwon**  
- 📧 adetenny9@gmail.com    

---

