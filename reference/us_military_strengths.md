# US Military Strengths

Active Duty US Military Personnel by Regional Area and by Country:
Worldwide Manpower Distribution by Geographical Area

## Usage

``` r
us_military_strengths
```

## Format

A data frame with 50 observations of 27 variables.

## Details

This data subset was extracted and transcribed in February 2018 from 48
individual DoD military troop strength yearly reports which varied in
composition over time according to requirements mandated by Congress.
The compiled spreadsheet covers the period 1950-1999, less the years
1951-1952 which are not available. It includes total military personnel,
the numbers in the U.S. and overseas, the totals by military Service,
and the figures for some twenty countries in which the United States had
a significant military presence for much or all of the period. The
original DoD reports are a mix of .pdf and .xls formats downloaded in
one.zip file from the section “Historical Publications” at the bottom of
the DMDC reports page. The country column headings in this spreadsheet
use the ISO 3166 Alpha-2 country codes from the ISO Online Browsing
Platform (OBP) at <https://www.iso.org/obp/ui/#search>.

Clarke Bursley put this data together.

## References

Defense Manpower Data Center, “Active Duty Military Personnel by
Regional Area and by Country: Worldwide Manpower Distribution by
Geographical Area (M05), Historical Reports - Military Only - 1950,
1953 - 1999,” DoD Personnel, Workforce Reports & Publications,
[www.dmdc.osd.mil/appj/dwp/dwp_reports.jsp](https://docs.ropensci.org/historydata/reference/www.dmdc.osd.mil/appj/dwp/dwp_reports.jsp)

## Examples

``` r
head(us_military_strengths)
#> # A tibble: 6 × 27
#>    Year   Total   CONUS  OCONUS     USA    USN   USMC   USAF    PA    GU     JP
#>   <dbl>   <dbl>   <dbl>   <dbl>   <dbl>  <dbl>  <dbl>  <dbl> <dbl> <dbl>  <dbl>
#> 1  1950 1460261  952600  328392  593167 381538  74279 411277 10716 17127 115306
#> 2  1951      NA      NA      NA      NA     NA     NA     NA    NA    NA     NA
#> 3  1952      NA      NA      NA      NA     NA     NA     NA    NA    NA     NA
#> 4  1953 3555067 2338379 1216688 1533815 794440 249219 977593 14028 16225 185829
#> 5  1954 3279579 2159404 1120175 1384983 711107 221818 961671 12064 15849 185705
#> 6  1955 2930863 2003012  927851 1109543 660254 201579 959487 13539 11859 162075
#> # ℹ 16 more variables: OKI <dbl>, KR <dbl>, PH <dbl>, TW <dbl>, VN <dbl>,
#> #   TH <dbl>, CA <dbl>, FR <dbl>, DE <dbl>, GB <dbl>, IT <dbl>, ES <dbl>,
#> #   TR <dbl>, MA <dbl>, LY <dbl>, SA <dbl>
```
