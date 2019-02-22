# AK bearded and spotted seal example dataset and analysis

This is a compendium of example data and code designed to help end users explore
the crawl package for analysis of animal movement from telemetry data.

The `crawl` package is an R package that provides analytical tools for
estimating the movement paths of animals from telemetry data. The package is
specifically designed with marine mammals in mind, but other species in other
habits with similar telemetry devices will work. This package compendium
provides step-by-step instructions for importing and setting up the telemetry
data, initiating the `crwMLE()`, `crwPredict(), and
`crwSimulator()`/'crwPostIS()` functions and visualizing results. The write up
also discusses use of the `fix_path()` function to re-route predicted tracks
around land. Examples of data visualization plots are also presented. This
compendium was originaly developed in support of a training course at the NOAA
Fisheries Protected Species Assessment Workshop in La Jolla, California, USA.

## Installation

You can install the released version of `crwexampleakbs` from GitHub with:

``` r
install.packages("devtools")
devtools::install_github('jmlondon/crwexampleakbs')
```

## Documentation and Examples

See [the vignette](https://jmlondon.github.io/crwexampleakbs/analysis.html) for a 
detailed discussion of the data, example analysis, and visulaization plots.

## Data Availability and Citation

The data provided for this are available from
[DataONE](https://search.dataone.org/view/10.24431/rw1k118) 
and, if used, should be cited as

> Cameron, Michael, Josh London, Kathy Frost, Alex Whiting, and Peter Boveng. 2017. Satellite Telemetry Dataset (Raw): Juvenile Bearded and Spotted Seals, 2004-2006, Kotzebue, Alaska. Research Workspace. DOI: 10.24431/rw1k118

*************************************************

##### Disclaimer

<sub>This repository is a scientific product and is not official communication of the Alaska Fisheries Science Center, the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All AFSC Marine Mammal Laboratory (AFSC-MML) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. AFSC-MML has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.</sub>
