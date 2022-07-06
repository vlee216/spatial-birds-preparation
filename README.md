# spatial-birds
Code documentation for the manuscript "Spatial modeling of the relative abundance of wading birds in peninsular Florida using citizen science data".

Part 1: Code for loading eBird data for a selected species.

Part 2: Code for preparing GIS, MODIS, and elevation data; code for preparing environmental covariates; code for merging environmental covariates with species datasets. 

Part 3: Code for cleaning the data prior to modeling and multicollinearity analysis.

Part 4: Code for modeling the data using Poisson, quasi-Poisson, negative binomial, and zero-inflated Poisson GLMs; code for modeling with quasi-Poisson, negative binomial, and zero-inflated Poisson GAMs; code for calculating MAD values for the 2017 test set.

Part 5: Code for generating neighbor and weight objects; code for fitting a quasi-Poisson HGAM; code for HGAM p-values and MAD values.

Part 6: Code for generating MAD values for quasi-Poisson GAMs and HGAMs given the full test set, the test set with just zeros, and the test set with just nonzeros.

Part 7: Code for producing quasi-Poisson GAM and HGAM effect displays for the "time observations started", wetland, and urban covariates.

Part 8: Code for producing the wetland map; code for producing quasi-Poisson GAM and HGAM prediction plot maps.
