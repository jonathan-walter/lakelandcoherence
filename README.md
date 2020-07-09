# lakelandcoherence
Derived data products and code from "Temporal coherence between lake and landscape primary productivity" by Walter, Fleck, Kastens, Pace, and Wilkinson.

There are three subdirectories.

"Analysis Code" contains R markdown files used to 1) prepare chlorophyll-a and NDVI time series (dataPrep) and 2) perform analyses appearing in the manuscript. The dataPrep file is included for transparency about data preparation steps,
but we do not archive all raw data due to its size; instead, we archive derived data products. Walter (jaw3es@virginia.edu) will field data requests.

"R package" contains a suite of helper functions developed for this project, wrapped up into an R package called "aqts." It is not on CRAN and should be installed locally.

"Data" contains derived data products (produced by dataPrep) and a couple other ancillary files used in our analyses. 
