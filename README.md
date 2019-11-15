# StatsDemo

Demo package for teaching basic univariate and multivariate
statistics, originally developed for an EMBO course on computational
metabolomics In Hinxton, UK. In 2019 this package is used for the 
EMBO Practical Course:

“Metabolomics Bioinformatics in Human Health” 
16-20 September 2019, Lyon, France

at IARC.

To install the package, type in your R console:

library(devtools)
install_github("rwehrens/StatsDemo")

Then you can access the shiny exercises as follows (again, from an R console):

library(StatsDemo)
runEx("Quiz")
runEx("Plotting")
runEx("PCA")
runEx("PLS")
