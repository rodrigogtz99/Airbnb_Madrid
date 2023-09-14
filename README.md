# Madrid Airbnb Price Prediction

This project aims to predict prices for Airbnb listings in Madrid by utilizing data analysis and machine learning techniques. The dataset was obtained from Inside Airbnb's website, which provides data and advocacy about Airbnb's impact on residential communities.

## Data Collection
The data for this project was gathered from the following link: [Inside Airbnb Data](http://insideairbnb.com/get-the-data/). The dataset was collected and maintained by Murray Cox, John Morris, and Taylor Higgins, who contribute to the Inside Airbnb project. Inside Airbnb is a mission-driven project that provides data and information to empower communities in understanding and controlling the impact of renting residential homes to tourists.

## Data Preprocessing
For this project, all the information from exactly one year before the last scraping was used. The data was cleaned by removing duplicates, handling null values, and dropping unnecessary columns. Additional columns were created during this process to enrich the dataset.

## Exploratory Analysis
An exploratory analysis was performed to gain insights into the data. This involved understanding the most expensive neighborhoods, districts, and months for Airbnb listings in Madrid.

## Feature Selection and Engineering
The variables with the strongest correlations with the target variable (price) were identified. Both linear and non-linear correlations were considered. Exogenous variables, including Madrid hotel occupation during each month, were also incorporated. The selected features were then used to construct a machine learning model.

## Machine Learning Model
The machine learning model was built using H2O, an open-source platform for machine learning and predictive analytics. The model was trained to predict the prices of Airbnb listings in Madrid. The root mean square error (RMSE) metric was used to evaluate the model's performance.

## Interactive Visualizations
Interactive visualizations were created using Tableau to showcase the findings and insights from the project. You can access the visualizations at the following link: [Tableau Visualizations]([link-to-tableau-visualizations](https://public.tableau.com/app/profile/rodrigo.gutierrez.garcia/viz/AirbnbPredictionsMadrid/Story2?publish=yes)).

Feel free to explore the code, data, and visualizations provided in this repository. If you have any questions or suggestions, please feel free to reach out.



