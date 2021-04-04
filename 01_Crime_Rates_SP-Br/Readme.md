
## Project 1 ) Crime rates in São Paulo state, Brazil

The aim is to obtain crime data of all São Paulo state cities through webscrapping techniques and develop an online ETL process to monthly update the datasets. Also the data visualization was prepared (in PowerBI), to provide information for the journalists and population in general.
 
Data is available at Civil state Police statistics site (SSP):  http://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx   
Obs.: Crime type interpretation manual available (only in brazilian  portuguese) at: http://www.ssp.sp.gov.br/Estatistica/download/manual.pdf

----------------------
#### Part 1 - Data extraction via webscrapping  using Selenium library, to navigate through the pages and extract data, and Pandas library to create and deal with dataframes from the scrapped data, including the crime types, year, city and region.
There is no API or JSON file available in the website, thus wescrapping was required.

Deployment:  E.T.L. process developped in Python with Pandas. Dataset is automatically  updated monthly as soon as SSP site is updated.


 
#### Available datasets:  

 - Crime rates ( "Taxas de Delito")  -  from 2001 to 2020   
   Note: Annual rates available. Crime rate data from current year will only be avaible in January of next year, after data consolidation.
 
 - Monthly occurences ("Ocorrências mensais") - from 2001 to current month  

- Policy productivity (Produtividade policial) -- from 2001 to current month
 
  **Since there is a size limit for files upload here in Github, I have been uploading the datasets in Kaggle:**
  **https://www.kaggle.com/dbwaller/official-crime-data-sao-paulo-statebrazil-ssp**

-  Geographic coordinates of São Paulo state cities and its respective IBGE codes :  ds_SPcities_coordinates.csv  
   IBGE:  Brazilian Institute of Geography and Statistics

--------------------------

### Part 2 - Data visualization - Dashboards

Monthly occurences dashboard developped in PowerBi and available at  
 ### http://segurancabrasil.pythonanywhere.com/
 Note: temporarily unavailable 
 
Data until May/2020:

<img width="956" alt="ssp-fig" src="https://user-images.githubusercontent.com/52055874/87192447-d8860480-c2cc-11ea-980d-e14b6d285658.png">


