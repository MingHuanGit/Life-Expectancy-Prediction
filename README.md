# Life-Expectancy-Prediction

## Dataset
Life Expectancy Data taken from https://www.kaggle.com/datasets/lashagoch/life-expectancy-who-updated. contains data about life expectancy, health, immunization, economic information, and demographic statistics for 179 countries from 2000-2015.

## Installation
This project requires Python and the following libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Usage
This project demonstrates the application of data cleaning, EDA, and predictive modeling using linear regression. 2 models were made: 
- 1 containing as many relevant features as required for the model
- 1 containing only features that are not considered 'sensitive' information from the country - a more ethical model

The order of reading/running the notebooks should be executed in this order:
1. Life_Expectancy_Cleaning_and_EDA.ipynb
2. Life_Expectancy_Feature_Engineering.ipynb
3. Life_Expectancy_Modelling
4. Non-Sensitive_Data.ipynb
5. Final_Function.ipynb

## Collaborations
This project was completed in collaboration with Kacper Rawicki https://github.com/KacperRawicki and Karan Ruprah https://github.com/KSR-16

## License 
[GNU General Public License version 3](https://opensource.org/license/gpl-3-0/)
