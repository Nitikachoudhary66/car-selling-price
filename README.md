<img width="920" alt="image" src="https://github.com/user-attachments/assets/5c3aefe7-7908-4664-8761-461f5d94211b" />![GitHub repo size](https://img.shields.io/github/repo-size/Nitikachoudhary66/car-selling-price?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Nitikachoudhary66/car-selling-price?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Nitikachoudhary66/car-selling-price?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Nitikachoudhary66/car-selling-price?color=red&style=plastic)

# Car Selling Price Prediction


## Table of Contents

1. [Objective](#objective)  
2. [Quick Demo](#quick-demo)  
3. [Dataset Preview](#dataset-preview)  
4. [Description of Variables in the Dataset](#description-of-variables-in-the-dataset)  
5. [Directory Structure](#directory-structure)  
6. [Installation](#installation)  
7. [Technologies Used](#technologies-used)  

---

### Objective
The goal of this project is to predict the selling price of used cars based on various features such as the car's present price, kilometers driven, ownership, fuel type, seller type, and transmission type. The dataset used is sourced from Kaggle and contains information about used cars listed on the [CarDekho website](https://www.cardekho.com).

---

### Quick Demo
![demo_gif](https://github.com/Nitikachoudhary66/car-selling-price/blob/main/demo.gif)

Using this project, users can predict the selling price of a car by filling out a form in the UI. The prediction result will be displayed directly on the interface.

---
## UI Screenshots
<img width="920" alt="image" src="https://github.com/user-attachments/assets/233ef620-e6fd-46cb-a605-d4d0599a4543" />



### Dataset Preview
Below is a preview of the first five rows of the dataset:

|   | Car_Name | Year | Selling_Price | Present_Price | Kms_Driven | Fuel_Type | Seller_Type | Transmission | Owner |
|---|----------|------|---------------|---------------|------------|-----------|-------------|--------------|-------|
| 0 | ritz     | 2014 | 3.35          | 5.59          | 27000      | Petrol    | Dealer      | Manual       | 0     |
| 1 | sx4      | 2013 | 4.75          | 9.54          | 43000      | Diesel    | Dealer      | Manual       | 0     |
| 2 | ciaz     | 2017 | 7.25          | 9.85          | 6900       | Petrol    | Dealer      | Manual       | 0     |
| 3 | wagon r  | 2011 | 2.85          | 4.15          | 5200       | Petrol    | Dealer      | Manual       | 0     |
| 4 | swift    | 2014 | 4.60          | 6.87          | 42450      | Diesel    | Dealer      | Manual       | 0     |

---

### Description of Variables in the Dataset
- **Car_Name**: Name of the car.
- **Year**: Year the car was purchased.
- **Selling_Price**: Price at which the car was sold.
- **Present_Price**: Current price of the car model.
- **Kms_Driven**: Total kilometers the car has been driven.
- **Fuel_Type**: Type of fuel used by the car (e.g., Petrol, Diesel, CNG).
- **Seller_Type**: Type of seller (Dealer or Individual).
- **Transmission**: Transmission type (Manual or Automatic).
- **Owner**: Number of previous owners.

---

### Directory Structure

├── Templates │ └── index.html ├── app.py ├── demo.gif ├── rf_regression_model.pkl ├── Car Dekho Price Prediction.ipynb ├── LICENSE ├── car data.csv ├── Procfile ├── README.md └── requirements.txt

- **Templates**: Contains the HTML template for the UI.
- **app.py**: Main script for the front-end and back-end integration.
- **rf_regression_model.pkl**: Pre-trained model for car price prediction.
- **Car Dekho Price Prediction.ipynb**: Jupyter Notebook file containing the data analysis and model training.
- **requirements.txt**: Lists the libraries required for the project.
- **car data.csv**: Dataset used in the project.

---

### Installation

1. Clone this repository and navigate to the directory:
   ```bash
   git clone https://github.com/Nitikachoudhary66/car-selling-price.git
   cd car-selling-price
