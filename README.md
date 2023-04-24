#Empathy-Score-Regression-Analysis
This repository contains a Python script for performing Random Forest Regression on data which can be found at [https://www.nature.com/articles/s41597-022-01862-w#Sec10]. The script uses scikit-learn to implement the Random Forest Regression algorithm and pandas to load and manipulate the data.

Requirements
Python 3.7
pandas
missingno
fancyimpute
Installation
Clone this repository:
git clone https://github.com/Muhathaz/Empathy-Score-Regression-Analysis.git
Install the required Python packages:
pip install pandas missingno fancyimpute
Usage
Download the sample datasets from this link and extract them to the data folder.

Run the script:
python Empathy Model.py

The script will output the R-Squared and MSE scores for each cross-validation sample, as well as a plot of the cross-validation scores.
License
This repository is licensed under the MIT License. See the LICENSE file for more details.
