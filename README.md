# affordable-housing-sanjose
A python converter to visualize affordable housing data for San Jose on an html page.

# Dev Setup #

Python
Eclipse For Python

# Dependencies #

usaddress(https://pypi.python.org/pypi/usaddress)

# Resources #

San Jose affordable-housing datasets - PublishAffordableExcelCSV.csv
HTTP API for looking up code-enforcement cases related to an address


#Open issues#
All the addresses do not conform to the US address conventions. Their format differs so we are unable to identify the Street Direction accurately.
Cannot access the code enforcer url via javascript because of CORS issues.
CURL posts to the code enforcer url work fine.







