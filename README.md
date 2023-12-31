
# Boston Housing Price Prediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.9 -y
```
This repository contains a machine learning project that predicts Boston housing prices. It uses a linear regression model trained on the Boston Housing dataset. The model is then deployed as a web application with Flask, allowing users to input parameters and receive housing price predictions.

# Project Structure
Linear Regression ML Implementation.ipynb - Jupyter notebook containing the code for data preprocessing, analysis, model training, and evaluation.
app.py - The main Flask application script used to run the web server and provide API endpoints for predicting housing prices.
regmodel.pkl - The pre-trained linear regression model used for predictions (not included in the repository, but generated by the Jupyter notebook).
scaling.pkl - A file containing the scaler object for scaling feature data (not included in the repository, but generated by the Jupyter notebook).
templates/ - Folder containing HTML templates for the web application.

# Installation
Before running the application, you need to install the necessary Python packages. You can install these packages using pip:
```
pip install -r requirements.txt
```
Note: The requirements.txt file is not included in the repository. You should create this file and list all the necessary packages and their versions.

# Usage
To run the web application on your local machine, execute the following command:
```
python app.py
```

This command will start a local web server, and the application will be accessible at ``` http://127.0.0.1:5000 ``` by default.

For making predictions, navigate to the home page, input the required parameters, and submit the form. The predicted Boston housing price will be displayed on the screen.

# Notebook
To view the model training and evaluation process, you can open the Linear Regression ML Implementation.ipynb notebook. This notebook includes detailed steps on data loading, preprocessing, exploratory data analysis, model training, and performance evaluation.

# Contributions
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

# Author
Name: MGJIllani (Jillani SoftTech)
GitHub: [@MGJillaniMughal](https://github.com/MGJillaniMughal)

Show your support
Give a ⭐️ if you like this project!
