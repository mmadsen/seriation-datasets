# Data Sources #

## Smith and Neiman 2007 #

The `SmithAndNeiman` directory contains data sets analyzed by Karen Y. Smith and Fraser Neiman in their 2007 Southeastern Archaeology paper on Deep South Woodland assemblages.  The main data set is the `MidLateWoodlandData.csv` file, which is downloaded directly from Neiman's website and modified only to have the final "total" column removed (since it would be mistaken for just another type count in most seriation programs, including our IDSS tools).

The Kolomoki data are different collection units from the Kolomoki site, and are included here for completeness, not because you'd use classic frequency seriation to analyze them.  

No geographic coordinates are available at present for these assemblages, so the IDSS function for calculating the geographic significance of seriation neighbor patterns is not available for these data.

## Phillips, Ford, and Griffin 1951 ##

The `PhillipsFordGriffin` directory contain ceramic assemblages derived from the original PFG 1951 publication, subsetted by Carl P. Lipo for his 2001 Ph.D. dissertation and used by Mark E. Madsen in his dissertation work.  The file `pfg-cpl.txt` represents the subset of assemblages Lipo employed after removing assemblages too small to represent stable sample sizes, and after removing plain pottery types from the tabulations, and from the Memphis and St. Francis survey areas.  The file `pfg-big.txt` contains assemblages from the entire survey region, with plain types removed and > 30 decorated sherds in the sample.  

Both data files are accompanied by XY files with geographic coordinates, to faciitate significance analysis of spatial clustering of the seriation results.
