# Consumer Price Index, 1800-2024

This dataset contains historic consumer price index (CPI) data including
estimates before the modern U.S. CPI, retrieved from the Federal Reserve
Bank of Minneapolis.

## Usage

``` r
minneapolisfed_cpi
```

## Format

A data frame with 225 observations of 3 variables.

## Details

These details are taken from
<https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1800->
and edited.

Official U.S. data go back to 1913 for a consumer price index (CPI)
comparable to what the U.S. Bureau of Labor Statistics (BLS) still
calculates today. The table below reflects the following historical
series as initially compiled by the BLS for the Handbook of Labor
Statistics, with modern CPI data from 1913 to the present day:

- 1800 to 1851 - Index of Prices Paid by Vermont Farmers for Family
  Living

- 1851 to 1890 - Consumer Price Index by Ethel D. Hoover

- 1890 to 1912 - Cost of Living Index by Albert Rees

- 1913 to 1977 - Consumer Price Index (CPI)

- 1978 to present - Consumer Price Index for all Urban Consumers (CPI-U)

The dataset uses 1967 as the index (1967=100). With the caveat that data
before 1913 should be considered estimates To find out how much a price
in Year 1 would be in Year 2 dollars:

Year 2 Price = Year 1 Price x (Year 2 CPI/Year 1 CPI)

## Variables

- `year`: date of CPI, or estimate of CPI.

- `annual_average_index`: average annual CPI, or estimate of average
  annual CPI.

- `annual_percentage_change`: annual percentage change of the CPI.

## References

This data is compiled from the Federal Reserve Bank of Minneapolis:

<https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1800->

## Examples

``` r
head(minneapolisfed_cpi)
#> # A tibble: 6 × 3
#>    year annual_average_index annual_percentage_change
#>   <int>                <dbl>                    <dbl>
#> 1  1800                   51                     NA  
#> 2  1801                   50                     -2  
#> 3  1802                   43                    -14  
#> 4  1803                   45                      4.7
#> 5  1804                   45                      0  
#> 6  1805                   45                      0  
```
