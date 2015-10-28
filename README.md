INFM600 - Information Organization Assignment
=======

This project deals with the search, organization and analysis of Howard County data. 
Data sets used are specific to Howard County Day Care Centers, Maryland Demographic Profile and Tax Stats.


Objective
----------

To identify the distribution pattern of Day Care Centers in regards with the population density across Howard County.


Version
-------------
Version 1.0 (October 2015)


Table of Contents
-------------

* [Maryland Population Zipcode](https://github.com/aajmani/INFM600/raw/master/Maryland_Population_Zipcode.xls)

* [Maryland Day Care Centers](https://github.com/aajmani/INFM600/raw/master/Maryland_Day_Care_Centers.xls)

* [Howard County Day Care, Zipcode and Population Analysis](https://github.com/aajmani/INFM600/raw/master/Howard%20County%20Day%20Care%2C%20Zipcode%20and%20Population%20Analysis.xls)

* [Process Document]()
        
* [License](https://github.com/aajmani/INFM600/raw/master/LICENSE)
      

Description
------------

**Maryland_Day_Care_Centers.xls**

This data set acts as the 'Focal' data set. It provide details about the Day Care Centers across Howard County. It provides details like their name, location, contact detail etc. Name and Zipcode columns have been referred for deriving useful analysis. 


**Maryland_Population_Zipcode.xls** 

This data set provides information on Demographic Profile of Maryland State. It includes content like Zipcode, Arealand etc. For project purpose a subset of this data set has been created and used, which focusses only on the cities in Howard County. ZCTA5 and POP100 columns have been referred for deriving useful analysis.


**Howard County Day Care, Zipcode and Population Analysis.xls**

This data set has been created as a result of performing Join operation on records from 'Maryland_Population_Zipcode.xls' and 'Maryland_Day_Care_Centers.xls' using 'Zipcode' as the common field. It can act as a new data set or can simply be used to derive useful analysis and find new trends. 

This data set has been created as a part of Information Organization Assignment for INFM 600, Fall 2015, University of Maryland. 

**Process Document**

Process document provides the step by step instruction to merge the Maryland_Day_Care_Centers.xls (Focal data set) with Maryland_Population_Zipcode.xls.

**License**

License under which the derived data is distrubuted.


**References**

**Maryland_Population_Zipcode.xls** 

```

Department of Planning Maryland State Data Center. (2011). Zip Code Tabulation Areas [Data set]. Retrieved from http://census.maryland.gov/census2010/SF1DP/cen10_SF1DP.shtml Date Accessed: 10/24/2015

```

**Maryland_Day_Care_Centers.xls**

```

Howard County Maryland. (2014). Day Care Centers – Commercial [Data set]. Retrieved from https://data.howardcountymd.gov/ Date Accessed: 10/24/2015

```

**Howard County Day Care, Zipcode and Population Analysis.xls**

```

Ajmani, A. (2015). Howard County Day Care and Population Analysis [Data set]. Available at https://github.com/aajmani/INFM600 

```

**Maryland_IRS_SOI_Tax_Stats.xls**

```

Internal Revenue Service. (2011). Individual Income Tax Returns: Selected Income and Tax Items by State, ZIP Code, and 
Size of Adjusted Gross Income, Tax Year 2011 [Data set]. Retrieved from https://www.irs.gov/pub/irs-soi/11zp21md.xls Date Accessed: 10/25/2015

```

Conclusion
-----------

Question: Which cities need more day care centers?

For answering this question, number of day care centers, population by city and number of working parents with children can be merged to understand the need for more day care centers. In order to derive at number of working parents with children in a particular city, data from IRS dataset is considered. Number of child tax credit returns from the IRS dataset relates to number of working parents with children.  

By plotting a graph with population of working parents, population of city and the corresponding number of day care centers in the city, we can understand the demand for day care centers. The county can use this data to analyse which cities need more day care centers.

Approximate conclusions can also be derived on which cities have families with more kids. 


![Zipcode vs Number of Day Care Center](https://github.com/aajmani/INFM600/raw/master/Data%20Analysis/Zipcode%20vs%20Number%20of%20Day%20Care%20Center.jpg)
![Zipcode vs Population](https://github.com/aajmani/INFM600/raw/master/Data%20Analysis/Zipcode%20vs%20Population.jpg)
![Zipcode vs Population and Number of Day Care Centers](https://github.com/aajmani/INFM600/raw/master/Data%20Analysis/Zipcode%20vs%20Population%20and%20Number%20of%20Day%20Care%20Centers.jpg)


Data Format
-----------

Howard County Day Care, Zipcode and Population Analysis.xls

| Zipcode       | Count of Day Care Center| Population |
| ------------- |:-----------------------:| ----------:|

License
-----------
Copyright [2015] [Apoorva Ajmani]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Author
----------
Apoorva Ajmani