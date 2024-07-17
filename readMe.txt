
# Create gene of interest report.
%> cd GOI_report
%> Rscript buildReport.R

   Note that the final call to rmarkdown::render() may throw a pandoc error 
   on some installations. This can often be overcomed by running buildReport.R
   within Rstudio.
   
   The buildReport.R script will create a BED file named tracks.ucsc.
   This file should be moved to a webserver and placed in a location pointed 
   to by the URL defined by the config file parameter 'scanStatsBEDfileURL'.
   