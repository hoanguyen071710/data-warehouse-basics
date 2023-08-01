## 1. Definition
- Database used and optimized for analytical purposes
  - User friendly
  - Fast query performance
  - Centralized and consistent
  - Enable data analysis
- Bring all relevant data into a centralized location (ETL)
  - Extract, Load, Transform
  - E: So that we don't use production/backend resource when running query, which slow down system
  - T: Configure into the same structure to be able to work with
  - L: Load into centralized location (DW)
  - Must be done consistently and repeatedly

## 2. Data lake vs Data warehouse
|            | Data lake           | Data warehouse            |
|------------| ------------------- |---------------------------|
|Data        | Raw                 | Processed/Transform       |
|Technologies| Big Data            | Databases                 |
|Structure   | Unstructured        | Structured                |
|Usage       | Not defined yet     | Specific and ready to use |
|Users       | Data Scientist      | Business Users, IT        |
|            | higher skills to use| user-friendly             |
