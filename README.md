# Capstone-Project-Submission
# 🚗 Dynamic Pricing for Urban Parking Lots

## 📌 Overview
This project was developed as a part of the Summer Analytics 2025 Capstone hosted by the Consulting & Analytics Club × Pathway. The objective was to build a dynamic, intelligent, and real-time pricing system for urban parking lots based on demand, capacity, congestion, queue length, and special events.

## 🛠️ Tech Stack
- **Python**
- **Pandas / NumPy** for data processing
- **Pathway** for real-time streaming simulation
- **Bokeh** for visualization
- **Google Colab** for code development

⚙️ Workflow

 Data Preprocessing

 Combined date and time into a single timestamp

 Filtered and cleaned the dataset

Converted to real-time stream using Pathway

 Model 1

Linear price update based on occupancy

 Model 2

Included advanced features like queue length, vehicle type, and congestion

Smoothed demand function and price calculation

Real-Time Visualization

Live plotting with Bokeh to monitor pricing behavior

📊 Key Highlights

 Base price starts at $10

Prices are dynamically adjusted in real time

Normalized demand values ensure smooth transitions

Real-time simulation using pw.demo.replay_csv

📈 Models Implemented
✅ Model 1: Baseline Linear Model

Price increases linearly with occupancy:
price = previous_price + α * (occupancy / capacity)
✅ Model 2: Demand-Based Dynamic Pricing

Price adjusts based on:

 Occupancy Rate

Queue Length

Traffic Condition

Special Day Indicator

 Vehicle Type

📊 Visualizations

Real-time price fluctuations are plotted using Bokeh, based on simulation data streamed with Pathway.
📝 How to Run

Open the Capstone Project Final.ipynb notebook in Google Colab.

Run all cells to simulate data ingestion and pricing logic.

Visualization will be served via Panel and Bokeh.
## 🧠 Project Architecture

```mermaid
graph TD
    A[Dataset] --> B[Data Preprocessing]
    B --> C[Model 1 - Linear Pricing]
    B --> D[Model 2 - Demand-Based Pricing]
    C --> E[Price Output]
    D --> E
    E --> F[Visualization with Bokeh]

