# issueyears
Stata code to determine issue years from patent numbers (for patents issued 1836-2017). 

## Background

Several patent databases include issue dates for patents since the 1970s. For example the USPTO's [PatentsView](http://www.patentsview.org/download/) data includes patent issue dates for patents issued since 1976, and the [NBER Patent Citation database](http://www.nber.org/patents/) includes issue dates for patents issued since 1963.

Historical patent data are harder to date. Fortunately, patent numbers are monotonically increasing in issue date. So we can use patent numbers to determine issue date.

## What this does

This Stata .DO file uses information from the USPTO Document [Issue Years and Patent Numbers Since 1836](https://www.uspto.gov/web/offices/ac/ido/oeip/taf/issuyear.htm) 
to determine issue year for a given patent number. It takes as input a 7-digit numeric patent number called `patent` and creates and output field `predicted_issyear`.

## TODO

1. Update to 2018
2. Add in re-issue patents





