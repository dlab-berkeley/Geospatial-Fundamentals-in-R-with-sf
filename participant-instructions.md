# Participant instructions

## Prior to the workshop start date please do the following.

1. Download and unzip (or clone, using the `git clone` command) this workshop. To download, just click on the green **CODE** button near the top of the repo's home page: https://github.com/dlab-berkeley/R-Geospatial-Fundamentals
    
    > Note: The files are typically updated prior to a workshop, so it's good to download these just before the workshop.


2. If you do not have R and RStudio installed on your computer, download and install [RStudio Desktop](https://rstudio.com/products/rstudio/) with R version >= 3.5.

3. Then open RStudio and install the following R packages, using the syntax **install.package('pkg_name')** 
  * `sf`
  * `here`
  * `tmap`
  * `units`
  * `tidyverse`
  * `raster`
  * `ggplot2`
  * `mapview`

If you are __prompted by the question__ "Do you want to install from sources the package which needs compilation? (Yes/no/cancel)", type "**no**" in your console and press Enter. (***Note**: This is most common for Mac users.*)

<!-- 
TO DO add confirmation code that their packages are installed correctly
4. After installation is complete, open the ['01-core_concepts_and_plotting.html'](https://dlab-berkeley.github.io/Geospatial-Fundamentals-in-R-with-sf/01-core_concepts_and_plotting.html#1) file in the 'docs' folder, to launch Pthe slides for Part I.
-->

> Contact us with any questions at `dlab.berkeley.edu/frontdesk`!

## At the start of the workshop

1. Open RStudio.

2. In the lower-right Files tab, navigate to the folder that contains the workshop files: **R-Geospatial-Fundamentals**.

3. Click on **More > Set as Working Directory** to set your R working directory to the folder with the workshop files.

4. Open the `Rmd` file in the `docs` folder for the current lesson, e.g. `02_Introduction_to_sf.Rmd'. You can follow along by executing the code in the Rmd file.

5. You can also open a new, empty R script file: **RStudio > File > New File > R Script** and type in the code.


 
