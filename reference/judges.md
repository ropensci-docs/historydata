# Federal judges in the United States of America

This dataset contains information about the appointments and careers of
all federal judges in United States history since 1789. It includes
judges who "judges presidentially appointed during good behavior who
have served since 1789 on the U.S. District Courts, the U.S. Courts of
Appeals, the Supreme Court of the United States, the former U.S. Circuit
Courts, and the federal judiciary's courts of special jurisdiction."
Some of the unnecessary information from the source has been excluded.

## Format

Two data frames, `judges_people` and `judges_appointments`.

## Data frames

The data frame `judges_people` contains information about the judges,
such as names and vital information. The data frame
`judges_appointments` contains information about their appointments,
such as the name of the court, nominating president, and the dates of
service.

## References

This data is taken from the [Biographical Directory of Federal Judges,
1789-present](https://www.uscourts.gov/sites/default/files/allauth.pdf).

## Examples

``` r
data(judges_people)
data(judges_appointments)
```
