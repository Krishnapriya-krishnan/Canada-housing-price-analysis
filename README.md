# 🏡 Canada Housing Market Analysis
## Project Overview
This project analyzes a dataset of Canadian housing properties to uncover trends, key price drivers, and insights into the real estate market. The project also includes a predictive model to estimate house prices based on property features.
### Key Objectives:

Explore the Canadian housing market by city, province, and property type

Identify features that influence property prices

Build a regression model to predict house prices

Visualize trends for insights suitable for investors, buyers, and analysts

### Dataset
The dataset contains housing data across Canada with the following features:

#### Feature	Description
City:	City where property is located

Province:	Province where property is located

Latitude / Longitude:	Geographic coordinates

Price:	Property sale price (CAD)

Bedrooms:	Number of bedrooms

Bathrooms:	Number of bathrooms

Acreage:	Land size (acres)

Property Type:	Type of property (house, condo, etc.)

Square Footage:	Area of the property in sq ft

Garage / Parking:	Garage or parking availability

Basement:	Presence of basement

Exterior:	Exterior type (brick, wood, etc.)

Fireplace / Heating:	Features that may affect price

Flooring / Roof:	Material and type

Waterfront:	Whether property is on waterfront

Sewer / Water	Utilities available

Pool / Garden / Balcony	Additional amenities

### Project Steps
Data Cleaning

Handle missing values and duplicates

Standardize categorical variables

Convert binary features to 0/1

Feature Engineering

Created Price_per_sqft and Total_rooms

Added Luxury_flag for premium properties

Exploratory Data Analysis (EDA)

Visualized price distribution and outliers

Analyzed price by province, city, and property type

Correlation analysis for numerical features

Bivariate analysis between features and price

Predictive Modeling

Split data into training and test sets

Built regression models: Linear Regression, Random Forest

Evaluated models using MAE, RMSE, and R² score

Analyzed feature importance to determine price drivers

### Visualization
Scatter plots, box plots, bar plots, heatmaps

Geographic visualization of property prices (optional)

### Key Insights
Square Footage is the strongest driver of property price.

Properties in Ontario and British Columbia have the highest average prices.

Amenities like pool, garage, and waterfront significantly increase property value.

Houses with more bedrooms and bathrooms generally command higher prices.

### Tools & Libraries
Python: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning: Scikit-learn

Optional: Plotly or Streamlit for interactive visualization

PowerBI : Dashboard
