## :red_car: Exploratory Data Analysis and Data Cleaning of Vehicle Sales Dataset :broom:  

Dataset obtained from [Kaggle](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data) provides in-depth details on each vehicle (make, model, year, features) alongside sales information (price, date). It even goes a step further, including estimated market values to help you track market trends. Additionally, you can analyze how a car's condition and mileage affect its selling price.

However, some cleaning is required before predicting on this dataset. The [Vehicle Sales Notebook](https://github.com/aprilhong/vehiclesales/blob/main/vehiclesales.ipynb) showcases the exploratory data analysis and cleaning process. 

**Issues discovered through early exploratory analysis**
  - duplicated categorical values with different formats (ex. Toyota vs toyota)
  - data entry errors with values placed in the wrong columns

**Methodologies** 
- Removing duplicate categorical values
- Spliting and Joining dataframes
- Filling in missing data based on existing values
  - For example, vehicle model can be found if both make and trim are available. 
- Imputing missing values with median
 
**Recommendations**
- The cleaned dataset can be used to forecast vehicle selling price. 

**File Descriptions**
  - [data](https://github.com/aprilhong/bankchurn/tree/main/data) : folder containing all data files
    - **car_prices.csv**: raw dataset from [Kaggle](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data)
    - **df_cleaned.csv**: cleaned dataset exported from notebook
  - **vehicalsales.ipynb** : jupyter notebook with EDA and Data Cleaning
  - **plots.py** : module with plotting functions used in the notebook



