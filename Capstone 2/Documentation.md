# Used Car Price Prediction
The COVID-19 pandemic started in March 2020 and has changed many aspects of the world, and the used motor vehicle market has suffered a direct impact. A shortage of components causes a decrease in new car production due to a disrupted supply chain, therefore the value of the used car has skyrocketed since the pandemic. In this project, I will create a machine learning model that will predict used car prices using it's information.
## 1.Data
The chosen dataset is obtained from Kaggle, it includes datas for the cars price, year, mileage, city, state, vin, make, and model. To view the original Kaggle website, click on the link below
- [Kaggle Dataset](https://www.kaggle.com/datasets/harikrishnareddyb/used-car-price-predictions?select=true_car_listings.csv)
## 2.Data Wrangling
[Data Wrangling Report](https://github.com/MarquinhosWang/SBDS/blob/565d778b993679510681dd0977bae1d50eb3360b/Capstone%202/Cap2_data_wrangling.ipynb)
- The dataset does not have any missing value that could cause problems to our machine learning algorithms 
- The dataset contains many duplicated values that could cause our model to overfit, these duplicated values are droped
- After dropping duplicated values our dataset has 852092 rows.
## 3.EDA
[EDA Report](https://github.com/MarquinhosWang/SBDS/blob/10b25d9b17be079757f7180928436aac31be9716/Capstone%202/Cap2_EDA.ipynb)
Below are the 5 questions that I explored in the EDA process
- Average used car price per year
![](./files/1.png)
- Top 5 most expensive used car models
![](./files/2.png)
- What features correlate the most with the price
![](./files/3.png)
- Which state sold most used cars
![](./files/4.png)
- Which year has most sold used cars.
![](./files/5.png)