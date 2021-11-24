# COVID.19 DATABASE PHP


## Description

This COVID19 DATABASE Based On 『K_COVID19.csv』 And 『addtional_Timeinfo.csv』  
Before start these php file,you must have a 『dbconfig.php』 in same folder.


## Table Name

* THE_CASE
* PATIENTINFO
* REGION
* WEATHER
* TIMEINFO
* TIMEAGE
* TIMEGENDER
* TIMEPROVINCE

## PHP File

* 【내용1】case.php
* 【내용1】patientinfo.php
* 【내용1】region.php
* 【내용1】timeinfo.php
* 【내용1】weather.php
* 【내용2】case_select_province.php
* 【내용2】patientinfo_select_country.php
* 【내용2】weather_select_wdate.php
* 【내용3】date_province_sex.php

## 내용3 date_province_sex.php

SQL in PHP —— select confirmed_date,province,COUNT(IF(sex='male',true,null)) as male_confirmed_num,COUNT(IF(sex='female',true,null)) as female_confirmed_num from patientinfo where confirmed_date='{$date_value}' GROUP BY province with ROLLUP;

Function —— Select date firstly,and then click 【load】,website will list The number of males and females infected in each province on the same date 

## Language

Korean
English


## Credits -- Team 20 Members
* 천스위
* 윤영우


## More
I upload all php file on personal website,so it is possible to ask these php files online,But the mysql connect is based on cobi.knu.ac.kr  
【내용1】  
http://mwgmonsun.com/patientinfo.php  
http://mwgmonsun.com/region.php  
http://mwgmonsun.com/weather.php  
http://mwgmonsun.com/timeinfo.php  
http://mwgmonsun.com/case.php  
  
【내용2】  
http://mwgmonsun.com/patientinfo_select_country.php  
http://mwgmonsun.com/case_select_province.php  
http://mwgmonsun.com/weather_select_wdate.php  
  
【내용3】  
http://mwgmonsun.com/date_province_sex.php  
