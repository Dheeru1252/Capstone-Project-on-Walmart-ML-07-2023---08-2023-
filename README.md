# Capstone-Project-on-Walmart-ML-07-2023---08-2023

** Problem Statement 1:
A retail store that has multiple outlets across the country are facing issues in managing the
inventory - to match the demand with respect to supply.


Dataset Information:
The walmart.csv contains 6435 rows and 8 columns.

Feature Name           Description
Store                  Store number
Date                   Week of Sales
Weekly_Sales           Sales for the given store in that week
Holiday_Flag           If it is a holiday week
Temperature            Temperature on the day of the sale
Fuel_Price             Cost of the fuel in the region
CPI                    Consumer Price Index
Unemployment           Unemployment Rate


** Task To Be Done.

1. You are provided with the weekly sales data for their various outlets.
   
2. Use statistical analysis, EDA, outlier analysis, and handle the missing values to come up with various
insights that can give them a clear perspective on the following:


-To perform task, we need to import the required libraries like, pandas,numpy,matplotlib,seaborn,Skleran.

-1- # Load the datasets...

-2- # Performming the EDA...
        which include, finding the null values, duplicated, first veiw of our datasets etc.

![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/356223fb-3138-4229-afc0-76af500eea3d)

        Check the unique values of our datasets.

![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/73e54787-de5b-4972-bbc4-888d044b011c)

        First five recods from the datasets.

![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/6661cbf8-c385-4d4a-81a1-d3c7e7d0e6ec)


        performing some feature engineering with our Date columns to get correct data for prediction.

![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/c559a161-0459-4523-bff9-c94ddd4af423)


        Perfornig the outliers detection by IQR method.

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/a022bea1-cb7c-4b89-8b7d-2049052a7788)

        -3- Data Visualization:

         Plotting the weekly sales
         
  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/4d510f12-b7a1-466f-a54f-5f219ea6423d)

        # in above graph shows that our weekly sales is not normally distributed, its skewed to right

        Ploting on Caterogical Variables:
  
  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/b21467b4-fc15-4c65-b854-e1ce2433fd3e)

        Month Wise Sale

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/63b9e8ec-9afe-4850-abb6-c611cdd92b8b)

        Yearly Sales

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/29922fe1-678b-43f5-9642-41d942c45622)

        Plotting the Numerical variables:

        Holiday Flag

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/2ae0d429-9e76-4c9d-a732-f5cda6fd15df)


         Unemployeement

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/b8a885ae-eeea-4b0b-90dd-194b4c185784)


        -4- Check the correlation between Numerical Data Variables:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/214fb4e5-f158-4339-a9d1-8433867d5e1b)

         Heatmap of our correlated variables:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/13235752-1337-41b5-83c0-a56a6ac62ca9)


  -sales are affected by the unemployment rate, if yes - which stores are suffering the most?

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/f372a1fd-f7b9-484e-a2b8-a316ca6c62f0)



b. If the weekly sales show a seasonal trend, when and what could be the reason?

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/8be58c6b-6fb6-47ac-900d-ab27f2d4ef78)


c. Does temperature affect the weekly sales in any manner?


  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/ebb65653-f6eb-4ea1-92b0-67d27356cace)

d. How is the Consumer Price index affecting the weekly sales of various stores?

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/744d2ab4-5161-474f-b54b-7d9cde5ccb7f)

e. Top performing stores according to the historical data.

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/0aaac8f0-ce54-4fa5-b8a6-505f720490b2)

f. The worst performing store, and how significant is the difference between the
highest and lowest performing stores.

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/bd1966d2-7bd5-43e3-9a9e-ba9e3f4631de)

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/38630545-6f83-4a50-9929-0004ee7d8c73)


  Various Machine Learning Superived Models:
  
  1-Linear Regression:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/12960c36-156e-4687-b34b-e1c3b7ddee39)

  2-Random Forest model:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/ed264806-4788-4b7f-a6d5-76cd692909c5)

  3-Decision Tree Model:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/d7fc80bc-4906-493b-940c-c8577f0ba260)

  4-KNearest Neighbors Model:
  
  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/ffeaca80-4b9a-4724-a961-43e12b8fb7a7)

  # One basis of above model we get find that Random Forest Model is performing best out of these models.

  
-5- Use predictive modeling techniques to forecast the sales for each store for the next 12

  To performe the forecast for 12 weeks by Facebook Prophet Technique.

  First five records of dataset for forcasting.

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/89f5b637-ff0c-49e1-8769-62fff205001f)

  Forcasted graphs:

  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/b8f14f10-25d9-45b3-94b8-595a5ccf2237)

  Total Sale forecast for 12 weeks:
  
  ![image](https://github.com/Dheeru1252/Capstone-Project-on-Walmart-ML-07-2023---08-2023-/assets/115200521/2188b14c-44e9-4bf4-a7f1-177b61535563)


  # as per above grphs we can find that sale is drop in Jan and it's maintain consistently high from mid of Feb and goes till novemenr mid and again at end of november sales will go up as due to public holidays... on Yearly basis...

eks
