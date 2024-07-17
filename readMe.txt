
# Create gene of interest report.
%> cd GOI_report
%> Rscript buildReport.R

   Note that the final call to rmarkdown::render() may throw a pandoc error 
   on some installations. This can often be overcomed by running buildReport.R
   within Rstudio.
   