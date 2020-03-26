***
geoIPmain.py Functions:

# 1. Database Functions:
## def c1():
    * Connects to the database

## def getCounties():
    * get countries from database

## def getC_Num(CC):
    * get abrivation of the countries from database based on the IP address

## def makeJson(CCL, numCL):
    * creates a json file from country code list, num of that country in the database

# 1. File Functions:
## def toJsonFile(JS):
    * dumps json data type to master.json

## def CtoCSV(CC):
    * writes to countries.csv

## def NtoCSV(num):
    * writes to num.csv

## def abrvTOFN(name):
    * opens /var/www/php_inc/data_csv.csv and compares countries and their code