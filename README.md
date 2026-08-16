# 🏥 Distribution of Medical Equipment Dashboard

> Interactive Power BI dashboard for analyzing the distribution of medical equipment.

---

## 1. Problem

Medical equipment distribution involves multiple dimensions such as equipment type, destination, quantity, and distribution location. Without a centralized analytical view, it can be difficult to:

* Monitor how medical equipment is distributed.
* Identify distribution patterns across locations.
* Compare equipment distribution between different areas or categories.
* Detect concentration or imbalance in the distribution process.
* Provide a clear overview for operational and management decision-making.

The goal of this project is to build an **interactive business intelligence dashboard** that transforms medical equipment distribution data into a clear and accessible analytical view.

---

## 2. Dataset

The project uses a medical equipment distribution dataset together with a mapping file:

```text
Mapping_Distribution.csv
```

The mapping data supports the transformation of distribution information into a more meaningful geographical and analytical representation.

### Dataset Dimensions

The analysis focuses on distribution-related attributes such as:

* Medical equipment
* Distribution quantity
* Distribution location
* Destination/region
* Equipment categories
* Geographic mapping information

> **Note:** The dashboard is intended for analytical and visualization purposes. The dataset should not be interpreted as real-time medical inventory or clinical information.

---

## 3. Method

The project follows a **Business Intelligence (BI) workflow** implemented in Power BI.

### Data Preparation

The data is prepared and structured before visualization to ensure that the distribution information can be analyzed consistently.

The general workflow is:

```text
Raw Distribution Data
        │
        ▼
Data Preparation
        │
        ▼
Mapping & Transformation
        │
        ▼
Semantic Model
        │
        ▼
DAX Measures
        │
        ▼
Power BI Report
        │
        ▼
Interactive Dashboard
```

### Analytical Approach

The dashboard applies:

1. **Data transformation**
   Preparing distribution data for analysis.

2. **Data modeling**
   Organizing the dataset into a Power BI semantic model.

3. **Measure creation**
   Creating analytical measures for distribution analysis.

4. **Geographical mapping**
   Connecting distribution information with geographic mapping data.

5. **Interactive filtering**
   Allowing users to explore the data by relevant dimensions.

6. **Data visualization**
   Presenting distribution patterns through charts, cards, and maps.

---

## 4. Results

The dashboard provides a consolidated analytical view of medical equipment distribution.

The analysis enables users to:

* Understand the overall distribution of medical equipment.
* Compare distribution across different locations.
* Identify areas with relatively higher or lower distribution activity.
* Analyze the composition of distributed equipment.
* Explore distribution patterns through interactive filters.
* Support operational discussions using a centralized visual report.

The main value of the dashboard is not only the presentation of individual numbers, but the ability to **explore relationships between equipment, quantity, and distribution location** within a single analytical interface.

---

## 5. Visualization

The Power BI report provides an interactive dashboard for exploring medical equipment distribution.

### Dashboard Components

The visualization is designed around several analytical perspectives:

| Visualization                | Purpose                                             |
| ---------------------------- | --------------------------------------------------- |
| 📊 KPI Cards                 | Provide high-level distribution metrics             |
| 📈 Charts                    | Compare distribution across categories or locations |
| 🗺️ Geographic Visualization | Analyze distribution by geographic area             |
| 📋 Tables                    | Provide detailed distribution information           |
| 🎛️ Slicers                  | Enable interactive filtering and exploration        |

### Dashboard Concept

```text
┌──────────────────────────────────────────────────────┐
│        MEDICAL EQUIPMENT DISTRIBUTION                │
├──────────────┬──────────────┬────────────────────────┤
│ Total        │ Equipment    │ Distribution           │
│ Distribution │ Categories   │ Locations              │
├──────────────┴──────────────┴────────────────────────┤
│                                                      │
│             📊 Distribution Analysis                 │
│                                                      │
├──────────────────────────┬───────────────────────────┤
│                          │                           │
│    🗺️ Distribution Map   │   📈 Equipment Analysis  │
│                          │                           │
├──────────────────────────┴───────────────────────────┤
│                                                      │
│              📋 Detailed Distribution                │
│                                                      │
└──────────────────────────────────────────────────────┘
```

The interactive nature of Power BI allows users to filter one visualization and immediately explore the corresponding changes across other visuals.

---

## 6. Conclusion

The **Distribution of Medical Equipment Dashboard** demonstrates how Power BI can be used to transform distribution data into an interactive business intelligence solution.

By combining data preparation, mapping, semantic modeling, analytical measures, and interactive visualization, the dashboard provides a structured way to understand medical equipment distribution.

The project can serve as a foundation for further development, including:

* Distribution trend analysis
* Regional performance comparison
* Equipment demand analysis
* Inventory and stock monitoring
* Distribution efficiency metrics
* Time-series analysis
* Additional geographic insights

Ultimately, the dashboard helps move the analysis from **raw distribution records to a visual, decision-oriented perspective**.

---

## 7. Technologies

### Core Technology

* **Microsoft Power BI** — Data modeling, DAX, analytics, and dashboard development
* **Power BI Project (`.pbip`)** — Version-controlled Power BI project structure
* **Power BI Semantic Model** — Data modeling and analytical layer
* **Power BI Report** — Dashboard and visualization layer
* **CSV** — Mapping and supporting data source
* **Git & GitHub** — Version control and project management

### Project Structure

```text
distribution-of-medical-equip-dashboard/
│
├── Medical Equipment Distribution Dashboard.Report/
│   └── Power BI Report files
│
├── Medical Equipment Distribution Dashboard.SemanticModel/
│   └── Semantic model files
│
├── Mapping_Distribution.csv
│
└── Medical Equipment Distribution Dashboard.pbip

```

The repository uses the Power BI Project structure alongside the traditional `.pbix` file, making the report and semantic model components easier to manage in a version-controlled development workflow.

---

## 📌 Project Information

**Project:** Distribution of Medical Equipment Dashboard
**Author:** [Ahmed Lubis](https://github.com/ahmedlubis)
**Platform:** Power BI
**Repository:** [distribution-of-medical-equip-dashboard](https://github.com/ahmedlubis/distribution-of-medical-equip-dashboard)

---

## ⭐ Purpose

This project is part of a **Business Intelligence / Data Analytics portfolio**, demonstrating the use of Power BI to transform operational distribution data into an interactive analytical dashboard.

If you find this project useful, consider giving the repository a ⭐.
