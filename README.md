
-----------------------------------------------------------------------------------------------------------------
# Data  Mining projects  (Python)
-----------------------------------------------------------------------------------------------------------------

### 1. Crime statistics of São Paulo state cities (Brazil)

Data is available at Civil state Police statistics site:  http://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx   

Obs.: Crime type interpretation manual available (only in brazilian  portuguese) at: http://www.ssp.sp.gov.br/Estatistica/download/manual.pdf

Since there is no API or JSON file available in the website, I scrapped data and created 3 complete datasetsin Python.

Part 1 - Data extraction via webscrapping  using Selenium library, to navigate through the pages and extract data, and Pandas library to create and deal with dataframes from the scrapped data, including the crime types, year, city and region.
 Data available until march 2020. see project folder. 
 
Part 2 (to be released soon) 
Dashboards:  http://segurancabrasil.pythonanywhere.com/

-----------------------------------------------------------------------------
### 2) FIPE table (Tabela FIPE)   

Webscrapping of Tabela FIPE data (no official  API available) , containing  average value of cars, trucks and motocycles. Values in brazilian Reais (BRL or R$).


-----------------------------------------------------------------------------
### 3) IBGE data tables   


If you want to gather any table from the Brazilian Institute of Geography and Statistics - IBGE - site , I suggest using the PyIBGE module, developed by Renan Birck: https://github.com/renanbirck/pyibge

This module accesses the API from IBGe website:  http://api.sidra.ibge.gov.br/ 

** After you download the module PyIBGE in a local folder, you have to add the folder path into the sys.path of your computer. So Python can identify this module via 'import' command as you work with it.  

Option 1) Using command lines in Python:   
      import sys  
      sys.path.append(r'yourpath\pyIBGE')  
      import pyIBGE    
Option 2) Go to System properties --> environment variables --> click "Path"--> edit --> add folder name)    
<img width="956" alt="ssp-fig" src="https://user-images.githubusercontent.com/52055874/89600833-648e3c00-d839-11ea-8bab-3cfc6c3d37a0.png">

-----------------------------------------------------------------------------------------------------------------
# Data Engineering  -  Resources
-----------------------------------------------------------------------------------------------------------------
## Web scraping   
- Web scraping with Python  
 https://towardsdatascience.com/web-scraping-with-python-a-to-copy-z-277a445d64c7  

- How to find elements via CSS and Xpath  
QArentena 20 - Localizando Elementos via CSS e XPath - com Danilo Freitas(available only in portuguese)    
https://www.youtube.com/watch?v=ZSAglCvKy9g

- Understanding Regex (which can be useful to search for a specific word in a text)  
https://www.w3schools.com/python/python_regex.asp
  
- Working with Json   
https://www.w3schools.com/python/python_json.asp    
https://www.geeksforgeeks.org/how-to-convert-pandas-dataframe-into-json-in-python/   
