# athens_weather_analysis

## Purpose
This repository contains an analysis of Athens' weather during the period 1955-2020, that was done in the context of the university course: "Applied Machine Learning".



## Tools and Packages
The analysis was executed on [Jupyter](https://jupyter.org/) *(Jupyter Notebook 6.4.4 and Python 3.9.0 will work for sure)*. 

Additional packages required for the project to run are:
* [NumPy](https://numpy.org/) *(1.19.5 or up will work for sure)*
* [pandas](https://pandas.pydata.org/) *(1.3.3 or up will work for sure)*
* [matplotlib](https://matplotlib.org/) *(3.4.3 or up will work for sure)*
* [SciPy](https://scipy.org/) *(1.7.1 or up will work for sure)*

All the packages above can be installed using the `pip install` command-line command.

## Data
The data used can be found in the <code>data</code> folder. Specifically:
* `data/hellinikon_noaa.csv`: was downloaded from [NOAA](https://www.ncdc.noaa.gov/cdo-web/search), and refer to the weather station of Hellinikon and the period 1955-2020.
* `data/athens_hds.csv`: was downloaded from [HDS](https://data.hellenicdataservice.gr/dataset/66e1c19a-7b0e-456f-b465-b301a1130e3f), and refer to the weather station of Athens and the period 2010-2019.

More detailed information about the datasets can be found within `weather_analysis.ipynb`.

## How to run
1. **Clone the project:** Execute the command `git clone https://github.com/giorgossideris/athens_weather_analysis.git`
2. **Move into the project:** Execute the command `cd athens_weather_analysis`
3. **Open the analysis:** Execute the command `jupyter notebook weather_analysis.ipynb`  
  
***Note**: The purpose behind this analysis was not to generate state-of-the-art meteorogical findings. Instead, I performed it in order to get comfortable with using pandas and Jupyter Notebook.*
