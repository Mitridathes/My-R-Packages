# My-R-Packages

A repo to remind me usefull R packages

If you have version problems with packages, you can override the default repo in your <code>install.pacakes</code> call (i.e. rmarkdown
case):

<code>install.packages("rmarkdown", repos="https://cloud.r-project.org")</code>

WARNING

This caused me some problems installing other packages, so it might be done carefully.
I had to reinstall R and RStudio removing all configs.

## Writing documents

### knitr

A General-Purpose Package for Dynamic Report Generation in R

### markdown

'Markdown' Rendering for R

### slidify

Transforms markdown documents into slide presentations

### cacher

Caches data objects so in reproductible computations you don't need to recreate the whole environment.

## Plotting data

### plotly

Create Interactive Web Graphics via 'plotly.js

Create interactive web graphics from 'ggplot2' graphs and/or a custom interface to the (MIT-licensed) JavaScript library 'plotly.js' inspired by the grammar of graphics.

### ggplot2

Create Elegant Data Visualisations Using the Grammar of Graphics.
A system for 'declaratively' creating graphics, based on "The Grammar of Graphics". You provide the data, tell 'ggplot2' how to map 
variables to aesthetics, what graphical primitives to use, and it takes care of the details.

### lattice

A powerful and elegant high-level data visualization system inspired by Trellis graphics, with an emphasis on multivariate data. Lattice 
is sufficient for typical graphics needs, and is also flexible enough to handle most nonstandard requirements. See ?Lattice for an 
introduction.

## Colour

### RColorBrewer

Provides color schemes for maps (and other graphics) designed by Cynthia Brewer as described at http://colorbrewer2.org

## Analysing data frames

### dtplyr

This implements the data table back-end for 'dplyr' so that you can seamlessly use data table and 'dplyr' together.

### dplyr

A fast, consistent tool for working with data frame like objects, both in memory and out of memory.

### readr

The goal of 'readr' is to provide a fast and friendly way to read rectangular data (like 'csv', 'tsv', and 'fwf'). It is designed to flexibly parse many types of data found in the wild, while still cleanly failing when data unexpectedly changes.

### data.table 

A package that is used to work with large data frames in a more efficient way than the base R language does.

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

### lubridate

Functions to work with date-times and time-spans: fast and user friendly parsing of date-time data, extraction and updating of components of a date-time (years, months, days, hours, minutes, and seconds), algebraic manipulation on date-time and time-span objects. The 'lubridate' package has a consistent and memorable syntax that makes working with dates easy and fun. Parts of the 'CCTZ' source code, released under the Apache 2.0 License, are included in this package. See <https://github.com/google/cctz> for more details.

## String manipulation

### stringr

Simple, Consistent Wrappers for Common String Operations

## Pipe operator

### magrittr
Provides a mechanism for chaining commands with a new forward-pipe operator, %>%. 

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

## Imputing the data (missing data)

This uses the k nearest neighbors to calculate a values to use in place of the missing data. You may want to specify an integer k which
indicates how many neighbors you want to average to create this replacement value. The bioconductor package (http://bioconductor.org)
has an impute package which you can use to fill in missing data. One specific function in it is impute.knn.

### bioconductor

## Web apps and interactivity

### shiny

Web Application Framework for R.
Makes it incredibly easy to build interactive web applications with R. Automatic "reactive" binding between inputs and outputs and extensive prebuilt widgets make it possible to build beautiful, responsive, and powerful applications with minimal effort.

### miniUI

Shiny UI Widgets for Small Screens.
Provides UI widget and layout functions for writing Shiny apps that work well on small screens.
