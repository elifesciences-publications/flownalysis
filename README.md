This code is associated with the paper from Triandafillou et al., "Transient Intracellular Acidification Regulates the Core Transcriptional Heat Shock Response". eLife, 2020. http://doi.org/10.7554/eLife.54880


# Functions for reading and analyzing flow cytometry data

This package contains helper functions to read in and analyze data in the standard .fcs format (3.0 or 3.1). Ther
e are specificities to data generated on instruments at The University of Chicago Flow Cytometry core, but many functions can be modified so that they are generally applicable. Functions in this package can be used to analyze data from and generate the figures for 'Transient Intracellular Acidification Regulates the Core Transcriptional Heat Shock Response' by Triandafillou et al., eLife 2020. Note that the R version used for this work was 3.3.3 (Another Canoe), and have not been tested extensively with more recent versions of R.

To install directly from R, use the ```install_github``` function from ```devtools```:

```install_github("ctriandafillou/flownalysis")```
