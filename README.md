# nycflights13

[![Travis-CI Build Status](https://travis-ci.org/hadley/nycflights13.svg?branch=master)](https://travis-ci.org/hadley/nycflights13)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/nycflights13)](https://cran.r-project.org/package=nycflights13)

This package contains information about all flights that departed from NYC
(e.g. EWR, JFK and LGA) in 2013: 336,776 flights in total. To help understand 
what causes delays, it also includes a number of other useful datasets.
This package provides the following data tables.

* `flights`: all flights that departed from NYC in 2013
* `weather`: hourly meterological data for each airport
* `planes`: construction information about each plane
* `airports`: airport names and locations
* `airlines`: translation between two letter carrier codes and names

If you're interested in other subsets of flight data, see:

* [nycflights](https://github.com/jayleetx/nycflights) for flights departing 
  from from NYC in the _last_ year.
  
* [anyflights](https://github.com/simonpcouch/anyflights) for flights departing
  from any airport in any year.
  
* [airlines](https://github.com/beanumber/airlines) to maintain a local SQL
  database of all flight departure data.
