
### About Project 1: Crime rates in São Paulo state, Brazil

The aim is to obtain crime data of São Paulo state (Brazil) through webscrapping techniques and develop an online ETL process to monthly update the datasets. Also the data visualization was prepared, to provide information for the journalists and population in general.
 
Data is available at Civil state Police statistics site:  http://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx   
Obs.: Crime type interpretation manual available (only in brazilian  portuguese) at: http://www.ssp.sp.gov.br/Estatistica/download/manual.pdf

, I scrapped data and created 3 complete datasets sin Python.


### Part 1 - Data extraction via webscrapping  using Selenium library, to navigate through the pages and extract data, and Pandas library to create and deal with dataframes from the scrapped data, including the crime types, year, city and region.
There is no API or JSON file available in the website, thus wescrapping was required.



Deployment:  E.T.L process developped in Pyrthon with Pandas and deployed in http://segurancabrasil.pythonanywhere.com/


----------------------------------
#### Datasets disponíveis:     
 - Taxas de Delito
 - Ocorrências mensais
 - Produtividade policial
 
     Dados SSP de 2001 até 2019:
      - ds_Taxa_crime_SP-BR_v3_complete_utf8-2001-2019.csv  
      - ds_OcorrenciasMensais_SP-BR_v1_utf8.csv  
      - ds_ProdutPolicial_SP-BR_v1_utf8 -2019.csv

     Dados SSP de 2020 - 1o trimestre ( jan/ fev/mar):
     - ds_OcorrenciasMensais_2020_T1.csv  
     - ds_ProdutPolicial_SP-BR_2020_T1.csv     
     *As informações sobre taxas de delitos do ano vigente ficam dispoínveis apenas no ano seguintes, após consolidação dos dados.

 -  Coordenadas geográficas das cidades de Sao Paulo : ds_SPcities_coordinates.csv  
 Tabela com coordenadas geográficas das cidades de São Paulo e código IBGE  ( Fonte: IBGE) 




--------------------------------------------------------
  

### Part 2 - Data visualization - Dashboards

Monthly occurences dashboard developped in PowerBi and available at  
 ### http://segurancabrasil.pythonanywhere.com/

Data until May/2020:

<img width="956" alt="ssp-fig" src="https://user-images.githubusercontent.com/52055874/87192447-d8860480-c2cc-11ea-980d-e14b6d285658.png">


