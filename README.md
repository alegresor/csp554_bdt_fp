# CSP 554: Big Data Technologies ~ Final Project
# Big Data Machine Learning

## Team Members
- Aleksei Sorokin [asorokin@hawk.iit.edu]([mailto:asorokin@hawk.iit.edu)
- Harshit Paliwal [hpaliwal1@hawk.iit.edu](mailto:hpaliwal1@hawk.iit.edu)
- Sunny Chou [schou2@hawk.iit.edu](mailto:schou2@hawk.iit.edu)
- Vaibhav Ramesh Kunkerkar [vkunkerkar@hawk.iit.edu](mailto:vkunkerkar@hawk.iit.edu)

---

## Setup 
Make sure `csp554_bdt_fp` is on you python path, this is easiest with a virtual environment.\
Run the command `pip install -r requirements.txt` to install necessary python packages. 

---

## Files
`data/` 
- `iris.csv` iris dataset from [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/iris)
- `turtles/` contains raw, clean, and meta data sets about turtles
  - [DATA.GOV turtles dataset homepage](https://catalog.data.gov/dataset/sea-turtle-population-study-in-the-coastal-waters-of-north-carolina-from-1988-06-07-to-2015-09-)
  - [National Centers for Environmental Information turtles dataset download page](https://www.nodc.noaa.gov/cgi-bin/OAS/prd/accession/download/162846)

`spark_pkg/`
- `mllib_iris.py` train and test pyspark mllib models on iris dataset
- `sql_turtles.py` clean turtles dataset with pyspark sql
- `mllib_turtles.py` train and test pyspark mllib models on turtles dataset
- `mllib_util.py` utility functions with pyspark sql used in mllib_*.py files
- `logs\` output logs from *.py files

`depricated/`
- `pandas_turtles.py` clean turtles dataset with pandas
- `logs\` output logs from *.py files