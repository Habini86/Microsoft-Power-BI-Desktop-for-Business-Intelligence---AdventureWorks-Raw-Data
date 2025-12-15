# AdventureWorks BI

This repository contains a complete Business Intelligence solution for the AdventureWorks dataset, built using Microsoft Power BI. The project demonstrates best practices in data modeling, ETL, and interactive reporting for business analytics scenarios.

## Project Structure

- **AdventureWorks_BI.pbip**  
  Power BI Project file that links all artifacts and configurations.

- **AdventureWorks_BI.Report/**  
  Contains the Power BI report definition, layouts, and visual configurations.

- **AdventureWorks_BI.SemanticModel/**  
  Includes the semantic data model (`model.bim`) with tables, relationships, and data transformations.

- **AdventureWorks Raw Data/**  
  Raw CSV files used as data sources, such as:
  - `AdventureWorks Calendar Lookup.csv`
  - `AdventureWorks Customer Lookup.csv`
  - `AdventureWorks Product Categories Lookup.csv`
  - `AdventureWorks Product Lookup.csv`
  - `AdventureWorks Product Subcategories Lookup.csv`
  - `AdventureWorks Returns Data.csv`
  - `AdventureWorks Sales Data 2020.csv`, `2021.csv`, `2022.csv`, etc.

## Features

- **Data Model:**  
  Star schema with dimension and fact tables, including calendar, customer, product, territory, and sales data.

- **ETL Process:**  
  Power Query (M) scripts for importing, cleaning, and transforming raw CSV data.

- **Report Structure:**  
  Power BI report file is created and ready for visualizations. (No visuals have been added yet.)

- **Custom Theme:**  
  Includes a custom Power BI theme for consistent report styling.

- **Open Source:**  
  Licensed under the MIT License.

> **Note:** The Power BI report structure is set up, but no visuals or DAX measures have been added yet. The project currently focuses on data modeling and ETL.

## Getting Started

1. Clone this repository.
2. Open the `.pbip` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Ensure the raw data CSV files are located in the `AdventureWorks Raw Data/` folder.
4. Refresh the data to load the latest information.
5. Explore and customize the report as needed.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Author:** Habini86  
**Year:** 2025