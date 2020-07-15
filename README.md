### Tobin's Q Theory of Investment Applied to the United States Housing Market


### Overview
This M.S. Project focuses on [Tobin’s Q theory](https://en.wikipedia.org/wiki/Tobin%27s_q) and applies Tobin's Q to the United States housing market. My research follows the work published by [Jud & Winkler](https://libres.uncg.edu/ir/uncg/f/D_winkler_Q_2003%20(MULTI%20UNCG%20Authors).pdf) and aims to replicate their findings using the same data. The research question: Does Tobin’s Q serve as an accurate indicator for residential investment in the United States housing market?

### Programs used:
1. R version 4.0.0 (2020-04-24)
2. Latex
3. Git version 2.25.0.windows.1

### R packages used:
* vars 1.5-3  
* forecast 8.12
* astsa 1.10
* aTSA 3.1.2
* ggplot2_3.3.1
* readxl 1.31



### Data
The data is focused on the entire U.S. population and ranges from 1979 Q4 to 2000 Q4 and is measured quarterly. Building starts & housing permits is published monthly. We measure Tobin's Q ratio as the price index for existing homes over the price index for new homes (replacement cost). The data collected are the same variables that Jud & Winkler used for their research.

* [Existing housing price index](https://www.fhfa.gov/DataTools/Downloads/Documents/HPI/HPI_AT_us_and_census.txt) - Published as "U.S. and Census Divisions (Not Seasonally Adjusted)"   

* [New housing price Index](https://www.census.gov/construction/cpi/historical_data/) - Published as "Price Indexes For New Single-Family Houses (Base Year 1996)"

* [Housing Starts](https://www.census.gov/construction/nrc/historical_data/index.html) Published as "Housing Units Started by Purpose and Design", the "total" column is the data used.

* [Housing Permits](https://www.census.gov/construction/nrc/historical_data/index.html) Published as "Housing Units Authorized in Permit‐Issuing Places" <p>
 To obtain quarterly data for housing permits, simply sum every three observations to obtain quarterly data. The "1-unit" column is the data used.

* [Residential Investment](https://apps.bea.gov/histdata/fileStructDisplay.cfm?HMI=7&DY=2002&DQ=Q3&DV=2.%20Preliminary&dNRD=November-26-2002) Published on Section 5 Saving and Investment - Excel sheet labeled "504 Qtr", row 26 (Structures)
