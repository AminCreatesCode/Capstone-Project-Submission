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

## 🧠 Project Architecture

```mermaid
graph TD
    A[Dataset] --> B[Data Preprocessing]
    B --> C[Model 1 - Linear Pricing]
    B --> D[Model 2 - Demand-Based Pricing]
    C --> E[Price Output]
    D --> E
    E --> F[Visualization with Bokeh]
