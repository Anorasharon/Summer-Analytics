# 🚗 Dynamic Pricing for Urban Parking Lots

**Capstone Project — Summer Analytics 2025**  
**Hosted by:** Consulting & Analytics Club × Pathway

---

## 📌 Overview

Urban parking spaces are a limited and high-demand resource. Static pricing often leads to inefficiencies like overcrowding or underutilization.  
This project builds a real-time, data-driven dynamic pricing engine for 14 urban parking spaces using machine learning and economic theory to adapt prices based on demand, environment, and competition.

All models are built from scratch using only **NumPy**, **Pandas**, and **Pathway**.

---

## 🧰 Tech Stack

| Component        | Technology          |
|------------------|---------------------|
| Programming      | Python              |
| Data Handling    | Pandas, NumPy       |
| Real-Time Stream | Pathway             |
| Visualization    | Bokeh               |
| Notebook Runtime | Google Colab        |

---

## 🏗️ Architecture Diagram

```mermaid
graph TD
    A[Real-Time Data Stream] --> B[Pathway Stream Processor]
    B --> C[Feature Extraction]
    C --> D1[Model 1: Linear Pricing]
    C --> D2[Model 2: Demand-Based Pricing]
    C --> D3[Model 3: Competitive Pricing]
    D1 --> E[Price Prediction Output]
    D2 --> E
    D3 --> E
    E --> F[Real-Time Bokeh Visualizations]
    E --> G[Optional: Rerouting Suggestion System]
