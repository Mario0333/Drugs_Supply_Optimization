# README: Drugs Supply Chain Dataset

## Overview
This dataset contains synthetic data representing pharmaceutical sales transactions. It includes information about sales type, patient details, specializations, departments, billing details, quantities, costs, and drug-related categories.

## Data Description
The dataset consists of 5000 rows and 14 columns. Below is a description of each column:

| Column Name       | Data Type              | Description |
|------------------|----------------------|-------------|
| Typeofsales      | Nominal, Categorical | Type of sales transaction (Online, Offline, Wholesale, Retail) |
| Patient_ID       | Nominal, Categorical | Unique identifier for patients |
| Specialisation   | Nominal, Categorical | Medical specialization related to the transaction |
| Dept             | Nominal, Categorical | Department handling the transaction (Pharmacy, Surgical, etc.) |
| Dateofbill       | Ordinal, Categorical | Day of the month when the transaction occurred |
| Quantity         | Ratio, Numerical     | Number of drug units sold |
| ReturnQuantity   | Ratio, Numerical     | Number of returned drug units |
| Final_Cost       | Ratio, Numerical     | Final cost of the transaction |
| Final_Sales      | Ratio, Numerical     | Sales amount after any adjustments |
| RtnMRP          | Ratio, Numerical     | Maximum retail price for returned items |
| Formulation      | Nominal, Categorical | Formulation type (Tablet, Capsule, Syrup, Injection, Ointment) |
| DrugName        | Nominal, Categorical | Name of the drug sold |
| SubCat          | Nominal, Categorical | Drug category (Painkiller, Antibiotic, Diabetes, etc.) |
| SubCat1         | Nominal, Categorical | Classification (OTC, Prescription) |

## Usage
This dataset can be used for:
- Pharmaceutical sales analysis
- Demand forecasting for medications
- Customer behavior analysis in medical sales
- Inventory management and optimization

## Notes
- This dataset is synthetically generated and does not contain real patient data.
- Some values are randomly assigned to simulate real-world data variations.
- Dateofbill only represents the day of the month and not full date values.

## License
This dataset is provided for research and educational purposes only. It should not be used for any commercial or medical decision-making purposes.

## Contact
For any inquiries or suggestions, please reach out to the dataset creator.

