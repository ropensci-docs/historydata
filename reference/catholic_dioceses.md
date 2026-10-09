# Roman Catholic dioceses in the United States, Canada, and Mexico

Dates when Roman Catholic dioceses and archdioceses in the United States
were founded or made metropolitan sees, with geocoded locations. The
sources cited indicate that none of these sees have been discontinued.

## Usage

``` r
catholic_dioceses
```

## Format

A data frame with 425 observations of 6 variables.

## Variables

- `diocese`: name, and thus location, of the diocese.

- `event`, `date`: the date when the diocese was `erected`, that is
  first founded, or made a `metropolitan` see. Encoded as a date object.

- `rite`: the rite overseen by the diocese. Regions with ordinary
  jurisdiction but not episcopal character are not included.

- `lat`, `long`: latitude and longitude coordinates for the headquarters
  city of the diocese.

## References

This data is compiled from several sources:

Joseph Bernard Code, *Dictionary of the American Hierarchy (1789-1964)*
(New York: Joseph F. Wagner, 1964), 425-26.

For the United States since 1963, Canada, and Mexico:
<https://www.catholic-hierarchy.org/>

## Examples

``` r
head(catholic_dioceses)
#> # A tibble: 6 × 6
#>   diocese                    rite    lat  long event   date      
#>   <chr>                      <chr> <dbl> <dbl> <chr>   <date>    
#> 1 Baltimore, Maryland        Latin  39.3 -76.6 erected 1789-04-06
#> 2 New Orleans, Louisiana     Latin  30.0 -90.1 erected 1793-04-25
#> 3 Boston, Massachusetts      Latin  42.4 -71.1 erected 1808-04-08
#> 4 Louisville, Kentucky       Latin  38.3 -85.8 erected 1808-04-08
#> 5 New York, New York         Latin  40.7 -74.0 erected 1808-04-08
#> 6 Philadelphia, Pennsylvania Latin  40.0 -75.2 erected 1808-04-08
```
