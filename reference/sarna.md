# Population estimates of American Jews

This dataset contains estimates of the population of American Jews.

## Usage

``` r
sarna
```

## Format

A data frame with 92 observations of 3 variables.

## Variables

- `year`: date of estimate.

- `estimate`: the type of estimate. `population_low` and
  `population_high` are the lower and upper bounds on the population of
  American Jews; `percentage_high` and `percentage_low` are the lower
  and upper bounds on the percentage of Jews among the United States
  population.

- `value`: the value of the estimate.

## References

This data is taken from the appendix in Jonathan D. Sarna, *American
Judaism: A History* (New Haven: Yale University Press, 2004), 375-376.

## Examples

``` r
head(sarna)
#> # A tibble: 6 × 3
#>    year estimate       value
#>   <int> <fct>          <dbl>
#> 1  1660 population_low    50
#> 2  1700 population_low   200
#> 3  1776 population_low  1000
#> 4  1790 population_low  1300
#> 5  1800 population_low  2500
#> 6  1820 population_low  2650
```
