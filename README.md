**Weather Prediction using Linear Regression**

This project demonstrates how to predict weather temperature using a linear regression model with the help of the scikit-learn library in Python. The model is trained on a weather dataset and evaluated using common metrics like Mean Squared Error (MSE) and R² score.

**Project Overview**

This project includes the following key components:

**Data Loading and Exploration**

Feature Selection and Data Preprocessing
Training and Testing of the Linear Regression Model
Model Evaluation
Results Visualization
**Requirements**

To run the project, you will need the following Python libraries:

pandas
numpy
scikit-learn
matplotlib
You can install the dependencies using the following command:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib
**Usage**

Clone the Repository
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/weather-prediction.git
Prepare the Dataset
Ensure you have your weather dataset (e.g., weather_data.csv) in the correct path.

Run the Code
Execute the script to train the model and evaluate its performance:

bash
Copy code
python weather_prediction.py
View the Results
After running the script, the following outputs will be generated:

Mean Squared Error (MSE) and R² score of the model
A scatter plot comparing actual and predicted temperatures.
**Dataset**

Ensure your dataset contains the following columns (or adjust accordingly):

Humidity
WindSpeed
Pressure
Precipitation
Temperature (target variable)
The dataset is split into 80% training data and 20% testing data.

**Model**

The model used in this project is Linear Regression, which attempts to predict the Temperature based on the relationship with other weather parameters like Humidity, WindSpeed, Pressure, and Precipitation.

**Evaluation**

After training, the model is evaluated using the following metrics:

Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values.
R² score: Measures the proportion of variance in the dependent variable explained by the model.
Visualization
The script generates a scatter plot that compares the actual vs. predicted temperature values, allowing for a visual assessment of the model's accuracy.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
scikit-learn
pandas
matplotlib
