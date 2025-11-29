# 🚖 Uber Analytics Dashboard

### 📊 Interactive Power BI Dashboard for Ride-Sharing Insights

![Uber Dashboard Banner](Home-page<img width="1297" height="721" alt="Home page" src="https://github.com/user-attachments/assets/fd8214b6-3324-4c8e-9206-f61380690757" />
.jpg)

## 📖 Project Overview
This project is a comprehensive data visualization dashboard built using **Microsoft Power BI**. It analyzes Uber's ride-sharing data to uncover key insights into booking trends, revenue generation, vehicle utilization, and customer demographics.

The goal of this dashboard is to help stakeholders make data-driven decisions by visualizing ride patterns, cancellation reasons, and high-demand locations.

## 🌟 Key Features

### 1. **Bookings Analysis**
- **Total Bookings Overview:** Tracks Complete vs. Lost bookings (Cancellations/Incomplete rides).
- **Trend Analysis:** Visualizes booking volumes over months and quarters.
- **Vehicle Segmentation:** Breakdowns of bookings by vehicle types (Auto, Bike, Prime Sedan, etc.).

### 2. **Revenue Intelligence**
- **Financial Metrics:** Displays Total Revenue, Booking Value, and Payment Method distribution (UPI, Cash, Credit Card).
- **Revenue by Vehicle:** Identifies which vehicle types contribute most to the bottom line.
- **Customer LTV:** Analyzes revenue contribution by individual customer IDs.

### 3. **Customer & Rider Insights**
- **Rider Demographics:** Segments users into First-time, Regular, and Frequent riders.
- **Cancellation Analysis:** Drills down into reasons for lost bookings (e.g., "Driver asked to change destination," "AC not working").

### 4. **Operational & Location Metrics**
- **Heatmaps:** Identifies top pickup and drop-off locations (e.g., Khanda, Ashram, AIIMS).
- **Time-Slot Analysis:** Pinpoints peak demand hours (e.g., "Evening 6 PM - 9 PM") to optimize driver allocation.

## 📸 Dashboard Visuals

| **Bookings View** | **Revenue View** |
|:---:|:---:|
| ![Bookings Page](Booking-page.jpg) | ![Revenue Page](revenue-page.jpg) |
| *Tracks volume, ride status, and vehicle types* | *Analyzes payment methods and financial performance* |

| **Customer View** | **Vehicle & Riders** |
|:---:|:---:|
| ![Rider Page](Rider-page.jpg) | ![Vehicle Page](vehicle-page.jpg) |
| *Customer segments and cancellation reasons* | *Vehicle performance metrics and utilization* |

## 🛠️ Tools & Technologies Used
- **Power BI Desktop**: For data modeling, DAX calculations, and visualization.
- **Power Query**: For ETL (Extract, Transform, Load) and data cleaning.
- **DAX (Data Analysis Expressions)**: Used for creating custom measures like `Booking_Value`, `Cancellation_Rate`, and `Revenue_Growth`.
- **Figma / Canva**: (Optional) Used for designing the custom background layouts.

## 📂 Dataset
The dataset includes fields such as:
- **Booking ID**: Unique identifier for rides.
- **Status**: Success, Cancelled by Driver, Cancelled by User.
- **Vehicle Type**: Auto, Prime Sedan, Mini, etc.
- **Customer ID**: Unique user identifiers.
- **Revenue/Fare**: Cost of the trip.
- **Location**: Pickup and Drop-off points.

## 🚀 How to Use This Project
1. **Clone the Repo**:
