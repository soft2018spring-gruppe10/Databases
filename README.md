# Databases
This repository is for database things in a project for Software development (PBA) in Test and Database course.

## Data

### [CitiesFinal.csv](https://github.com/soft2018spring-gruppe10/Databases/blob/master/CitiesFinal.csv)
id | name | asciiname | latitude | longitude | cc | population
-----:|:-------:|:---------|:-------:|:---------:|:------:|:-----
integer | name of city | name of city in ascii | latitude in double/float | longitude in double/float | country code as 2 letters | population in integer

This .csv file has been obtained from: http://download.geonames.org/export/dump/.

Version cities15000.csv. The data has been heavily refractored to make it easier to work with. Delimiter has been changed from tab to coma, and a few colomns has been removed because they were not usefull for us.

### [Books.csv](https://github.com/soft2018spring-gruppe10/Databases/blob/master/Books.csv)
id | title | author 
-----:|:-------:|:--------
integer | title of book | author of book

This .csv file has been obtained from a program we've build to capture and store relevant data from many books (.txt) files. The program can be found in this repository [BookParser](https://github.com/soft2018spring-gruppe10/Databases/blob/master/BookParser/src/main/java/main.java).

## [BookMentions.csv](https://github.com/soft2018spring-gruppe10/Databases/blob/master/BookMentions.csv)
bookid | cityid 
-----:|:-------
integer of bookid | integer of cityid

This .csv file has been obtained from a program we've build to capture and store relevant data from many books (.txt) files, by also corssreferencing from all the cities in "Cities csv file". The program can be found in this repository [BookParser](https://github.com/soft2018spring-gruppe10/Databases/blob/master/BookParser/src/main/java/main.java).


