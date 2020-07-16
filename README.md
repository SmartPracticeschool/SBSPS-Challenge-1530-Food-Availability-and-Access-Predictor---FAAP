# SBSPS-Challenge-1530-Food-Availability-and-Access-Predictor---FAAP

## Description
The coronavirus pandemic will see more than a quarter of a billion people suffering from acute hunger by the end of the year. Risks faced my food security during the COVID-19 crisis have a major effect on disruptions in domestic food supply chains, other shocks affecting food production, and loss of incomes and remittances are creating strong tensions.
To solve this problem, we have created machine learning models that will predict the “Production” and “Demand” for crop yields considering the specified area and time. From the model predictions, one can estimate the demand and supply gap present in an area and will be able to take the required actions. As we can predict the future demand for products, it makes us control the supply chain and provide the products/goods at an affordable price to the consumers.

The main purpose of the model is to predict the demand and supply gap of the specified crop at a particular period, this will make the agriculture sector administration aware of any upcoming shortage of the stock of any commodity in the market in COVID-19 crises. This will help to prevent any shortage of the necessary commodity in the state.
People are dependent on markets for buying food and hence more vulnerable to price fluctuations and potential availability of the commodity. A sudden and sharp increase in prices of essential commodities will have a major effect on food security. Our model helps to understand food security problem and how it is even got worst with COVID-19 pandemic (crises within the crises)

## Architecture
![Architecture of Application](https://github.com/SmartPracticeschool/SBSPS-Challenge-1530-Food-Availability-and-Access-Predictor---FAAP/blob/master/images/architecture.png)

## Data 
* **Json data used for a rendering map. It consists of coordinates of states and state boundaries of India.**
![Json data 1](https://github.com/SmartPracticeschool/SBSPS-Challenge-1530-Food-Availability-and-Access-Predictor---FAAP/blob/master/images/jsondata.png)

![Json data 2](https://github.com/SmartPracticeschool/SBSPS-Challenge-1530-Food-Availability-and-Access-Predictor---FAAP/blob/master/images/jsondata1.png)
## Modules
* Entire application consists of 3 modules
* **Crop yield model**
* **Crop demand model**
* **Demand and Supply gap and data visualization**
## Module - 1: Crop Yield Model
* In this model first we have collected data regarding crop production from various resources. 
* After data is collected encoding and preprocessing of data are done followed by feature scaling.
* Then the data is divided into test and train data sets.
* After splitting of data, data is analyzed Deep Neural Network and prediction of crop yield is done.
* Here State name, crop year, crop name and area under cultivation are considered to predict crop yield.
## Module - 2: Crop Demand Model
* In this model first we have collected data regarding crop demand from various resources. 
* After data is collected encoding and preprocessing of data are done followed by feature scaling.
* Then the data is divided into test and train data sets.
* After splitting of data, data is analyzed Deep Neural Network and prediction of crop demand is done.
* Here State name, crop year and crop name are considered to predict crop demand.
## Module - 3: Data Visualization
* After successfully deploying module 1 and module 2 we can estimate demand and supply gap of the certain crop in a specific area.
* The gap between demand and supply is represented by a graph and the Indian map is generated based on the demand of the selected crop which is indicated by color range.
* Users can also visualize malnutrition in India based on the year and other important attributes like underweight, stunting, wasting, and income level.
* User can also see the suggestion that which crop needed to import or export from other states based on demand.

## Design Process

![Design Process](https://github.com/SmartPracticeschool/SBSPS-Challenge-1530-Food-Availability-and-Access-Predictor---FAAP/blob/master/images/design.png)

## Packages 
**Pandas:** -Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.
**NumPy:** -NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
**Scikit Learn:** -Scikit-learn is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbors, and it also supports Python numerical and scientific libraries like NumPy and SciPy.
**Dash:** -Dash is an open-source Python framework used for building analytical web applications. It is a powerful library that simplifies the development of data-driven applications.
**Requests:** -Requests is a Python HTTP library, released under the Apache License 2.0. The goal of the project is to make HTTP requests simpler and more human-friendly.
**Urllib:** -Urllib module is the URL handling module for python. It is used to fetch URLs. It uses the url open function and is able to fetch URLs using a variety of different protocols.
**Plotly:** -Plotly allows users to import, copy and paste, or stream data to be analyzed and visualized. For analysis and styling graphs, Plotly offers a Python sandbox, data grid, and GUI. Python scripts can be saved, shared, and collaboratively edited in Plotly.
**JSON:** -The json library can parse JSON from strings or file. The library parses JSON into a Python dictionary or list. It can also convert Python dictionaries or lists into JSON strings.

## Technology Stack
* **Programming Languages: Python**
* **App: Flask App**
* **Hosting Servers: IBM Cloud.**
* **Server Type: REST API Post**
* **Machine Learning Models Used: Deep Neural Network**


