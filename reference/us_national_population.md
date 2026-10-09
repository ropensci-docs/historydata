# Population of the United States, 1790-2020

Population figures for the entire United States of America from the
decennial census.

## Usage

``` r
us_national_population
```

## Format

A data frame with 24 observations of 2 variables.

## Variables

- `year`: date of the census.

- `population`: population of the state or territory.

## References

This dataset has been gathered by the [NHGIS](https://www.nhgis.org/).
Steven Manson, Jonathan Schroeder, David Van Riper, Katherine Knowles,
Tracy Kugler, Finn Roberts, and Steven Ruggles. *IPUMS National
Historical Geographic Information System: Version 19.0* \[dataset\].
Minneapolis, MN: IPUMS, 2024.
[doi:10.18128/D050.V19.0](https://doi.org/10.18128/D050.V19.0)

## Examples

``` r
head(us_national_population)
#> # A tibble: 6 × 2
#>    year population
#>   <int>      <int>
#> 1  1790    3929625
#> 2  1800    5308483
#> 3  1810    7239881
#> 4  1820    9638239
#> 5  1830   12860702
#> 6  1840   17063353
if(require(ggplot2)) {
  ggplot(us_national_population,
         aes(x = year, y = population)) +
  geom_line() +
  ggtitle("Population of the United States, 1790-2010")
}
```
