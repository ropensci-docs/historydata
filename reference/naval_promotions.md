# Promotions of U.S. Navy officers, 1798-1849

This dataset contains records of the careers of officers of the line in
the United States Navy who became midshipmen between 1798 and 1849. It
lists the dates at which officers were promoted to the ranks of
midshipment, lieutenant, master commandament, and captain.

## Usage

``` r
naval_promotions
```

## Format

A data frame with 5,705 observations of 4 variables.

## Variables

- `id`: A unique numeric identifier for each officer.

- `name`: Name of the officer.

- `generation`: A numeric value to represent a judgment about the
  generations within the officer corp of the U.S. Navy. First generation
  officers entered the service before 1801, as a rank higher than
  midshipman. Second generation officers entered the service before the
  Peace Establishment Act (or by the end of 1801), but as midshipman.
  Thus, they essentially became adults in the service, and they learned
  their craft from the first generation. Third generation officers
  entered the service as midshipmen after the Peace Establishment Act
  but before the end of the War of 1812. Those officers in this
  generation who became captain rose to that rank in the 1830s and '40s.
  Fourth generation officers entered the service after the War of 1812
  had ended. These officers saw almost no wartime service, and many of
  the ones who achieved captain found themselves having to decide
  whether to serve in the Union or the Confederacy during the Civil War.

- `rank`: The ranks which officers obtained, including `midshipman`,
  `lieutenant`, `master_commandant`, and `captain`. Also included are
  the dates some officers `left_service`.

- `date`: The date as a character string on which an officer attained
  the associated rank.

## References

This data was compiled by Abby Mullen from Edward W. Callahan, *Officers
of the Continental and U.S. Navy and Marine Corps, 1775-1900* (New York:
L. R. Hamersly, 1901), made available via the Naval Historical Center,
<https://www.ibiblio.org/hyperwar/NHC/Callahan/index.htm>. See Mullen's
blog post about compiling the data, "[Database of Officers of the
Line](https://abbymullen.org/database-of-officers-of-the-line/),"
abbymullen.org, January 5, 2013.

## Author

[Abby Mullen](https://abbymullen.org/), Northeastern University

Edward W. Callahan

## Examples

``` r
head(naval_promotions)
#> # A tibble: 6 × 5
#>      id name               generation rank       date      
#>   <int> <chr>                   <int> <fct>      <chr>     
#> 1     1 Abbot, Joel                 3 midshipman 1812-06-18
#> 2     2 Abbot, Trevett              4 midshipman 1848-10-13
#> 3     3 Abbott, Isaac               4 midshipman 1820-05-10
#> 4     4 Abbott, J. Francis          4 midshipman 1837-12-27
#> 5     5 Abbott, James W.            4 midshipman 1822-05-01
#> 6     6 Abbott, Thomas C.           3 midshipman 1814-12-06
```
