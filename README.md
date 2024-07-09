### Capstone Project 
# █▓▒▒░░░AQI TO THE DEATH░░░▒▒▓█
by Nattawaree Piyarat

GitHub link https://github.com/Nattie29/Capstone

Update Sprint 3  (July 8, 2024)
- Visualization
- EDA insight
- Model optimization, evaluation, and interpretation.

My capstone project

###  🌱The Problem area:░░░▒▒▓█ 
Can machine learning predict the death rate against the Air Quality Index (AQI)?
Is there any relationship between air quality and health (death rate) and what factors impact air quality? 

Nowadays, we know what will impact air pollution (wildfire, dust, car, manufacturing)

I would like to address the AQI and the number of deaths in selected Asian countries.\
	- China\
	- India\
	- Thailand
### 👩‍👩‍👧‍👦The User:░░░▒▒▓█ 
The users will be the world population especially people in selected Asian countries who are stressed from air pollution. The outcomes to be aware to create high chances of AQI. 
### ⚡The Impact:░░░▒▒▓█ 
The results of this project should raise awareness of air pollution and reduce the number of deaths of people by at least 1%, especially in the concerned areas.
### 📄The Data:░░░▒▒▓█ 
Dataset from WHO database (Air quality index, number of deaths by cause, pollution, dust, wildfire).
Currently, I reference the datasets below.

1. Air Quality Index (2009–2019):
- Initially sourced from WHO.
- This dataset has been removed and replaced with another due to the inclusion of more pollutants while retaining similar details.
2. Number of Deaths by Cause (2016–2019):
- Sourced from WHO.
3. Air Quality Open Data Platform (2019–2020): https://aqicn.org/data-platform/covid19/
- Sourced from The World Air Quality Index Project.
- The data includes city-specific measurements, aggregated to calculate the mean air quality for each country on each date for this project.

The data dictionary is provided in a separate document.

### 💡The Big Idea:░░░▒▒▓█ 
The machine learning approach will use historical AQI data, and historical death causes data.\
And predict the relationship between air quality and the number of deaths assumed to be caused by high AQI.\
Since the impact of the air quality index (AQI) on mortality takes time to become evident, it's crucial to forecast AQI based on each pollutant.Add more datasets that contain many pollutants (O3, PM2.5, PM10, CO2, NO2, CO, SO2)

**Focus** at level 5 (Very poor)

![image](https://github.com/Nattie29/Capstone/assets/159632621/682fe791-46e1-4b88-8760-51cbef12f7d2)

**📊Model candidates** 
- Linear Regression
- Logistic Regression
- KNN
- Decision Tree

#### 🏅Selected Model is Logistic Regression:░░░▒▒▓█ 
![image](https://github.com/Nattie29/Capstone/assets/159632621/d7e83961-2085-4173-91b1-841cac50bc37)


🏅Selected Model is XGBoost:
Reasons:
- A good score of R2 should be close to 1
- MAE and MSE should close to 0
- RMSE, the lower is better
- The above table shows that each model’s results are almost the same but the **XGBoost** is the best from those 3 models.!

  

### 📂Project Folders:░░░▒▒▓█ 
- Docs: keep all documents and reports including presentation files.
- Notebooks: keep Jupyter notebooks and data that are used in the notebooks.
- References: keep all data references.
- Bak: for backup and archive files.

### ⏭️Key Takeaways from the project (Next step)▄▀▄▀▄▀ 

- Since the impact of the air quality index (AQI) on mortality takes time to become evident, it's crucial to forecast AQI based on each pollutant. Add more datasets that contain many pollutants (O3, PM2.5, PM10, CO2, NO2, CO, SO2) or add more countries. Issue of this version some countries did not provide all pollutants.
- Find a relationship between asthma and pollutant density and improve the model to predict diseases or mortality. 
- Develop an application to predict the unhealthy indicator.



