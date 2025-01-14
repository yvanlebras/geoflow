geoflow – R engine to orchestrate and run geospatial (meta)data
workflows - List of accessors and handlers
================

# 1 Accessors

## 1.1 List of accessors supported by geoflow

| id                                    | software\_type | definition                            | packages         |
| :------------------------------------ | :------------- | :------------------------------------ | :--------------- |
| [**default**](#default)<br>           |                | A default HTTP(S) data accessor       |                  |
| [**googledrive**](#googledrive)<br>   | googledrive    | A Google Drive data accessor          | googledrive      |
| [**zenodo**](#zenodo)<br>             |                | A Zenodo public data accessor         | zen4R            |
| [**d4storagehub**](#d4storagehub)<br> | d4storagehub   | A D4science Storage Hub data accessor | d4storagehub4R   |
| [**gbif**](#gbif)<br>                 | gbif           | A gbif public data accessor           | rgbif            |
| [**thredds**](#thredds)<br>           | thredds        | A Thredds data server accessor        | thredds,httr,XML |

# 2 Handlers

## 2.1 List of handlers supported by geoflow

| id                                         | definition                                                              | packages                   |
| :----------------------------------------- | :---------------------------------------------------------------------- | :------------------------- |
| [**csv**](#csv)<br>                        | Handle metadata entities from a CSV file                                |                            |
| [**excel**](#excel)<br>                    | Handle metadata entities from a Microsoft Excel (xls,xlsx) file         | readxl                     |
| [**gsheet**](#gsheet)<br>                  | Handle metadata entities from a Google spreadsheet                      | gsheet                     |
| [**dbi**](#dbi)<br>                        | Handle metadata entities from a DB source                               | DBI,RSQLite,RPostgres      |
| [**ncdf**](#ncdf)<br>                      | Handle metadata entities from a Netcdf source                           | ncdf4                      |
| [**ncml**](#ncml)<br>                      | Handle metadata entities from a NCML source                             | XML                        |
| [**thredds**](#thredds)<br>                | Handle metadata entities from a Thredds server source                   | ncdf4,thredds,XML,png,curl |
| [**thredds\_csv**](#thredds_csv)<br>       | Handle metadata thredds entities from a CSV file                        |                            |
| [**thredds\_excel**](#thredds_excel)<br>   | Handle metadata thredds entities from a Microsoft Excel (xls,xlsx) file | readxl                     |
| [**thredds\_gsheet**](#thredds_gsheet)<br> | Handle metadata thredds entities from a Google spreadsheet              | gsheet                     |
