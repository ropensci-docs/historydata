# Wholesale Market Prices in Dijon, France 1568–1630

These are wholesale market prices in the city of Dijon in Burgundy in
central France from 1568 to 1630. They include the major cereal grains,
different qualities of wine, dried legumes, oils used for cooking,
seeds, and candle wax made from beef tallow. All prices were generally
recorded by the city council at the same time of year on the first
market day after the feast of St. Martin (November 11). All prices are
in *sous tournois* / 20 *sous* = 1 *livre tournois*.

## Usage

``` r
dijon_prices

dijon_prices_wide
```

## Format

`dijon_prices` is a data frame with 1,110 observations of 6 variables.
`dijon_prices_wide` is a data frame with 19 observations of 65
variables. `dijon_prices_wide` contains the data as it was transcribed;
that data has been converted to a tidy format in `dijon_prices`.

An object of class `tbl_df` (inherits from `tbl`, `data.frame`) with 19
rows and 65 columns.

## Variables

- `commodity`: the commodity for sale

- `measure`: the amount of the commodity for that price

- `price`: the price in *sous tournais*.

- `citation`, `citation_date`: citations and dates for documents in the
  Archives municipales de Dijon.

## References

All citations are to the Archives municipales de Dijon. See the columns
`citation` and `citation_date` in `dijon_prices` for the documents from
which each price was gathered.

## Author

Mack Holt, George Mason University
