### Datasets disponíveis:
 - Taxas de Delito
 - Ocorrências mensais
 - Produtividade policial
 
 

Dados SSP de 2001 até 2019:
 - ds_Taxa_crime_SP-BR_v3_complete_utf8-2001-2019.csv  
 - ds_OcorrenciasMensais_SP-BR_v1_utf8.csv  
 - ds_ProdutPolicial_SP-BR_v1_utf8 -2019.csv

Dados SSP de 2020 - 1o trimestre ( jan/ fev/mar):
- ds_Taxa_Crime_SP-BR_2020_T1.csv  
- ds_OcorrenciasMensais_2020_T1.csv  
- ds_ProdutPolicial_SP-BR_2020_T1.csv

Tabela com coordenadas geográficas das cidades de São Paulo e código IBGE  ( Fonte: IBGE) 
-  ds_SPcities_coordinates.csv  

-------------------------------------------------------------------------------
### About Project 1: Crime rates in São Paulo state, Brazil

The aim is to obtain crime data in São Paulo state , Brazil.

Data is available at Civil state Police statistics site:  http://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx   

Obs.: Crime type interpretation manual available (only in brazilian  portuguese) at: http://www.ssp.sp.gov.br/Estatistica/download/manual.pdf

Since there is no API or JSON file available in the website, I scrapped data and created 3 complete datasetsin Python.

Part 1 - Data extraction via webscrapping  using Selenium library, to navigate through the pages and extract data, and Pandas library to create and deal with dataframes from the scrapped data, including the crime types, year, city and region.
 Data available until march 2020.  
 
 <img width="956" alt="ssp-fig" src="https://user-images.githubusercontent.com/52055874/80321175-6c2d5600-87f1-11ea-9642-dbb6e8671ee3.png">
 
Part 2 - data visualization with maps (to be released soon) 





