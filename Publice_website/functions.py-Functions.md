
# 1. Database Functions:
## def c1():
    * Connects to the database

## def getTime(page):
    * Gets time of last entered DB 

## def ipToTable(ip, country):
    * inserts the ip to the table it into the table if not already entered

# Refereance and Convert Functions:
## def getFile():
    * Lists all the Webpages in Production

## def toIP(list1):
    * Takes a tupple and converts it into a string list of IP's

## def getJSON2():
    * Calls uIPS() and turns it into a json file

## def getJSON():
    * Calls uIPS() and turns it into a json file


# 2. View Functions:
## def getF1Views():
    * Gets views from 404.php

## def getF2Views():
    * Gets views from index.php

## def getF3Views():
    * Gets views from no.php

## def getF4Views():
    * Gets views from temp.php

## def getF5Views():
    * Gets views from tokenEnter.php

## def getF6Views():
    * Gets views from dashBl.php (dash board page)

## def getF7Views():
    * Gets views from l.php (login page)

## def viewList():
    * Calls getF1-7U() and prints them and returns the values as a list

## def ipToJson(l1):
    * turns a ip list into json

## def getIPBF(file1):
    * get/return ip based on website file

## def returnRealF(file1):
    * get/return views based on website file

## def returnViewsAr():
    * get/return views as a list


# 3. IP Functions:
## def getF1U():
    * This gets the number of unique ips and prints them from 404.php

## def getF2U():
    * This gets the number of unique ips and prints them from index.php

## def getF3U():
    * This gets the number of unique ips and prints them from no.php

## def getF4U():
    * This gets the number of unique ips and prints them from temp.php

## def getF5U():
    * This gets the number of unique ips and prints them from tokenEnter.php

## def getF6U():
    * This gets the number of unique ips and prints them from dashbL.php

## def getF7U():
    * This gets the number of unique ips and prints them from reg.php

## def getF1ips():
    * This gets the number of unique ips to compare them 

## def getF2ips():
    * This gets the number of unique ips to compare them 

## def getF3ips():
    * This gets the number of unique ips to compare them 

## def getF4ips():
    * This gets the number of unique ips to compare them 

## def getF5ips():
    * This gets the number of unique ips to compare them 

## def getF6ips():
    * This gets the number of unique ips to compare them 

## def getF7ips():
    * This gets the number of unique ips to compare them 

## def allIPS():
    * Calls getF1-7U() and prints them and returns the values as a list

## def uIPS():
    * Calls getF1-7ips() and prints them and returns the values as a list

## def ipCommand(file1):
    * return the ips if in the passed API value

## def ipCommand2(file1):
    * return the ips if in the passed API value (dynamic)

## def apiIP(file1):
    * return the ips if in the passed API value (dynamic for on the fly)

# 4. Geo Functions:
## def geoIP():
    * gets the country of the IP from the IP list and send the value to ipToTable

## def getGEOip(ip):
    * gets the country of the IP from the IP and returns if it has a entry

## def abrvTOFN(name):
    * creates a csv file with countries abrvation and full name

