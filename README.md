# My-R-Packages
A repo to remind me usefull R packages

## Analysing data frames

### dplyr

A fast, consistent tool for working with data frame like objects, both in memory and out of memory.

### readr

The goal of 'readr' is to provide a fast and friendly way to read rectangular data (like 'csv', 'tsv', and 'fwf'). It is designed to flexibly parse many types of data found in the wild, while still cleanly failing when data unexpectedly changes.

### data.table 

A package that is used to work with data frames in a more efficient way than the base R language does.

### sqldf

The sqldf package allows for execution of SQL commands on R data frames.

## Statistic analysis

### hmisc

Contains many functions useful for data analysis, high-level graphics, utility operations, functions for computing sample size and power, importing and annotating datasets, imputing missing values, advanced table making, variable clustering, character string manipulation, conversion of R objects to LaTeX and html code, and recoding variables.

## Subsetting and sorting data

### plyr
tools for Splitting, Applying and Combining Data

### hmisc
 Contains many functions useful for data analysis, high-level graphics, utility operations, functions for computing sample size and power, importing and annotating datasets, imputing missing values, advanced table making, variable clustering, character string manipulation, conversion of R objects to LaTeX and html code, and recoding variables.

## Reshaping

### tidyr

An evolution of 'reshape2'. It's designed specifically for data tidying (not general reshaping or aggregating) and works well with 'dplyr' data pipelines.

### reshape2

Flexibly restructure and aggregate data using just two functions: melt and 'dcast' (or 'acast').

## Dates-times

### lubrydate

Functions to work with date-times and time-spans: fast and user friendly parsing of date-time data, extraction and updating of components of a date-time (years, months, days, hours, minutes, and seconds), algebraic manipulation on date-time and time-span objects. The 'lubridate' package has a consistent and memorable syntax that makes working with dates easy and fun. Parts of the 'CCTZ' source code, released under the Apache 2.0 License, are included in this package. See <https://github.com/google/cctz> for more details.

## String manipulation

### stringr

Simple, Consistent Wrappers for Common String Operations

## Reading files
### Read excel files:
#### xlsx 
(read excel files) 
	
	JAVA PROBLEMS (https://github.com/lgreski/datasciencectacontent/blob/master/markdown/cleaningData-javaAndXLSX.md)
	
#### Openxlsx
 (if xlsx runs into java problems)
#### XLConnect
	XLConnect vignette is a good place to start for that package
	
	
### Read XML files

#### xml

### Read JSON files

#### jsonlite

### Reading MySQL databases

#### Step 1 - Install MySQL	

	[http://dev.mysql.com/doc/refman/5.7/en/installing.html](http://dev.mysql.com/doc/refman/5.7/en/installing.html)
	---
	## Step 2 - Install RMySQL
	* On a Mac: ```install.packages("RMySQL")```
	* On Windows: 
	* Official instructions - [http://biostat.mc.vanderbilt.edu/wiki/Main/RMySQL](http://biostat.mc.vanderbilt.edu/wiki/Main/RMySQL) (may be useful for Mac/UNIX users as well)
	* Potentially useful guide - [http://www.ahschulz.de/2013/07/23/installing-rmysql-under-windows/](http://www.ahschulz.de/2013/07/23/installing-rmysql-under-windows/) 

Desde <https://github.com/DataScienceSpecialization/courses/blob/master/03_GettingData/02_01_readingMySQL/index.Rmd#L74> 

### Read HDF5 files

#### Rhdf5

source("http://bioconductor.org/biocLite.R")
biocLite("rhdf5")

### Reading data from the web

#### httr 

### Reading data from other sources

#### foreign 

* Loads data from Minitab, S, SAS, SPSS, Stata,Systat
* Basic functions _read.foo_
  * read.arff (Weka)
  * read.dta (Stata)
  * read.mtp (Minitab)
  * read.octave (Octave)
  * read.spss (SPSS)
  * read.xport (SAS)
* See the help page for more details [http://cran.r-project.org/web/packages/foreign/foreign.pdf](http://cran.r-project.org/web/packages/foreign/foreign.pdf)
