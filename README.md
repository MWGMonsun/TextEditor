# COVID.19 DATABASE


## Description

This COVID19 DATABASE Based On 『K_COVID19.csv』 And 『addtional_Timeinfo.csv』

## Ability

>8 tables through data extraction and classification of individual cases and insert data with python


## Table

* THE_CASE
* PATIENTINFO
* REGION
* WEATHER
* TIMEINFO
* TIMEAGE
* TIMEGENDER
* TIMEPROVINCE

## Python File

* add_case.py
* add_patientinfo.py
* add_region.py
* add_weather.py
* add_timeinfo.py
* add_timeage.py
* add_timegender.py
* add_timeprovince.py

### Data Insert

* You Must Set host url before insert data,the default host is 127.0.0.1
* And there must be a Database CREATE BY COVID19.sql
* Both of『K_COVID19.csv』 And 『addtional_Timeinfo.csv』Must be in same floder with 8 python files.
* Then Run Python File To Insert data into this Database 
* Python version must above 3 ,check your python version,if it is python2,may be error

### Every Table Key

* Table Variable Key

* THE_CASE: case_id

* PATIENTINFO: patient_id

* REGION: region_code

* WEATHER: region_code,wdate 

* TIMEINFO: 

* TIMEAGE:   

* TIMEGENDER:  

* TIMEPROVINCE :



## Installation

Please Use COVID19.sql To Create DATABASE And Tables

## Environment

Above MySQL 5.7.26
Above Python 3

## Language

English


## Credits -- Team 20 Members
* 윤영우
* 천스위
