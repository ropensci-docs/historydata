# Records of missions held by the Paulist Fathers, 1851–1893

This dataset contains transcriptions of records of missions held in by
the Paulist Fathers, a Roman Catholic missionary order, in the
nineteenth-century United States. This dataset contains only the most
interesting data recorded in the full Paulist mission chronicles. The
founding members of the Paulist Fathers began as members of the
Redemptorist order. Their chronicles include both the missions held as
Redemptorists and as Paulists. This transcription only includes missions
up to the year 1893; the Paulist Chronicles contain more records than
are transcribed here, and the Paulists continued holding missions for
many more years than are recorded in the Chronicles.

## Usage

``` r
paulist_missions
```

## Format

A data frame with 841 observations of 17 variables.

## Variables

- `mission_number`: The number assigned to the mission in the Paulist
  Mission Chronicles.

- `church`: The name of the church or cathedral at which the mission was
  held.

- `city`, `state`: The location of the mission.

- `start_date`, `end_date`: The start and end dates of the mission as
  date objects.

- `year`: The year of the mission.

- `decade`: The decade of the mission (useful for faceting).

- `duration_days`, `duration_years`: The duration of the mission in days
  (as an integer) and in weeks (as an ordered factor).

- `confessions`: The number of confessions heard by the Paulists at the
  mission, which is a rough proxy for the number of people who attended
  the mission.

- `converts`: The total number of converts made during the mission and
  people left under instruction for conversion after the mission was
  over.

- `order`: Whether the mission was held under the Redemptorist or
  Paulist order.

- `lat`, `long`: The latitude and longitude of the city where the
  mission was held.

- `volume`, `page`: The location of the mission record in the Paulist
  mission chronicles.

## References

The Paulist missions are recorded in *Chronicle of the Missions Given by
the Congregation of Missionary Priests of St. Paul the Apostle*, six
manuscript volumes, Office of Paulist History and Archives, North
American Paulist Center, Washington, DC. Data transcribed by Lincoln
Mullen.

## Author

[Lincoln Mullen](https://lincolnmullen.com), George Mason University

## Examples

``` r
head(paulist_missions)
#> # A tibble: 6 × 17
#>   mission_number church           city  state date_start date_end    year decade
#>            <int> <chr>            <chr> <chr> <date>     <date>     <dbl> <chr> 
#> 1              1 St. Joseph's Ch… New … NY    1851-04-06 1851-04-20  1851 1850s 
#> 2              2 St. Michael's C… Lore… PA    1851-04-27 1851-05-11  1851 1850s 
#> 3              3 St. Mary's Chur… Holl… PA    1851-05-18 1851-05-28  1851 1850s 
#> 4              4 Church of St. J… John… PA    1851-05-31 1851-06-08  1851 1850s 
#> 5              5 St. Peter's Chu… New … NY    1851-09-28 1851-10-12  1851 1850s 
#> 6              6 St. Patrick's C… New … NY    1851-10-19 1851-11-03  1851 1850s 
#> # ℹ 9 more variables: duration_days <int>, duration_weeks <ord>,
#> #   confessions <int>, converts <int>, order <chr>, lat <dbl>, long <dbl>,
#> #   volume <int>, page <int>
```
