
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Reproducibility.in.Plant.Pathology

[![Travis-CI Build
Status](https://travis-ci.org/openplantpathology/Reproducibility_in_Plant_Pathology.svg?branch=master)](https://travis-ci.org/openplantpathology/Reproducibility_in_Plant_Pathology)
[![DOI](https://zenodo.org/badge/62676177.svg)](https://zenodo.org/badge/latestdoi/62676177)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

This repository contains the data and code for our paper:

> Sparks, A.H., Del Ponte, E.M., Everhart, S., Foster, Z., Grünwald, N.
> (YYYY). *Title of paper*. Name of journal/book
> <https://doi.org/xxx/xxx>

Our pre-print is online here:

> Authors, (YYYY). *Title of paper*. Name of journal/book, Accessed 02
> Jun 2018. Online at <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Sparks, A.H., Del Ponte, E.M., Everhart, S., Foster, Z.S.L., Grünwald,
> N., (2018). *Compendium of R code and data for ‘Status and Best
> Practices for Reproducible Research In Plant Pathology’*. Accessed 02
> Jun 2018. Online at <https://doi.org/10.5281/zenodo.1250665>

### How to download or install

#### The R package

This repository is organized as an R package. There is one R function,
`doi2bib()`, that is used in this repository, along with a bibliography
file of the articles that were examined that are located in
`inst/extdata` directory. We have used the R package structure to help
manage dependencies, to take advantage of continuous integration for
automated code testing and for file organisation.

You can download the compendium as a zip from from this URL:
<https://github.com/openplantpathology/Reproducibility_in_Plant_Pathology/archive/master.zip>

Or you can install this compendium as an R package,
Reproducibility.in.Plant.Pathology, from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("adamhsparks/Reproducibility_in_Plant_Pathology")
```

Once the download is complete, open the
`Reproducibility_in_Plant_Pathology.Rproj` in RStudio to begin working
with the package and compendium files.

The package has a number of dependencies on other R packages, and
programs outside of R. These are listed at the bottom of this README.
Installing these can be time-consuming and complicated, so we’ve
provided a Docker image that includes all the necessary software, code
and data to run our analysis. The Docker image may give a quicker entry
point to the project, and is more self-contained, so might save some
fiddling with installing things.

#### The Docker image

A Docker image is a lightweight GNU/Linux virtual computer that can be
run as a piece of software on Windows and OSX (and other Linux systems).
To capture the complete computational environment used for this project
we have a Dockerfile that specifies how to make the Docker image that we
developed this project in. The Docker image includes all of the software
dependencies needed to run the code in this project, as well as the R
package and other compendium files. To launch the Docker image for this
project, first, [install Docker](https://docs.docker.com/installation/)
on your computer. At the Docker prompt,
    enter:

    docker run -dp 8787:8787 adamhsparks/reproducibility_in_plant_pathology

This will start a server instance of RStudio. Then open your web browser
at localhost:8787 or or run `docker-machine ip default` in the shell to
find the correct IP address, and log in with rstudio/rstudio.

Once logged in, use the Files pane (bottom right) to navigate to
`Reproduciblity_in_Plant_Pathology` folder for this project, and open
the `.Rproj` file for this project. Once that’s open, you’ll see the
`analysis/paper` directory in the Files pane where you can find the R
markdown document, and knit them to produce the results in the paper.
More information about using RStudio in Docker is available at the
[Rocker](https://github.com/rocker-org)
[wiki](https://github.com/rocker-org/rocker/wiki/Using-the-RStudio-image)
pages.

We developed and tested the package on this Docker container, so this is
the only platform that we’re confident it works on, and so recommend to
anyone wanting to use this package to generate the vignettes, etc.

## Meta

Code: [MIT](http://opensource.org/licenses/MIT) year: 2018, copyright
holder: Adam H Sparks

Data: [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Licenses

We used [RStudio](http://www.rstudio.com/products/rstudio/) on macOS and
Ubuntu 17.10.

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

Adam H Sparks, Associate Professor, Centre for Crop Health  
University of Southern Queensland  
Toowoomba, Queensland 4350

(+61) (7) 4831 1948 <adam.sparks@usq.edu.au>
<https://staffprofile.usq.edu.au/Profile/Adam-Sparks>
