# Populations of US states and territories, 1790-2020

Population figures for US states and territories from the decennial
census.

## Usage

``` r
us_state_populations
```

## Format

A data frame with 1034 observations of 4 variables.

## Variables

- `year`: date of the census.

- `state`: name of the state or territory.

- `population`: population of the state or territory.

- `GISJOIN`: a unique identifier for joining NHGIS data to spatial data.

## References

This dataset has been gathered by the [NHGIS](https://www.nhgis.org/).
Steven Manson, Jonathan Schroeder, David Van Riper, Katherine Knowles,
Tracy Kugler, Finn Roberts, and Steven Ruggles. *IPUMS National
Historical Geographic Information System: Version 19.0* \[dataset\].
Minneapolis, MN: IPUMS, 2024.
[doi:10.18128/D050.V19.0](https://doi.org/10.18128/D050.V19.0)

## Examples

``` r
head(us_state_populations)
#> # A tibble: 6 × 4
#>   GISJOIN  year state         population
#>   <chr>   <int> <chr>              <int>
#> 1 G090     1790 Connecticut       237655
#> 2 G100     1790 Delaware           59096
#> 3 G130     1790 Georgia            82548
#> 4 G240     1790 Maryland          319728
#> 5 G250     1790 Massachusetts     475199
#> 6 G330     1790 New Hampshire     141899
```
