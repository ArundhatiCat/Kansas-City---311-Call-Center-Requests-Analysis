

---

# 📊 Kansas City 311 Call Center Requests Analysis

## 🧠 Project Overview

This project focuses on enhancing city responsiveness by analyzing **1.56 million** 311 call center requests submitted by Kansas City residents over a **10-year period**. By leveraging modern data engineering, graph-based modeling, and real-time visualizations, the goal was to uncover actionable insights and optimize city services.

---

## 🎯 Objectives

* Identify trends and inefficiencies in city service delivery.
* Clean and standardize large-scale civic data for meaningful analysis.
* Build real-time, insightful dashboards for stakeholders and city officials.
* Create a graph-based model to uncover hidden relationships in request patterns.

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                     |
| ------------------- | ------------------------------------------- |
| **YData Profiling** | Initial data exploration & profiling        |
| **Talend**          | Data cleaning and ETL pipeline creation     |
| **Neo4j**           | Graph modeling of 311 requests (25M+ edges) |
| **Tableau**         | Real-time interactive dashboards            |
| **Python**          | Scripting & algorithm development           |

---

## 🔍 Key Features

* 🧼 **Data Cleaning with Talend**: Eliminated duplicates, standardized timestamps, normalized location and request types.
* 🧠 **Data Profiling**: Used YData Profiling to detect anomalies, missing values, and skewed distributions.
* 🔗 **Graph Database Modeling**: Imported data into **Neo4j** to model relationships between request types, neighborhoods, and resolution times — over **25 million relationships** captured.
* 📈 **Real-time Dashboards**: Designed dynamic **Tableau dashboards** for:

  * Request distribution by category and time
  * Response time heatmaps
  * Neighborhood-level service performance
  * Trend analysis over the decade

---

## 📌 Impact

* Improved understanding of long-term trends in civic engagement.
* Enabled **data-driven prioritization** of service areas needing attention.
* Helped city officials **monitor performance** and take timely action using **real-time visual insights**.

---

## 🚀 How to Run the Project

> This is a multi-tool pipeline. High-level steps below:

1. **Data Preprocessing**

   * Load and clean raw CSV files using Talend
   * Profile data using `ydata-profiling` in Python

2. **Graph Construction**

   * Run the Neo4j import script to create nodes and edges
   * Visualize and query graph for insights

3. **Dashboard Integration**

   * Connect cleaned dataset to Tableau
   * Build and publish interactive dashboards

---

## 💡 Future Work

* Integrate weather and traffic data for richer context.
* Predict high-traffic service request times using time-series models.
* Apply NLP to analyze request descriptions and improve categorization.

---

## 👩‍💻 Author

**Arundhati Pathrikar**
📧 [pathrikar.ar@northeastern.edu](mailto:pathrikar.ar@northeastern.edu)
🔗 [LinkedIn](https://www.linkedin.com/in/arundhati-rajendra-pathrikar/) | [GitHub](https://github.com/ArundhatiCat)

---

