## Earthquake Prediction using XGboost
## Overview
The goal of this project is to use machine learning algorithms to forecast earthquakes. Python and a number of libraries for data processing, analysis, and machine learning are used in the model's construction.

## Table of Contents
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Model Screenshots](#model-screenshots)

## Installation
To use this project locally, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-.git
   ```
2. Export ipynb to google collab

3. Put all_month(2).csv to root directory of Data_Processing(Earthquake) in google collab
   ![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/7ba096b2-4cf0-4cff-9163-142ed97bc3c5)
4. Get Earthquake_features.csv and Earthquake_predict.csv and put them in the root directory of Earthqauke_Prediction(XgboostClassifier)
   ![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/3dbbfcf7-0527-4c01-8956-947108f4a4cb)

## Project Structure
The project structure is organized as follows:
- `Data_Processing(Earthquake).ipynb`: Used for Data transformation and to create csv on which prediction will be performed
- `Earthquake_Prediction(XgboostClassifier).ipynb`: Contains python code.
- `all_month(2).csv`: Data used for training and testing the model.

## Dependencies
- ### Python 3:
  Python is a widely-used programming language in the field of data science and machine learning. It serves as the foundation for developing the entire project, including the web application and machine learning model.
- ### numpy:
  Library for numerical computing.
- ### Pandas:
  Pandas is a powerful library in Python used for data manipulation and analysis. In this project, Pandas likely plays a role in preprocessing the input data, handling missing values, and transforming the data into a format suitable for the machine learning model. Version 2.0.0 of Pandas is specified to ensure consistency and compatibility with the project.
- ### sklearn:
  Library for machine learning algorithms
- ### datetime:
  Module for working with dates and times.
- ### matplotlib:
  Library for plotting graphs and charts.
- ### os:
  Module for interacting with the operating system.
- ### xgboost:
  Library for gradient boosting.
  
## Contributing
Contributions to improve the project are welcome! Here's how you can contribute:
- Fork the repository
- Create a new branch (`git checkout -b feature`)
- Make modifications and commit changes (`git commit -am 'Add new feature'`)
- Push changes to the branch (`git push origin feature`)
- Create a pull request

Feel free to modify this README file to include more specific instructions, additional details about the model, or any other relevant information about your project. Good luck with your project!

### Model Screenshots

I've included screenshots from my Jupyter Notebook to showcase various aspects of the model's performance and insights.

#### Feature Importance
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/a798a57f-0790-42b2-9bdd-2f31a2eb541b)
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/f64da021-463b-4503-86f4-81ce85b5bc56)
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/72af5dc1-7412-48f7-9c41-67dcd9a4016f)


## Model Evaluation Metrics

#### 1. For DecisionTreeClassifier
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/b788056b-dc4c-4394-ae3d-dd126211f37c)

#### 2. For RandomForestClassifier
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/21c89be6-c399-4b26-874e-670e78c7d7e3)

#### 3. For XGBClassifier
![image](https://github.com/DivyanshuKaanaujia/EarthquakePredict-Xgboost-/assets/124723859/df529f65-48cc-4b2b-9a4d-9bcddaa366e1)


