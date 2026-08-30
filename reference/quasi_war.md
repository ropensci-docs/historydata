# Naval encounters during the Quasi War between France and the United States of America

Naval encounters during the Quasi War between France and the United
States of America

## Usage

``` r
quasi_war
```

## Format

A data frame with 198 observations of 16 variables.

## References

This data was gathered by [Abby Mullen](https://abbymullen.org/).

## Examples

``` r
head(quasi_war)
#> # A tibble: 6 × 16
#>   date       ship_1_name   ship_1_type         ship_1_nationality ship_2_name   
#>   <date>     <chr>         <chr>               <chr>              <chr>         
#> 1 1798-09-28 America       armed merchant ship USA                "privateer"   
#> 2 1798-07-11 American      armed merchant ship USA                "3 privateers"
#> 3 1798-09-27 Amphitrite    armed merchant ship USA                "ship  "      
#> 4 1798-05-09 Belvedere     armed merchant ship USA                "privateer sl…
#> 5 1798-04-22 Boston Packet armed brig          USA                "2 brigand bo…
#> 6 1798-12-28 Camilla       armed merchant ship USA                "2 privateers"
#> # ℹ 11 more variables: ship_2_nationality <chr>, location <chr>, lat <dbl>,
#> #   long <dbl>, outcome <chr>, source <chr>, engagement_type <chr>,
#> #   status <chr>, year <dbl>, month <dbl>, day <int>
```
