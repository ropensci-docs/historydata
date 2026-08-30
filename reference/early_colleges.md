# Early colleges in the United States

This dataset contains information about the founding of colleges
established before 1848 in the United States of America.

## Usage

``` r
early_colleges
```

## Format

A data frame with 65 observations of 6 variables.

## Variables

- `college`: The name of the college or university.

- `original_name`: The name under which the institution was founded, if
  different.

- `city`, `state`: The location of the institution.

- `established`: The year that the institution was founded.

- `sponsorship`: The sponsoring religious denomination, or `secular` if
  not founded by a denomination.

## References

This data was transcribed by George Oberle from the table "Some American
Institutions of Higher Education Founded Before 1848, in Daniel Walker
Howe, *What Hath God Wrought: The Transformation of America, 1815-1848*
(New York: Oxford University Press, 2007), 460-461.

## Author

[George Oberle](https://library.gmu.edu/faculty/george-oberle), George
Mason University

Daniel Walker Howe

## Examples

``` r
head(early_colleges)
#> # A tibble: 6 × 6
#>   college                original_name       city  state established sponsorship
#>   <chr>                  <chr>               <chr> <chr>       <int> <chr>      
#> 1 Harvard                NA                  Camb… MA           1636 Congregati…
#> 2 William and Mary       NA                  Will… VA           1693 Anglican   
#> 3 Yale                   NA                  New … CT           1701 Congregati…
#> 4 Pennsylvania, Univ. of NA                  Phil… PA           1740 Nondenomin…
#> 5 Princeton              College of New Jer… Prin… NJ           1746 Presbyteri…
#> 6 Columbia               King's College      New … NY           1754 Anglican   
if(require(ggplot2)) {
  ggplot(early_colleges, aes(x = established)) + geom_bar(binwidth = 5) +
  ggtitle("Founding Dates of Early American Colleges")
}
#> Loading required package: ggplot2
#> Warning: Ignoring unknown parameters: `binwidth`
```
