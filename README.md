# BART Peak Period Pricing Sketch Model
This research applies sketch modeling to estimate how more complex fare structures could manage congestion and increase revenue on the Bay Area Rapid Transit (BART) system. BART is an excellent case study because it already applies a relatively complex fare structure based on origin and destination. This exploration is motivated by an interest in making BART more efficient. BART experiences highly peaked ridership and is considering costly new investments to expand capacity. BART is also grappling with a substantial deferred maintenance deficit.

<img width="813" alt="screen shot 2017-02-20 at 12 29 20 pm" src="https://cloud.githubusercontent.com/assets/830005/23140759/3ce95bcc-f768-11e6-8e04-9793bccbfe26.png">

## Contents
This repository holds a PDF report, a PDF poster, and an Excel spreadsheet.
* The PDF report is a draft of a report published by the Transportation Research Board of North America (TRBNA) in 2013. The final report is available on the [TRBNA website](http://amonline.trb.org/trb-59976-2013a-1.2504412/t13031-1.2512649/421-1.2512315/13-1378-1.2512719/13-1378-1.2512724?qr=1) (subscription required).
* The PDF poster was presented at the TRBNA conference in 2013.
* The Excel spreadsheet was developed for research purposes, and its data has not been updated since 2012. 


## Running the Model
This spreadsheet relies on a companion dataset of BART ridership data. BART graciously gave us a sample of 2012 ridership data to build the model. We averaged across a representative set of weekdays to build a baseline. The model will work with any baseline you care to compare against, including the monthly ridership spreadsheets available on [BART's website](http://www.bart.gov/about/reports/ridership). 
It is formatted to match the standard output format from BART, and requires only a few formula references be changed to connect. These files are quite large, and we recommend turning on manual cell execution. 

## Authors
The research and model were created by Matthew Schabas and Ruth Miller during their second year of the Master of City Planning program at the University of California – Berkeley's Department of City and Regional Planning.

## License
The contents of this repository are licensed by their authors under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html).
