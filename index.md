
# *naijR*: An R package on Nigeria and for Nigeria <img src="man/figures/logo.png" width=100px align="right" />

*naijR* is an R package that contains a suite of functions that make it
easier to deal with data and datasets about the country Nigeria and its
constituent parts. <br>

Inspiration for the project is drawn from experience within real data
science projects where peculiar problems are often encountered, such as:

  - **Data cleaning:** When dealing with data specific to the county,
    there are data entry issues that seem to occur quite frequently.
    Rather applying repetitious data cleaning tasks, it is better to
    encapsulate them in a way to automate them.
  - **Data point ambiguity:** Although key data are standardized by
    relevant authorities e.g. names of administrative divisions like
    Local Government Areas, it is still common to find bodies of data
    where these points are used arbitrarily and incorrectly.
  - **Dependence on idiosyncratic tools:** Many organisations in Nigeria
    defer to the use of tools that add their own layer of complexity to
    data management without due cognisance being taken of the
    peculiarities associated with local data sets. <br>

*naijR* brings an approach to data analysis that is tailored towards
enhance the productivity of anyone working with any data that has to do
with Nigeria. <br>

## Things that *naijR* can do

There are a number of things that one can to with this package. These
include:

  - List all the States of the Nigerian Federation or group them by
    geo-political zones.
  - List the Local Government Areas, either as a whole or by their
    States.
  - Check if a data structure contains an administrative division. As of
    this version, only States are supported.
  - Fix incorrectly entered mobile numbers.
  - Draw maps of Nigeria using **vector graphics**, including choropleth
    maps at State level.

*Additional functionality is being added and will be available in future
releases*.

## Getting Started

The easiest way to start using this package is within an active R
session by running

``` r
install.packages('naijR')
```

<br> This will install the **stable version** from
[CRAN](https://cran.r-project.org/package=naijR). To work with the
**development version** of the package, it can be installed from
[GitHub](https://github.com/BroVic/naijR) with

``` r
# install.packages('remotes')
remotes::install_github("BroVic/naijR")
```

<br> For an introduction to the package’s ability to draw Nigeria
country maps, read this [article](articles/nigeria-maps.html)
